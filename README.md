![Logo-nav](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/Kalvium-Logo.png)

# Kalvium Lab | Create a functionality


Progression 1: Fetch Users

 Modify the fetchUsers function to log the number of users fetched from the API to the console.The function should return a promise, use fetchAPI
Hint: You can use console.log inside the .then block after the users are pushed to the users array.


Progression 2: Display Users
 Update the displayUsers function to display the total number of users at the end of the user list.
Hint: You can append a paragraph with the total count of users to the output string before setting the innerHTML.

Progression 3: Create User
 Implement error handling in the createUser function to simulate a real error scenario. Make the function reject the promise if a user with the same email already exists in the users array.
Hint: You can use the .find method to check if the email already exists in the users array before pushing the new user.


Progression 4: Initialize Data
 Enhance the init function to show a loading message while the user data is being fetched and displayed.
Hint: You can set the innerHTML of the message element to "Loading..." at the beginning of the init function and clear it after displaying users.

Progression 5: Fetch and Add User
 Modify the getData function to add a new user only if there are fewer than 10 users in the users array. Otherwise, log an error message to the console.
Hint: Check the length of the users array before calling createUser and handle the case where the length is 10 or more.

Display Error Handling
 Update the displayError function to clear any existing error messages before displaying a new one.
Hint: Ensure that the errorDiv is removed if it already exists before appending the new error message.
General Challenge: Use Fetch API Instead of Axios

Question: Rewrite the fetchUsers function to use the Fetch API instead of Axios for fetching user data.
Hint: Use fetch and handle the promise with .then and .catch for response handling and error handling.

Advanced Challenge: Add Edit Functionality
 Implement a new function editUser that allows editing the details of a user based on their email. Update the display to reflect the changes.
Hint: Use the .find method to locate the user in the users array, update their details, and then call displayUsers to refresh the display.

Happy Coding Kalvium ❤️
