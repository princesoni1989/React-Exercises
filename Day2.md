# Day 2

> To make it easier to evaluate better, would request you all to put each of the questions into a separate file(s) and use those instead to test. 
Unless there is a need for the questions to be interlinked.

1. Create a component Water having a state variable as temperature. Render `Water is in solid state` if `temperature <= 0`, `Water is in a liquid state` if `temperature > 0 and < 100`, `Water in Gas state` if `temperature >= 100`. Change the state of the component from react extension in the browser. 

2. Add ability to above component to change it's state ( `temperature` ) every `5` seconds with some random value between `-10` to `110`. 

3. Create a component UserDetail that takes user object as a prop and displays the user info in  a table.
	```
		sample user data  = [
		{name: 'John', age: 25, avatar: 'https://randomuser.me/api/portraits/men/15.jpg'},
		{name: 'Joe', age: 35, avatar: 'https://randomuser.me/api/portraits/men/13.jpg'},
		{name: 'Andrei', age: 45, avatar: 'https://randomuser.me/api/portraits/men/10.jpg'},
		{name: 'Ted', age: 29, avatar: 'https://randomuser.me/api/portraits/men/1.jpg' },
		{name: 'Ben', age: 30, avatar:'https://randomuser.me/api/portraits/men/2.jpg' }
	      ]
	```
	```
		Name 		Age			Avatar
		John		25			userImage
	```
4. Apply prop validation on `userDetail` component. prop user in UserDetail should be an `object` with key `name (string)`, `age (number)`, `avatar (string)`.
5. Create components Cart, Item and CartTotal. Cart component displays list of Items and CartTotal. 
  (set items in the state of Cart)
	```
		sample items = [
		    {name: 'item1', qty:2, price: 30},
		    {name: 'item2', qty:5, price: 10},
		    {name: 'item3', qty:7, price: 120},
		]
	```
6. Create a stop watch component. called `StopWatch`
	This component should have a `button` and a `timer` inside it.
	On click of the button, the timer should start and should display the time passed (since the click of the button) every second.
	On click of the button again, the timer should stop and the displayed time should freeze.

	  TIP: `componentWillUnmount` should be used
7. Create a User Registration form with fields ( FirstName, LastName, EmailId, Contact Number, Password and Confirm password). Form should have a submit button. Apply form validation to incorporate following rules. 
	
	* First Name should not be equal to LastName and both the fields should be required.
	* Password and Confirm password should be same.
	* Email should be a valid email. 
	* Contact number should be of 10 digit numbers only.

	Submit button should validate the form if it is validated, it should display validation successful (in green color) otherwise it should show the error messages bellow the respective text boxes (in red color). 

	When form is loaded for the first time, FirstName should be focused. 


