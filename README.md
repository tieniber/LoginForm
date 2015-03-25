#LoginForm
A custom login form which can be used as an alternative to the default Mendix login page.

## Contributing

For more information on contributing to this repository visit [Contributing to a GitHub repository](https://world.mendix.com/display/howto50/Contributing+to+a+GitHub+repository)!

## Features

- Use this widget to login **local users** from any page in your Mendix application
- A link to open a 'Forgot my password' page
 
## Limitations
- Input credentials are authenticated with user credentials available in System.User entity(local accounts). Logging in with Mendix SSO account credentials, using this widget, will not result in being logged in.
- In a Sandbox environment an application owner is not able to configure the MxAdmin account(=local). To log in with a MxAdmin account is not possible in a Sandbox.

## Configuration 
- Insert the widget in a page
- Configure the properties 

## Properties

### Display
* *Username placeholder* - Standard text to be displayed in username field
* *Password placeholder* - Standard text to be displayed in password field
* *'Login' button caption* - Text to be displayed on login button
* *Progress bar caption* - Text to display in progress bar, displayed while login request executes
* *Empty username/password message* - Feedback message shown when a user didn't provide all credentials
* *'Forgot password' link text* - Text to use in Forgot password link

### Behaviour
* *Show progress bar* - Display a progress bar while signing in
* *Forgot password microflow* - Microflow being triggered in case of 'forgot password' onclick
* *Focus username input field* - Move focus to username field when the form is showed (only use this if it is not done automatically)


### Mobile
* *Auto capitalize* - Enables/disables auto capitalize functionality on username input field for mobile devices
* *Auto correct* - Enables/disables auto correct functionality on username input field for mobile devices

### Password
* *Show/mask password toggle* - Adds a toggle button to show/mask password.*
* *'Show password' button caption* - The caption that is used for the show button for the value of the password
* *'Mask password' button caption* - The caption that is used for the hide button for the value of the password
* *'Show password' button image* - Optional image to be displayed in 'Show password' button
* *'Mask password' button image* - Optional image to be displayed in 'Mask password' button

## Known issues
- Mendix runtime returns no feedback about the existence of a username. This is by design.



 
