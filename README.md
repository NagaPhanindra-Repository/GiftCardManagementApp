# GiftCardManagementApp
Spring Boot Micro service with Angular App
	
	@CrossOrigin(origins = "*")
@RestController
@RequestMapping("/GiftCardManagement/api/v1")
public class BasicAuthController {
	
	@GetMapping(path = "/basicauth")
    public AuthenticationBean basicauth() {
		System.out.println("You are authenticated");
        return new AuthenticationBean("You are authenticated");
    }
	@GetMapping(path = "/cardUserDeatils")
    public CardUser cardUserDeatils() {
		UserTransactionService trasactionService=new UserTransactionService();
		System.out.println("getCardUserdetails"+trasactionService.getCardUserdetails().getCardNumber());
		CardUser CurrentUser=trasactionService.getCardUserdetails();
		return CurrentUser;
		
    }
	

}
