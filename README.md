# usecase-activity-collaborative-diagrams
The project consists of a use case,collaborative and activity diagram for the following scenario.
## scenario
Design a use case,activity diagram and collaborative diagram.
A system that can enable church members to login to an online service and give offerings and enable members see their contribution.
### Use case diagram
![usecase](https://github.com/kayikalvin/usecase-activity-collaborative-diagrams/blob/main/imgs/use%20case.drawio.png)
<br>

### Actors:
1.	Church Member: A user who can create an account, log in, give offerings, and view contributions.
2.	System: The online service providing these functionalities.
Use Cases:
1.	Create Account: Church members who don’t have an account can create one.
2.	Login: After creating an account, members can log in.
3.	Give Offering: Logged-in members can make financial contributions.
4. 	View Contributions: Logged-in members can view their contribution history.

### collaborative diagram
![collaborative](https://github.com/kayikalvin/usecase-activity-collaborative-diagrams/blob/main/imgs/activity.drawio.png)
<br>
### Objects:
1.	Church Member
2.	Account Creation Module
3.	Login System
4.	Offering Module
5.	Payment Processor
6.	Contribution Database


### Activity diagram
![activity](https://github.com/kayikalvin/usecase-activity-collaborative-diagrams/blob/main/imgs/activity.drawio.png)
1.	Start
2.	Check if Account Exists
- If No:
	- Create Account
	- input personal details
	- Set up login credentials
	- Confirm account creation
	- Login to System
	- Input credentials
	- Validate credentials
	- Display dashboard
- If Yes:
	- Login to System
	- Input credentials
	- Validate credentials
	- Display dashboard
3.	Select "Give Offering"
-	Input donation amount
-	Choose payment method
-	Confirm payment
4.	Process Payment
-	Validate payment details
-	Process transaction
-	Update contribution record
5.	Confirmation Message
6.	Optionally, View Contributions
o	Display contribution history
7.	End


