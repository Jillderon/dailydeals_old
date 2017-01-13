DESIGN.md

# Design DailyDeals 
Because this app is centered both around clients as around companies, there are two kinds of accounts:
1. Client account
2. Business account 

## Diagram of classes 
* Login ViewController
* SignUp ViewController
* Map ViewController
* AddDeal ViewController
* SearchDeal ViewController 
* InformationDeal ViewController

[![Screen Shot 2017-01-13 at 11.26.06.png](https://s30.postimg.org/ckloeg841/Screen_Shot_2017_01_13_at_11_26_06.png)](https://postimg.org/image/5u5750ky5/)

## Sketches UI 
[![Screen Shot 2017-01-13 at 11.14.03.png](https://s30.postimg.org/bla5w6fq9/Screen_Shot_2017_01_13_at_11_14_03.png)](https://postimg.org/image/vfw7iauxp/)

1. Login ViewController. 
2. Sign Up ViewController
3. Add Deal ViewController. Hidden for people with an user account. 
4. Search Viewcontroller. A Screen where you can add your preferences (activities, festivals, dinner etc) through a drop-down menu.
5. Map Viewcontroller. Map of Amsterdam with pins representing activities of the user's preference.  When clicked on a pin, more detailed information about that activity will be loaded. There is also a 'more information' option and when clicked the user is send to the InformationDeal ViewController. You can also navigate across the map and new pins will automatically appear.


## APIs and frameworks or plugins
To create this app the UIKit and UIMapKit library will be used. UIMapKit will be used to determine the current location of the user and to place activities and deals on the map. Firebase will be used to save preferences of users. 
