Ayesha Beauty Creation is a Kamanjab based manufacturer in the Beauty, Personal Care, and Cosmetic sector that has distributors ranging from Dischem Pharmacies Namibia and PnP Namibian Stores. The manufacturer is solely comprised of females and together with the knowledge from Namibian generations have constantly been transforming the beauty sector.

Ayesha Beauty Creation despite its quest for revolutionising the beauty sector it faces some challenges. 
The manufacturer solely uses a paper-based system for all its transactions and a filing system for its storage. At the end of a day, the manager collects the money made during that day and record it in a record counter book. This is time consuming as the manager reads through all the receipts to check for trending products, to check whether the transactions were correctly executed and overall analyse the progress of the business. 
This is very labour intensive, inaccurate, and inefficient as records of many weeks or a month must be tracked back manually through the filing system.
At the cashier point where customers buy their beauty products, the cashier manually keys in the quantity of products and their prices using a calculator, there is a poster of all the products with their respective prices although it does not show the reorder levels.
This process is cumbersome especially on a busy day hence the customers end up being frustrated waiting in long queues and the employees end up lacking motivation.

When a new product is shelved, each product is given a sticky label of the price. This is done by the store keepers on Fridays when new goods are delivered from supplying unit. The manager sets the prices as per manufacturer's instructions. The store keepers then records the number of stock placed on the shelves and are also responsible for replacing goods once the they see the product levels are lowered or once re-stock level has reached. The manager signs an inventory  form from the store keepers to verify permission to shelf goods.

The manager weekly has to check through the filing cabinet to re-arrange the invoices and also to do calculations and analysis of credits and debits with a calculator and scrap paper which he places in his drawers. The papers get disorganised so he fails to make payments to the distributors, he is charged greater interest which distorts his budget. Poor customer service is rendered which causes trusted customers to lose credibility in the Ayesha Beauty Creation as the customers wait for a long period to recieve their orders and as a result the customers have been suggesting for Ayesha to computarise their current system.
 
Once invoices are paid, they are stored in a docket and thrown away after a month because there is no physical storage space left. Invoice payments are then recorded as cheques and a copy is kept in ink-copy books. From this progress of the business can be analysed with a calculator and manually drawn charts so the information is often inaccurate. This task is very monotonous for the manager.

As a result, Ayesha has decided to computarise its current paper-based system to an application. The application will be able to fully automate its processes hence increasing customer service, financial transactions and also improving the relations of the employees. 

The system will be an intergration of a website that enhances customer intimacy and a database application for the internal operations of Ayesha's day to day activities.
The website will be mainly used by customers to order, rate and review different products hence this information will be essential to Ayesha as they are able to know the different drawbacks on different products and most liked or ordered products hence aiding in the creation of indivisualised advertising campeigns. 
The information from custoemers will also allow Ayesha to evaluate the different location of customers and the most preferred products in each location hence allowing them produce products targeting that specific region and also work on their marketing strategies in other regions.

The website will also act as a link between foreign clients and Ayesha as it will be able to reach a wider audience.

The new computerised system will help Ayesha Beauty Creation: 
1. saves resources as of the stationery used
2. reduce errors during the payment of employees and calculations as the system will be able to automatically calculate this
3. save on storage space as the system will have a storage capability hence more room for working for the employees.
4. provide levels of access amongst employees to ensure that some information is only accessible by the manager. 
5. have a platform where customers will provide their reviews on a certain product and their information will be used for individualised sales campaigns. 
6. generate balance sheet reports, Return On Investment Reports.
7. have a search function to reduce time spent looking for a certain product's information.
8. provide suggestions on new products as per trend information collected from customers'reviews and likes.
9. Increase the workking motivation of the Ayesha company as no monotonous, cumbersome work will be done by employees.
10. Money theft within the departments will be reduced.

Due to the above stated reasons, the Ayesha Beauty Creation Software will be comprised of different modules that aid it in executing its predefined roles.
The modules will be as follows:
1. User module: this module will allow the manager to add, delete, edit a user and as well as an employee.
2. Transaction module: this module will have submodules of inventory and sales transactions which are the Point of sales and Re-stock operations.
3. Distributor module: the module will have the information of the distributors of the Ayesha products and allows for the insertion, deletion and updation of information.
4. Product module: the module will allow for the insertion, deletion and updation of the product's information in the system.
5. Payroll module: the module will be responsible for the calculation of employees'salaries, ensuring that each employee receives their fair share of payment.
6. Report module: the module will be responsible for the creation of reports regarding overall transactions,product history, pay slips and customers'recommendations.
7. Customer module: the module will have the customers'information ranging from their frequent products that they buy to the suggestions regarding how the business can optimise its intemacy with its customers.

As per module there will be operations carried out on certain data structures and those operations are outline below: 
1. returnOnInvestment(), this function calculates the gross income of the business by subtracting all its expenses from its income to see the green light progression of the business.
2. managerSalary(), this is used in the calculation of the manager's payment as he has a different rate from other employees.
3. generalSalary(), used to calculate the employees' payments.
4. new(), edit(), delete(), this are the main functions for the insertion, updation, deletion of customers', employees's, distributor's and products'information.

By implementing the above procedures on the modules, efficiency and transperency will be depicted in the Ayesha system as its operations will be maximised with less minimul errors.


Pseudocodes
	Login 
     Start
String Employee [20][20]
username, password, 
attempt=0
Do While(attempt<3)
Prompt username, password
Get username, password
If (username, password==Employees [] []) then
Display “Login Successful”
Attempt=3
	Else
Display “Wrong username, or password”
Attempt=attempt+1
System redirect to Main Menu window
           EndIf
EndDo
Stop.

	Sales Transaction
Start
vat=0.15
search product
	If product is available then
Prompt quantity
		Get  quantity
		subtotal=quantity*price
		balance= (subtotal*vat) + subtotal
		Display “product, quantity, balance”
		Get cash
		If cash>balance then
		change=cash-balance
RemainingStock= remainingStock-quantity
		Get ReorderLevel
If (remainingStock<ReorderLevel) then 
			Display “Product out of Stock, please Reorder”
			EndIf
		Else 
		Display “Error, cash entered is not enough”
EndIf
Else
Display “Product not found”
EndIf
Stop.

	Inventory Transactions 
Start
Navigate to product
Enter reOrderLevel
If choice=updateReOrderLevel    then
	Enter newReorderLevel
	Enter newTargetLevel
	Enter newRemainingStock {This is when new products have been ordered}
If remainingStock<reOrderLevel then
	Output “Product has to be reordered”
	Generate ReOrder-Report
EndIf
EndIf
Stop.

	Products
Begin
Choose add, update, delete
If choice=add then
	Enter ProductCode, Category, Name,
	Enter quantityPerUnit, CostPrice, SellingPrice, Supplier
	Enter targetLevel
endif
If choice=Update
	Navigate to product
	Edit field
	Output “The field has been modified”
Endif
If choice=Delete then
	Navigate to product
	Delete product
	{This will also affect the inventory details}
End.

	Distributor’s details
Begin
Choose add, update, delete
If choice=add then
	Enter ShippingCompanyID, Name,
	Enter Representative, Address, City, ZipCode
	Enter phoneNumber, Fax
endif
If choice=Update
	Navigate to ShippingCompany
	Edit field
	Output “The field has been modified”
Endif
If choice=Delete then
	Navigate to ShippingCompany
	Delete ShippingCompany
End.
                               
	Investment
Start
totalExpenses, totalIncome
Get totalExpenses, totalIncome
returnOnInvestment()
Stop. 

	User management 
Start
1= “New”
2= “Edit”
3= “Delete”
4= “New Employee”
5= “Update Employee”
6= “Delete Employee”
Get position, password
Login as  manager
If position<> ”Manager” then
Output ”You need to be a manager to access this option”
     Else
	Output” Welcome to the edit account form.”
      Endif
Get choice
Case (choice){
1: new()
2: edit()
3: delete()
4: newEmployee()
5: updateEmployee()
6: deleteEmployee()
Default: Display “Input correct choice”
EndCase
Stop.

	Payroll
salary=0
hoursWorked=0
Start
1= “Manager”
2= “General Employee”
Get choice 
Case (choice){ 
1: managerSalary()
2: genericSalary()
Default: Display “Invalid choice”
EndCase
Stop. 

Functions
returnOnInvestment(totalExpenses,totalIncome){
		roi=((totalIncome-totalExpenses)/totalExpeses)*100
			Display “The Return On Investment is,roi,%”
} 

managerSalary(s,t){ 
	salary=(hoursWorked*60)
	display salary
}


generalSalary(u,v){
	salary= (hoursWorked*40)
	display salary
}

new(a,b){
Click Create new record button
	Create record 
Prompt username, password
Get username,password
	save record
	Display “Record has been saved”
}

Edit(x,y){
Click edit record button
	Navigate to record 
edit username, password
	save records
	Output” The account change has been computed” 
}

Delete(p,q){
Click delete record button
	Navigate to record 
Delete account
	save records
	Output” The account change has been deleted” 
}



newEmployee(j,k,l,m,n){
Prompt firstName, surname, position, contactNumber
	Get  firstName, surname, position, contactNumber
	Display “Enter either Male or Female for gender!”
	Prompt gender
	Get gender
}
updateEmployee(){
	Navigate to employee
	Edit field 
	Output “Employee has been modified”
}
deleteEmployee(){
	Navigate to Employee
	Delete record
	}





