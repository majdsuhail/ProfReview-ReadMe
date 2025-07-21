# ProfeReview
### This repository was created as a documentation to explain how the platform (profreview.net) works and showcase its features. The main project is in a private repository for security reasons, so i created this one for the ReadMe.md file.
## The project is live on [profreview.net](https://profreview.net/)

### Breif description:
Profreview is a platform dedicated to enhancing the academic experience for both students and professors. It allows university students to rate and review their professors, providing valuable feedback that helps professors improve their teaching and students make informed decisions.

# The Platform's Features:
* It has a public access mode which is viewed as a **read-only** for any public visitor and doesn't require a login/signup. The public access shows the universities available on the platform, each professor and their details(Name, Image, Email, office location, and office phone number), and the reviews and ratings made by the students for each professor in the selected university.
![]() ![]()

❗*** The platform allows only the students from the same university to login/signup to the university's **editing/writing mode**(for example: Bilgi university editing/writing mode can be accessed only with emails that end with the @bilgiedu.net domain, and so on for other univeristies) to ensure authenticity***

### In the editing mode students can: 
* Rate(using a five star system) and write reviews for any professor(**Anonymous review submission is supported**)
* Delete and Update their rating and reviews(after submission)
* Like reviews(students who find a review helpful can like other student's reviews(they can remove their like at any time)
* Report offensive or inappropriate Reviews by other students and moderators will notice and act accordingly if applicable
![]()
* Add missing professors from the selected university (example: professors that are newly joined to the university, do not exist on the platform, or were not added to the database before, etc..). The process of submitting a new professor to the database requires the student to input the professor's full or partial info(Name, Image, Email, office location, and office phone number) through the platform and submit for review by the moderators
![]() ![]()
  
### Student's account profile:
* Each account has its own profile which shows their email, contributions(ratings and reviews), the year the account was created on, the total number of contributions on the platform (including the professors submissions which is also counted as contributions), and the reviews a student found helpful, and the professors they have submitted and their submission/moderated status(accepted, modified and accepted, rejected, or pending)
* Students can delete or logout from their account from the profile page.
* Students are also able to remove their professor submissions but only if a submission is still pending
![]() ![]() ![]()

# Other features:
* The login/signup mechanism is email verification based(you recieve an email with a verification code to access your account)
![]() ![]() ![]() ![]()
* The plaform supports sorting for the professors(Best, popular, worst, alphabetical), reviews(Top, newest, oldest, highest, lowest) and reviews in the student's profile(newest, oldest).
* It also supports a name search functionality for the professors
![]() ![]() ![]()
* If the student doesn't logout, the platform will log you out automatically after 24 hours

# Technical:
* The platform was created using react native to allow support for Web(using expo bundler), Android and IOS.

- **Frontend:** React Native (Expo Web)
- **Backend:** Node.js with Express
- **Database:** MySQL

## 🌟 Support
If you like this project, consider buying me a coffee: [Buy Me a Coffee](https://www.buymeacoffee.com/profreview).


