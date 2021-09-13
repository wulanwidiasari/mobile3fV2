01
What is Android?
-Software Stack for mobile devices
-SDK provides tools and APIs to develop apps
Application is Ships with core set of apps written in java
Main Components of Android
-Activities
-Services
-Content Providers
-Broadcast Receivers

02
#Activity is an java class application component, Represents one window, one hierarchy of views
Typically fills the screen, but can be embedded in other activity or a appear as floating window
Represents an activity, such as ordering groceries, sending email, or getting directions
Activity Can start other activities in the same or other apps
#Apps and activities
-Activities are loosely tied together to make up an app
-First activity user sees is typically called "main activity"
-Activities can be organized in parent-child relationships in the Android manifest to aid navigation
#Layouts and Activities
An activity typically has a UI layout
Layout is usually defined in one or more XML files
Activity "inflates" layout as part of being created
#Intent
-An intent is a description of an operation to be performed.
-An Intent is an object used to request an action from another
app component via the Android system.
#Navigation
-When a new activity is started, the previous activity is stopped and pushed on the activity back stack
-Last-in-first-out-stack—when the current activity ends, or the user presses the Back button, it is popped from the stack and the previous activity resumes
-Two forms of navigation
1.Temporal or back navigation
2.Ancestral or up navigation
