Week 6 project for the Code Fellows iOS Development Accelerator

This is a sample client app to access your Stack Overflow account.
The user can log in and view their profile, search for questions by tag, and search for other users.
__________________________________________________________________________________________
![](https://github.com/pakalewis/StackOverFlowed/blob/master/screenshot.png)
__________________________________________________________________________________________


Features:
- OAuth access to Stack Overflow
- Network calls to Stack Overflow API
- JSON parsing
- Split view controller
- UITableViewController with custom cells
- Localization (a few labels are translated into Spanish)
- Custom activity indicator installed from a CocoaPod (https://github.com/TransitApp/SVProgressHUD)
- WKWebView displays content on Stack Overflow




Monday
- Setup your model layer of your stack overflow client. Create a class for a question and a user. Model them using the stack overflow API.
- Structurally, set your app up with a split view controller to help with universal layout.
- Create a network controller with a method designed to fetch questions based on a tag. Consult the stack overflow API documentation to find the endpoint for this.
- Parse the results and show them in a table view. Do this inside of a QuestionSearchViewController.

Tuesday
- Get OAuth access working with your stack overflow account.

Wednesday
- Write a unit test to test out your JSON parsing on your question class
- Enable localization in your app for any non english language, and set at least one user facing label or button to be translated when the user changes the language setting on the device.

