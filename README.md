# SecureCheck: Adopting Safe Cybersecurity practices through Persuasive Technology 

SecureCheck is cybersecurity platform that promotes the adoption of security practices through the persuasion of gamification, personalized feedback, and social comparisons. This dynamic approach creates a game-like interface that nudge users to strengthen their security measures, promote a spirit of healthy competition among users. The platform is designed to conform to mobile and desktop environments, making it engaging and accessible to all.

## Application Scope
- Responsive Design: Application should be fully responsive in all devices from screen size 280 pixels and above.
- There should no loss of functionality between mobile devices and tablets or desktops.
- App uses interactive emojis and feedbacks to nudge users into creating strong passwords.
- App user can register, login and view profile.
- An authenticated user can access a leaderboard dashboard displaying all users' password strength.
- Authenticated users can upgrade existing passwords to asscend the leaderboard dashboard.

## Wireframe
- Wireframe was created using wireframe.cc                                      
![wireframe1](/images/wireframe1.png)
![wireframe2](/images/wireframe2.png)
![wireframe3](/images/wireframe3.png)
![wireframe4](/images/wireframe4.png)


## Implementation

Overview of the Technical Aspects and Implementation Details

The web-based application is a dynamic and interactive program that has been precisely designed to simplify user registration, authentication, and password management. This solution necessitates a number of technical considerations and programming, spanning from the visual design on the frontend to the backend's architecture. The overall goal is to provide users with a secure, intuitive, and user-friendly experience while using the application.

### Frontend 
HTML was used to create the elements while CSS3 and bootstrap were used achieve responsiveness in the application. Javascript was used for password masking and unmasking. Also for frontend password authentication. 

### Backend 
Node.js express.js and javascript was used to create and authenticate/validate the backend submission of registration and login forms.
Bcrypt was used in password hashing and authentication of login password.
Mongoose and mongodb was used to implement the database
## Technologies and Tools Used

*frontend:*
- JavaScript.
- HTML5.
- CSS3

*Library/Tools:*
- bcrypt
- ejs
- express  
- mongodb
- mongoose
- Express.js
- Bootstrap

*Database:*
- Mongodb

*Deployment:*
- www.render.com

## Testing

Manual testing was exhaustively done
- Checked if all the links worked by clicking on all elements with link E.g SecureCheck logo, Registration and Login. Click the link and confirm if the link openeed the desired page.
- Tested for user validation by entering valid and invalid input respectively. Confirmed error message for invalid entries and successful message for valid inputs.
-Test that upgraded password is updated on the database by upgrading and logging in with the new password.
- Test that only authenticated user can access the profile page.
- Usability testing was done among participants to test the persuasive s=effect of the application. This was done by giving the participants link to the application.

## Bugs

- Registered users details  not writing to the database - Fixed
- Login form was not reading from the database  - Fixed
- Authentcated users could not login into the application - Fixed
- Both successful and error messages showing at the same time during login -  Fixed

*Deployment Process*

Deploying the SecureCheck Application to Render.com was a straightforward and efficient process, enabling the application to be accessible to users seamlessly. The following steps outline the deployment journey:

1. *Repository Setup:*
   - A new GitHub repository was established to serve as the version control system for the SecureCheck application. This repository acts as a central hub for managing code changes and updates.

2. *Render Account Creation:*
   - An account was created on the Render.com platform. Render offers a user-friendly interface and provides a free tier that suits small to medium-sized projects.

3. *Service Creation:*
   - In the Render dashboard, a new Web Service was created specifically for the SecureCheck application. This service acts as the hosting environment for the application.

4. *Integration with GitHub:*
   - The SecureCheck application was seamlessly connected to the GitHub repository. This integration streamlines the deployment process and ensures that updates to the codebase are automatically reflected in the deployed version.

5. *Configuration Settings:*
   - Essential configuration settings were specified during the service creation process:
     - *Name, Region, and Branch:* A unique name was assigned to the service, the region was chosen for optimized performance, and the desired branch (e.g., `main`) was selected.
     - *Build Command:* The build command, set as `npm install`, is responsible for installing the required dependencies for the application.
     - *Start Command:* The start command, set as `npm start`, initiates the execution of the application.

6. *Deployment Completion:*
   - The SecureCheck application was successfully deployed to Render's hosting environment.

7. *Accessible URL:*
   - The live version of the SecureCheck application is accessible at [SecureCheck](https://www.securecheck.onrender.com). Users can conveniently access and interact with the application through this URL.
