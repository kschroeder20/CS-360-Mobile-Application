# CS-360-Mobile-Application
## Weight Tracking App Built in Android Studio

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The purpose of the app is to provide its user a place where they can document a goal weight and track their daily weight in order to map their progress towards their goal. There are three user types that I will be focusing on to meet their needs:
- 60+ year-olds who are actively taking care of their health (going to the doctor appointments, eating according to their needs, staying physically active, etc.). These users did not grow up with modern technology, so they need a simple, and effective application to monitor their weight. Doctors typically ask elderly people for their weight and if they’ve seen changes recently. These users need an easy way to access that information with minimal tapping. When logging their weight, they need a simple interface that will allow them to get in and out of the app as quickly as possible.

- Over-weight people who are starting their health journey. These people don’t need all of the bells and whistles that come with a lot of weight-loss apps. They may be intimidated by the amount of information they are receiving from these apps as they are just starting to take control of their weight. They would want a simple interface where they can log and track their weight without having to spend a lot of time navigating.

- Under-weight people who have been told by a doctor to gain weight. These people have been identified as medically underweight and need to start paying more attention to their weight on a consistent basis. They don’t need the typical weight-tracking app that is focused on people losing weight. They just need a simple way to track and stay on top of their weight-gain journey.

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app needed login and signup functionalities as well as a home screen that would display the user’s name, their goal, and fragments that would display their user-entered weight logs. The user is able to their weight log, edit existing logs and delta logs. When designing my UI, I tried to keep the look as simple as possible since we are trying to reach users that don’t want complicated technology to track their health. I also used a database so that the user information would persist every time that they use the app.

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I started with designing the database to ensure that it includes columns for all of the user and weight log information that I will need. From there, I started to develop the app in the same order in which the user would use it. For example, I started with the signup functionality and screens, then moved to the home screen, then moved to the weight log display, etc. I also tried to keep my classes short and modularize the different functionalities as much as I could. I think that these strategies helped me keep track of what is done and what was remaining and it allowed me to debug the application faster.

### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
I used the application as a normal user would and acted like a user who required each one of the application functionalities. This revealed bugs and aspects of the app that were not user-friendly.

### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
I had to get a little creative on how I connected the two database tables. I wanted to connect the Users table with the WeightLog table using a user_id. I’ve done this before using backend systems like Ruby on Rails that allow you to create has_many relationships. However, for this app, I had to search for the weight logs by user_id every time the user logged in.

### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I think that the login functionality demonstrated my knowledge of how to connect different activities, save information to a database, and retrieve that information correctly. 

