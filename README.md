**Introduction:** 

Test Automation Framework Webdriver

**Application Under Test:** 

Uses Cleartrip website (http://www.cleartrip.com) for automation. This website is used as it is rich with controls like
Textbox, Drop down, Calendar control, Ajax wait etc.
The Scenarios considered are mostly the day to day business use case where in we have used ticket booking business scenario and it's different flavors.


**What to find under this repo:** 

It contains certain chapters and also how a user would transition
 
From 	
	`driver.findby`  

To 
	`given(user).choosesToDoAFlightSearch();`
    `when(user).searchesForAOneWayJourneyWith(journeyDetails);`
    `then(user).hasJourneyOptionsAvailableForHisOutboundJourney();`
