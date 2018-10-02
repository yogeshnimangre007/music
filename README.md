# UBAND-Musical-Structure
Udacity Android Basics Nanodegree- Musical Structure

App Design

    • Suitability
		  o The app’s structure is suitable for a music player app. A similarly structured app which 
			focuses on audiobooks, podcasts, or other audio media is also acceptable.
      
	  • Clarity
		  o Each activity is clearly labelled, using a TextView, such that the final 
			purpose of such an activity is easy to understand. For instance, one 
			screen might be labelled ‘song detail screen’ and another might be labelled 
			‘music library’
			
     • Plan for creation
          o Any activity that requires an external library or class not yet covered 
			includes the name of that library or class. For instance, a payment 
			screen might include information on how to process the payment.
	  
	  • Number of activities
          o The app contains 3 to 6 activities.
		  
Layout

    • Structure
          o The app contains multiple activities, each labelled, which together 
			make a cohesive music app.
    • Labelling
          o Each activity contains a TextView which explains the purpose of the activity.
    • Buttons
		  o Each activity contains buttons which link it to other activities a user 
			should be able to reach from that activity. For instance, 
			a ‘library’ activity might contain a button to move to the ‘now playing’ activity.
	• Layout Best Practices
		  o The code adheres to all of the following best practices:
				o Text sizes are defined in sp
				o Lengths are defined in dp
				o Padding and margin is used appropriately, such that 
				  the views are not crammed up against each other.
		  
Functionality

    • Runtime Errors
          o The code runs without errors
    • OnClickListeners
          o Each button’s behavior is determined by an OnClickListener in the Java code 
			rather than by the android:onClick attribute in the XML Layout.
    • Intents
		  o Each button properly opens the intended activity using an explicit Intent.

Code Quality

    • Code Formatting
          o The code is properly formatted i.e. there are no unnecessary blank lines. 
          o There are no unused variables or methods. 
          o There is no commented out code.
          o The code also has proper indentation when defining variables and methods.
    • Readability
          o Code is easily readable such that a fellow programmer can understand 
			the purpose of the app.
    • Naming Conventions
          o All variables, methods, and resource IDs are descriptively named such that 
			another developer reading the code can easily understand their function.
