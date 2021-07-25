# GiftCardManagementApp
Spring Boot Micro service with Angular App
	
	import java.util.ArrayList;
import java.util.List;
import java.util.concurrent.atomic.AtomicLong;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.actuate.health.Health;
import org.springframework.context.annotation.Bean;
import org.springframework.web.bind.annotation.CrossOrigin;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RequestParam;
import org.springframework.web.bind.annotation.RestController;

import com.mastercard.giftcard.model.CardUser;
import com.mastercard.giftcard.model.cardUserTransactions;
import com.mastercard.giftcard.service.ApplicationHealthIndicator;
import com.mastercard.giftcard.service.UserTransactionService;

@CrossOrigin(origins = "*")
@RestController
@RequestMapping("/GiftCardManagement/api/v1")
public class UserLoginController {
	  
	UserTransactionService userService=new UserTransactionService();
	
	@Autowired
	ApplicationHealthIndicator healthIndicator;
	   
    @GetMapping("/LastFiftyTransactions")		   
    public List<cardUserTransactions> getTransactions() {
    	
    	
    	return   userService.getLastFiftyTransactions();
    }
    
    @GetMapping("/Transactions")		   
    public List<cardUserTransactions> getTransactionsd() {
    	
    	
    	return   userService.getAllTransactions();
    }
    
    @GetMapping("/CurrentTransactions")		   
    public List<cardUserTransactions> getCurrentTransactions() {
    	
    	
    	return   userService.getCurrentTransactions();
    }

    @GetMapping("/HealthStatus")		   
    public Health getApplicationHealthStatus() {
    	System.out.println("################Health##########");
    	
    	return   healthIndicator.health();
    }   
	    


}
