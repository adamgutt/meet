# meet
As a user 
      I should be able to click the event details button
      So that I can see and hide the details when I want to
		
	Scenario 1: An event element is collapsed by default

	Given - An event element doesn’t need to be seen
	When - the user doesn’t click that event
	Then - the element will be collapsed by default

	Scenario 2: User can expand an event to see its details
	
	Given - A user wants to see the details of an event
	When - The user clicks the expands details button
	Then - The events details will be shown

	Scenario 3: User can collapse an event to hide its details

	Given - A user wants to hide the events details
	When - A user click the hide details button
	Then - The details of the event will disappear
 
2.  As a user 
     I should be able to specify how many events I want to see 
     So I can see as many events as I want 

	Scenario 1: When user hasn’t specified a number, 32 is the default number
	
	Given - The user hasn’t specified the number of events to show
	When - the user searches for events
	Then - 32 events will be shown

	Scenario 2: User can change the number of events they want to see

	Given - A user wants to see a specific number of events
	When - The user specifies the amount of events to be shown
	Then - The user will see that many events

3.  As a user
     I should be able to have the ability to use the app offline
     So I dont have to worry about having internet to use the app

	Scenario 1: Show cached data when there’s no internet connection

	Given - The user doesn’t have an internet connection
	When - the user tries to use the app
	Then - Cached data will still be shown

	Scenario 2: Show error when user changes the settings (city, time range)

	Given - the user doesn’t have internet
	When - The user tried to change the setting
	Then - An error will take place

4.  As a user
     I should be able to see upcoming event by city
     So I can easily see all the data for the events

	Scenario 1: Show a chart with the number of upcoming events in each city

	Given - The user wants to see upcoming events in each city
	When -	 The user searches for a specific city 
	Then - The number of events that are taking place will show up
		
