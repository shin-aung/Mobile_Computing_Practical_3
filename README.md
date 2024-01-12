# Mobile_Computing_Practical_3

**Learning Journey: Implementing StopwatchApp with MVC Architecture**

As an intermediate learner in Android app development, I devoted approximately 3 hours to navigate through the complexities of creating the StopwatchApp with Model-View-Controller (MVC) architecture, inspired by Chapters 3 and 4 from the textbook.

**Task 0 - Setup Android Emulator (5 mins):**

Starting with configuring the Android emulator, the focus was on enabling screen rotation for comprehensive testing. Navigating the emulator settings and enabling auto-rotate screen set the stage for an effective testing environment.

**Task 1 - Create MVC Stopwatch Activity (90 mins):**

Creating the StopwatchApp involved setting up a new project, renaming the MainActivity to StopwatchActivity, and implementing the app based on the provided MVC UML class diagram. The layout adjustments using LinearLayoutCompat, TextView styling, and button placement were crucial. Understanding the role of activity lifecycle methods in maintaining the stopwatch state presented a significant challenge.

**Task 2 - Implement Helper Methods (30 mins):**

Integrating helper methods like enableStopwatch and disableStopwatch in StopwatchActivity showcased the importance of encapsulating functionality for better code organization. Leveraging member fields and Android's handler mechanism facilitated efficient control over the app's behavior.

**Task 3 - Implement Lifecycle Methods (30 mins):**

Ensuring the app's resilience to device rotation required implementing onSaveInstanceState and onCreate appropriately. Utilizing the Bundle object to store and retrieve UI element states, including a new helper method for updating the TextView, contributed to a robust implementation.

**Task 4 - Using Intents and Getting Results (30 mins):**

Expanding the app's functionality with SettingsActivity involved creating a new activity, handling user input, and using intents to exchange information between activities. The exploration of onActivityResult as another lifecycle method was enlightening, and it added depth to understanding Android app navigation.

**Task 5 - Self-Reflection (150 words):**

Navigating through the complexities of implementing the StopwatchApp with MVC architecture was both challenging and enlightening. The intricate interplay of activity lifecycle methods, UI updates, and data flow demanded a meticulous approach. Challenges were prominent in grasping the nuances of handler mechanisms and ensuring proper state management during device rotations.
