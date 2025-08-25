# CS-360


# Weight Tracker App

This is the mobile app I built for CS 360 using Kotlin, Jetpack Compose, and Room. The goal was to create something simple but functional where a user can log their daily weight, set a goal, and get notified when they hit that goal.  

The app starts with a login screen where you can either sign in or create a new account. Once logged in, you get a tracker screen that shows your weight history, lets you add or delete entries, and set a goal weight. There’s also an SMS permission screen that asks if you want the app to send you alerts. If you say no, the rest of the app still works fine.  

While building it, I focused on keeping the flow simple and clean. The login screen only has what’s needed, the tracker screen groups data and actions together, and the SMS screen keeps the choice clear. I used Room for persistence and a ViewModel to tie the database to the UI, which helped keep things organized. I tested features step by step in the emulator to make sure weights saved, updates showed up right away, and the app handled denied permissions without breaking.  

The trickiest part was handling permissions gracefully and making sure the UI updated smoothly with database changes. Getting that right felt like a big win. Overall, I’m most proud of the database integration because it ties the user actions, stored data, and UI updates together in a way that feels complete.  

This project changed how I think about app development. Before I mainly thought about how screens looked, but now I see how design, functionality, and user needs all connect to make an app actually work.  
