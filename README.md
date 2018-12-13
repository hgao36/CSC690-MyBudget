# MyBudget
My Budget
- Author: Huawei Gao 917974036
- Code Reviewer: Xiaoqian Huang

# proposal

## Must-have features [estimated work load: 25 hours]

-Record your expense (done)

-Create categories for sorting the  (done)

-Show detailed information for each record you created (place, time, categories, notes) (need add 'notes)

-Easy to use interface (done)

-Income tracker, show balance (half done)


## Nice-to-have features [estimated work load: 25 hours]

-Add warning, budget money suggestions based your own rules (Max expense for each categories you created) (undone)

-Accounting for expenses (add graphs) (done, pie graph added)

-Notification for user to record current expenses (undone)

-Better UI design (undone)



#MyBudget Documentation

##MyBudget Framework
  cocoa pods

##AppDelegate - Project Entry
Main code:
Initialize Keyboard Management: IQKeyboardManager
Initialize DataBase: Realm

##LoginViewController (login interface)
check if the username and password is correct

##ViewController (Main interface)
MainCode:
@objc func update() (get the information to the tableview)
sort the data (ascending, descending) according to the time

##ChartsViewController (Pie Chart interface)
Main code:
used a third-party chart from internet, see reference.
Get the data from database and then use 'setDataCount' to create a pie chart,
also this is based on typeInt.


##BudgetTableViewCell 
customized tableview cell

##AddBudgetViewController 
Main code:
check if the input is stored in the database


##MapViewController (map interface)
Main code:
I used a 'mapkit' to get current location,
https://blog.csdn.net/walkerwqp/article/details/70884132

reference cited:

Map delegate:
https://blog.csdn.net/walkerwqp/article/details/70884132

Pie Chart
https://github.com/danielgindi/Charts

IQKeyboardManagerSwift
https://www.jianshu.com/p/01c0682003a9

MapKit:
https://www.cnblogs.com/Free-Thinker/p/4843580.html

Realm DataBase:
https://www.jianshu.com/p/06782df0b901

CocoaPods
https://www.jianshu.com/p/7d0ad4cde012





