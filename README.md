# GiftCardManagementApp
Spring Boot Micro service with Angular App
	
	@Getter
@Setter
@NoArgsConstructor
@ToString
@JsonAutoDetect(fieldVisibility = JsonAutoDetect.Visibility.ANY)
public class cardUserTransactions implements Serializable {
	
	private long cardNumber;
	private String CreditedTo;
	private String location;
	@DateTimeFormat(pattern = "dd.MM.yyyy HH:mm:ss")
	private Date TransactionTime;
	
	private String Amount;
	
	private String Currency;
	
	public cardUserTransactions(long cardNumber,String CreditedTo, Date date,String location, String Amount, String currency) {
		this.CreditedTo=CreditedTo;
		this.TransactionTime=date;
		this.location=location;
		this.Amount=Amount;
		this.Currency=currency;
		this.cardNumber=cardNumber;
	}

	
	
	
	public long getCardNumber() {
		return cardNumber;
	}




	public void setCardNumber(long cardNumber) {
		this.cardNumber = cardNumber;
	}




	public String getCreditedTo() {
		return CreditedTo;
	}




	public void setCreditedTo(String creditedTo) {
		CreditedTo = creditedTo;
	}



	@DateTimeFormat(pattern = "dd/MM/yyyy h:mm a")
	public Date getTransactionTime() {
		return TransactionTime;
	}




	public void setTransactionTime(Date transactionTime) {
		TransactionTime = transactionTime;
	}




	public String getAmount() {
		return Amount;
	}




	public void setAmount(String amount) {
		Amount = amount;
	}




	public String getCurrency() {
		return Currency;
	}




	public void setCurrency(String currency) {
		Currency = currency;
	}




	@Override
	public String toString() {
		return "cardUserTransactions [cardNumber=" + cardNumber + ", CreditedTo=" + CreditedTo + ", TransactionTime="
				+ TransactionTime + ", Amount=" + Amount + ", Currency=" + Currency + "]";
	}




}

