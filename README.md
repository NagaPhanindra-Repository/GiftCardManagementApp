# GiftCardManagementApp
Spring Boot Micro service with Angular App
	
	Stream<cardUserTransactions> stream=Stream.of(new cardUserTransactions(8978787829l,"Purchase   - Mari De ville & Resort MOTEL MO ",new Date("02/07/2020 10:20 AM"),"Mari de ville MOTEL 1876 West County MO USA","670.00 USD","660.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Pharmacie de la Place de la République",new Date("09/04/2020 01:15 PM"),"5 Place de la République, 75003 Paris, France","61.00 USD","46.90 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Victoria Pharmacy Drive-through",new Date("09/01/2020 03:10 PM"),"58 Horseferry Road Westminster London SW1P 2AF United Kingdom","013.12 CHF","10.00 EUR"),
			
			new cardUserTransactions(8978787829l,"Purchase   -StarBucks Time Square INC",new Date("09/01/2020 04:00 AM"),"4523 Flox Plaza - Time Square NYC NJ USA","25.00 USD","12.00 EUR"),
			
			new cardUserTransactions(8978787829l,"Withdrawal  -CASH WITHDRAW HSBC MACHINE:HSBC",new Date("09/02/2020 09:20 PM"),"4413 HSBC - FrankFurt DR London UK","40.00 CHF","30.00 EUR"),  
			new cardUserTransactions(8978787829l,"Purchase   -Westfield Forum des Halles",new Date("09/02/2020 09:20 PM"),"101 Porte, Rue Berger, 75001 Paris, France","10.00 USD","07.00 EUR"),
			
			
			new cardUserTransactions(8978787829l,"Purchase   -Duck&Donuts",new Date("09/02/2020 09:20 PM"),"Chesterfield - MO","10.00 USD","07.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -NVC Pharma INC",new Date("09/02/2020 09:20 PM"),"46 Baker Street London W1U 7BR United Kingdom","101.00 USD","07.00 EUR"),
			
			
			new cardUserTransactions(8978787829l,"Purchase   -Dunkin Donuts",new Date("09/03/2020 03:10 PM"),"CauseWay St - Boston","013.12 CHF","10.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Victoria Pharmacy Drive-through",new Date("09/03/2020 03:10 PM"),"58 Horseferry Road Westminster London SW1P 2AF United Kingdom","013.12 CHF","10.00 EUR"),
			
			
			new cardUserTransactions(8978787829l,"Purchase   -Taco Bell",new Date("09/04/2020 01:15 PM"),"Boylston St - CANADA","61.00 USD","46.90 EUR"),
			
			new cardUserTransactions(8978787829l,"Purchase   -Gould Pharmacy Walk-in",new Date("09/02/2020 09:20 PM"),"37 North Audley Street Mayfair London W1K 6ZLUnited Kingdom","101.00 USD","07.00 EUR"),
			
			
			new cardUserTransactions(8978787829l,"Purchase   -Pasta House",new Date("09/08/2020 10:20 PM"),"Independence DR - MO","22.95 USD","29.00 EUR"),
			new cardUserTransactions(8978787829l,"Card Loading Swiss Bankers",new Date("09/03/2020 11:20 AM"),"Commerce Bank - SFO","200.00 USD","350.00 EUR"),	
            new cardUserTransactions(8978787829l,"Purchase   - InterContinental Miami",new Date("09/07/2020 10:20 AM"),"100 Chopin Plaza, Miami, FL","78.00 USD","29.00EUR"),
            new cardUserTransactions(8978787829l,"Purchase   - Honey Creek Resort",new Date("09/08/2020 09:20 PM"),"12633 Resort Dr, Moravia, IA","34.00 CHF","27.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Federal Reserve Member Bank:SO",new Date("09/04/2020 09:20 PM"),"6985 S Union Park Ctr, Midvale, Utah","100.00 EUR","100.70 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH WITHDRAW FROM STATE STREET CORP MACHINE:RE",new Date("09/02/2020 09:20 PM"),"BOSTON, MA","49.00 USD","30.98 EUR"),   
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM BMO FNCL CORP ATM:SO",new Date("09/01/2020 09:20 PM"),"CHICAGO, IL","70.00 EUR","100.70 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH WITHDRAW FROM FIRST HORIZON BK MACHINE:RE",new Date("09/03/2020 09:20 PM"),"MEMPHIS, TN - London ","40.00 CHF","30.00 EUR"),  
			new cardUserTransactions(8978787829l,"Purchase   - Walmart Supercenter",new Date("01/07/2020 10:20 AM"),"2196 Emporium Dr, Jackson, TN","200.00 CHF","200.10 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Bielany Retail Shopping",new Date("07/08/2020 09:20 PM"),"Baxter Wroclaw St, Poland","34.00 USD","44.67 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE BOFA ATM",new Date("07/09/2020 09:20 PM"),"Just post DR Bank of America, MO","100.00 CHF","99.17 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Walmart Pharmacy",new Date("07/01/2020 09:20 PM"),"1851 KY-192 W, London, KY","98.00 USD","25.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Walgreens America LLP",new Date("07/02/2020 09:20 PM"),"330 Clarke Rd, SFO, CA","50.00 USD","75.00EUR"),	
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM OLD NB MACHINE ",new Date("07/03/2020 09:20 PM"),"5985 King St Riverside-Albert, Canada","56.00 CHF","67.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE BOSTON PRIVATE B&TC MACHINE",new Date("07/04/2020 09:20 PM"),"West Pkwy, BOSTON, MA ","35.00 CHF","86.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Walmart stores.INC",new Date("07/05/2020 09:20 PM"),"2700 Ridge Point Dr, High Ridge, MO","58.00 USD","34.70 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Frost Bank",new Date("07/06/2020 09:20 PM"),"11555 Bandera Rd, San Antonio, TX ","49.00 CHF","49.87 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Target America LLP",new Date("08/07/2020 09:20 PM"),"WestMount Mall- Madison - WI ","95.00 USD","21.23EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Macys",new Date("09/07/2020 09:20 PM")," 4190 State Hwy K, O'Fallon, MO","200.00 USD","202.00EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Jefferson Bank & Trust MACHINE",new Date("06/07/2020 09:20 PM"),"DZ Bank - Frankfurt ","404.00 CHF","100.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM U.S. Bank ATM",new Date("05/07/2020 09:20 PM"),"U.S Bank, Charlotte, NC ","67.00 CHF","34.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Office Max",new Date("06/01/2020 09:20 PM"),"12140 W Burleigh Rd, Wauwatosa, WI","200.00 USD","202.00EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM TD Bank MACHINE",new Date("06/02/2020 09:20 PM"),"2570 NJ-37 Suite A, Manchester Township, NJ","400.00 CHF","60.98 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Wendy's",new Date("06/03/2020 09:20 PM"),"4210 State Khimki, Moscow ","35.00 USD","25.00EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Bank of America Financial Center ATM  ",new Date("06/04/2020 09:20 PM"),"555 Broadway, Millbrae, CA","100.09 CHF","98.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Express",new Date("06/05/2020 09:20 PM"),"447 Great Mall Dr, Milpitas, CA ","140.00 USD","56.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Capital One  MACHINE",new Date("06/06/2020 09:20 PM"),"13236 Gateway Center Dr, Gainesville, VA ","50.76 CHF","36.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - H&M",new Date("06/07/2020 09:20 PM")," 7007 Friars Rd, San Diego, CA","500.00 USD","250.00EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM TIAA ATM",new Date("06/08/2020 09:20 PM"),"411 Lafayette St Floor 6, New York, NY","4.00 CHF","45.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Maurices",new Date("06/09/2020 09:20 PM"),"220 Boardwalk Blvd Bldg. H, Bossier City, LA","200.00 USD","202.00EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM J.P. Morgan Private Bank MACHINE",new Date("06/10/2020 09:20 PM"),"800 Connecticut Ave NW 9th Floor, Washington, DC","410.00 CHF","200.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Talbots",new Date("06/11/2020 09:20 PM"),"1 Walden Galleria, Buffalo, NY","59.29 USD","45.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM BMO Harris MACHINE",new Date("06/12/2020 09:20 PM"),"99 W Washington St, Chicago, IL ","20.00 CHF","56.87 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Klutch",new Date("06/13/2020 09:20 PM")," 3211 Frederica St c, Owensboro, KY","24.00 USD","12.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Papaya",new Date("06/14/2020 09:20 PM")," 500 Lakewood Center Mall, Lakewood, CA ","199.00 USD","158.00EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM State Farm ATM",new Date("06/15/2020 09:20 PM")," 2709 Godfrey Rd, Godfrey, IL","30.00 CHF","12.12 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM USAA MACHINE",new Date("06/16/2020 09:20 PM"),"7300 Parkwood Blvd &, Legacy Dr, Plano, TX","40.00 CHF","50.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Cato",new Date("06/17/2020 09:20 PM"),"Greater Manchester, England ","78.00 USD","220.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Rainbow Shops",new Date("06/18/2020 09:20 PM"),"Zaragoza - Spain","1000.00 USD","150.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM MUFG Union Bank MACHINE",new Date("06/19/2020 09:20 PM")," 1251 6th Ave, New York, NY ","60.93 CHF","43.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE UBS ATM",new Date("06/20/2020 09:20 PM"),"5007 Horizons Dr, Columbus, OH","26.14 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM M&T Bank MACHINE",new Date("06/21/2020 09:20 PM"),"3037 Bailey Ave, Buffalo, NY","19.00 CHF","31.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Tranquility Bay Beachfront Hotel & Resort",new Date("03/07/2020 10:20 AM"),"2600 Overseas Hwy, Marathon, FL ","129.00 USD","100.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Luxor Hotel & Casino",new Date("08/08/2020 03:00 PM"),"3900 S Las Vegas Blvd, Las Vegas, NV","34.00 CHF","27.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM The Bank Of Italy ATM:SO",new Date("05/04/2020 08:20 PM")," 39 King St, London EC2V 8JJ, United Kingdom","100.00 EUR","100.70 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Shinhan Bank London Branch ATM:RE",new Date("06/02/2020 01:00 PM"),"77 Gracechurch St, Langbourn, London","4.00 USD","3.98 EUR"),   
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM  Metro Bank ATM :SO",new Date("04/01/2020 11:20 AM"),"227 Tottenham Court Rd, Bloomsbury, London","100.00 EUR","100.70 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM HSBC ATM:RE",new Date("10/08/2019 10:40 AM"),"Lion House, 25 Islington High St, The Angel, London  ","40.00 CHF","30.00 EUR"), 
			new cardUserTransactions(8978787829l,"Purchase    -Walmart Auto Care Centers",new Date("03/07/2020 10:20 AM"),"1851 Highway 192 W, London, KY","89.00 CHF","19.10 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Bielany Retail Shopping",new Date("07/08/2020 04:20 PM"),"Baxter Wroclaw RD - Poland","34.00 USD","44.67 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE Union Bancaire Privée MACHINE",new Date("07/09/2020 05:20 PM"),"26 Seymour Mews, Marylebone, London","100.00 CHF","99.17 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Walmart stores.INC",new Date("07/01/2020 06:20 AM"),"1275 Highbury Ave N, London","238.00 USD","176.90 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - China Merchants Bank London Branch",new Date("07/02/2020 09:20 PM"),"18th floor, 20 Fenchurch St, Bridge, London","200.00 USD","202.00EUR"),	
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM PNC Bank ATM",new Date("07/03/2020 09:20 PM"),"1642 Bryan Rd, O'Fallon, MO","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM St Johns Bank ATM",new Date("07/04/2020 09:20 PM"),"2897 State Hwy K, Indiana","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - CVS",new Date("07/05/2020 09:20 PM"),"1580 Bryan Rd, O'Fallon, MO","16.76 USD","20.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM RB ATM",new Date("07/06/2020 09:20 PM"),"RabncoBank pkwy - Utrecht ","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Target America LLP",new Date("08/07/2020 09:20 PM"),"22- South WestMount Mall- Madison, WI ","150.00 USD","50.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Macys",new Date("09/07/2020 09:20 PM"),"104 White Oaks Mall, Springfield, IL","90.00 USD","79.22 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM DZ BANK MACHINE",new Date("06/07/2020 09:20 PM"),"100 Park Ave, New York, NY 10017","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Truist Financial ATM",new Date("05/07/2020 09:20 PM"),"24 Lombard St, Candlewick, London","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Office Max",new Date("08/24/2019 09:20 PM"),"1824 HIGHWAY 192 WEST, London, KY","75.00 USD","22.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Bank of Canada MACHINE",new Date("06/02/2020 09:20 PM"),"234 Wellington St. W, Ottawa, ON K1A 0G9, Canada","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - McDonalds",new Date("04/03/2020 09:20 PM"),"1 McDonald's Place, Toronto, ON ","34.00 USD","15.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Canadian Tire Bank  MACHINE",new Date("06/04/2020 09:20 PM"),"3475 Superior Ct, Oakville, ON","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Express",new Date("05/06/2020 09:20 PM"),"250 WGreat MALL - CA ","130.00 USD","29.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Exchange Bank of Canada MACHINE",new Date("06/06/2020 09:20 PM"),"CExchange Bank of Canada, ON ","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - H&M",new Date("06/07/2020 09:20 PM"),"8882 170 St NW, Edmonton, AB T5T 4M2, Canada","22.00 USD","67.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM Adam Hautly Thrivent Financial MACHINE",new Date("06/08/2020 09:20 PM"),"325 N Kirkwood Rd UNIT 104, Kirkwood, MO","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Maurices",new Date("02/10/2020 09:20 PM"),"941 North, IL-3, Waterloo, IL ","53.00 USD","44.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE FROM CIBC Banking Center MACHINE",new Date("06/10/2020 09:20 PM"),"502 W Mondamin St, Minooka, IL","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   - Talbots",new Date("07/11/2020 09:20 PM"),"6520 N Illinois St #105, Fairview Heights, IL","11.00 USD","32.00 EUR"),
			new cardUserTransactions(8978787829l,"Withdrawal  - CASH ADVANCE From Wealth One Bank of Canada MACHINE",new Date("06/12/2020 09:20 PM"),"Canada, Ontario, Markham, Gibson Dr","40.00 CHF","30.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -MG Women",new Date("02/26/2020 10:00 AM"),"STITCH FIX Online Shopping","10.00 USD","05.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Kasper",new Date("06/01/2020 09:20 PM"),"3255 Hwy 7, Markham, ON","86.00 USD","09.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Evereve",new Date("03/19/2020 09:20 AM"),"5101 Hinkleville Rd, Paducah, KY ","07.12 CHF","05.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Ann Taylor",new Date("05/12/2020 09:20 PM"),"Metropolis - Metrotown -CANADA","45.00 USD","22.90 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Altard's State",new Date("01/01/2020 09:20 AM")," Mississauga, ON L5B 4C1, Canada","04.95 USD","56.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase -Sole & Blues",new Date("06/29/2020 09:20 PM"),"2370 North Expressway, Brownsville, TX","37.00 USD","89.89 EUR"),
			new cardUserTransactions(8978787829l,"Purchase -Dry Goods",new Date("10/15/2019 09:20 PM"),"26 St Mid Way, Sherman","15.00 CHF","09.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Forever21",new Date("09/04/2019 09:20 PM"),"2205 Veterans Blvd, Del Rio, TX ","91.00 CHF","67.98 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Ross",new Date("12/31/2019 09:20 AM"),"300 Early Blvd, Early, TX","89.00 UDS","13.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Love Culture",new Date("04/06/2020 09:20 PM"),"800 N Navarro St, Victoria, TX ","207.00 USD","29.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Nordstrom",new Date("04/07/2020 09:20 PM"),"303 Memorial City Way, Houston, TX ","300.00 USD","38.00 EUR"),
			new cardUserTransactions(8978787829l,"Drury Plaza Hotel ",new Date("08/08/2020 09:20 PM"),"2 S 4th St, St. Louis, MO","108.00 CHF","90.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Old Navy",new Date("09/08/2020 09:20 PM"),"7051 S Desert Blvd, Canutillo, TX","800.00 USD","700.00 EUR"),
			new cardUserTransactions(8978787829l,"Quality Inn MOtel ",new Date("09/01/2020 09:20 PM")," 205 BayPoint PWY - CA", "90.00 USD","40.89 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -CeCi",new Date("11/07/2019 09:20 PM"),"5400 W Parmer Ln, Austin, TX ","76.00 CHF","12.00 EUR"),
			new cardUserTransactions(8978787829l,"CASH ADVANCE FROM Texas Capital Bank MACHINE",new Date("08/07/2019 09:20 AM"),"707 W Algonquin Rd, Arlington Heights, IL","304.00 CHF","99.96 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Windsor",new Date("04/07/2019 09:20 AM"),"Scarborough - Ontario","300.00 USD","38.00 EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Kohl's",new Date("08/09/2019 09:20 PM"),"West Edmonton RD, Alberta","35.00 USD","38.00 EUR"),
			new cardUserTransactions(8978787829l,"CASH ADVANCE FROM Credit Suisse MACHINE",new Date("01/04/2019 09:20 PM"),"1 Federal St, Boston, MA","45.00 CHF","89.00EUR"),
			new cardUserTransactions(8978787829l,"Purchase   -Pay Less",new Date("09/07/2019 09:20 AM"),"Vauxhall RD -22, London","20.00 USD","38.00 EUR"),
	        new cardUserTransactions(8978787829l,"Purchase   -StarBucks",new Date("03/26/2020 04:00 AM"),"2121 Avenue of the Stars, Los Angeles, CA","25.00 USD","12.00 EUR"),
	        new cardUserTransactions(8978787829l,"Purchase   -Duck&Donuts",new Date("07/01/2020 09:20 PM"),"Chesterfield - MO","10.00 USD","07.00 EUR"),
	        new cardUserTransactions(8978787829l,"Purchase   -Dunkin Donuts",new Date("03/19/2020 03:10 PM"),"CauseWay St - Boston","013.12 CHF","10.00 EUR"),
	        new cardUserTransactions(8978787829l,"Purchase   -Taco Bell",new Date("01/30/2020 01:15 PM"),"Boylston St - CANADA","61.00 USD","46.90 EUR"),
	        new cardUserTransactions(8978787829l,"Purchase   -Pasta House",new Date("08/08/2019 10:20 PM"),"Independence DR - MO","22.95 USD","29.00 EUR")
			);
		




	List<cardUserTransactions> Slist=stream.collect(Collectors.toList());
		
	        public List<cardUserTransactions> getAllTransactions(){
		    return Slist;
		
	        }


		public List<cardUserTransactions> getLastFiftyTransactions(){
			List<cardUserTransactions> Slist2=Slist.stream().sorted(Comparator.comparing(cardUserTransactions::getTransactionTime).reversed()).collect(Collectors.toList());
			List<cardUserTransactions> myLast50Transactions = Slist2.stream().limit(50).collect(Collectors.toList());
			//List<cardUserTransactions> myLast50Transactions = Slist2.subList(Slist2.size()-Math.min(Slist2.size(),50), Slist2.size());
			//return Slist2;
			
			return myLast50Transactions;
			
		}
		
		public  List<cardUserTransactions> getCurrentTransactions() {
			
			 LocalDate currentDate = LocalDate.now();
			    int month=currentDate.getMonthValue();
			List<cardUserTransactions> CurrentTransactionWithoutSort =Slist.stream()
	        .filter(cardUserTransactions -> cardUserTransactions.getTransactionTime().getMonth()==month-1).collect(Collectors.toList());
			
			
			List<cardUserTransactions> myCurrentTransactions=CurrentTransactionWithoutSort.stream().sorted(Comparator.comparing(cardUserTransactions::getTransactionTime).reversed()).collect(Collectors.toList());
			
			
			return myCurrentTransactions;
	        
			
		}
		
		
		public  CardUser getCardUserdetails() {
			
			CardUser CurrentUser=new CardUser("8978787829","EUR 721.78");
			return CurrentUser;
		}
