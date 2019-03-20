[![Build Status](https://travis-ci.org/codeforboston/voiceapp311.svg?branch=master)](https://travis-ci.org/codeforboston/voiceapp311)

# Boston Info Alexa Skill

## How to Use This Skill
You can use our skill with the Amazon Alexa stand-alone home device or with the Alexa app on your phone.  You can start interacting with our skill by asking Alexa to "Open Boston Info" or starting any of your requests with "Alexa, ask Boston Info ..."

In order for Boston Info to work it will need your address to access the right information. If your Amazon Alexa already has your address it may provide it to us, otherwise our skill will ask you for an address. **Once you provide an address it should remain as your address for as long as you are actively using the skill.**


## Current Skill Abilities:
#### Set your Current Address
This is used set and get current addresses in the current session.  If our skill does not know what address to use when trying to access information it will ask for one. You can also specify the address you need for a query by appending it to the skill request.

Example Request:
> "My address is ..."
>
> "Alexa, ask Boston Info for ... at {Address}"


#### Find out your Trash Day
This is used to find trash and recycling pickup and collection days. You can ask for recycling or trash/garbage days specifically. It will tell you what day of the week trash is picked up from the given address.

Example Request:
> "Alexa, ask Boston Info what my garbage day is."
>
> "Alexa, have Boston Info find the recyclables collection days at {Address}"


#### Find the nearest Emergency Snow Parking
This is used to find snow emergency parking. Given an address it will find the nearest emergency snow parking lot by distance. It will tell you the name of and address of the parking lot, as well as estimating how long it will take you to drive there. If the information is available this intent can also tell you how many spaces are in the lot, if the lot charges a fee, and what phone number to call for more information about the parking lot.

Example Request:
> "Alexa, Ask Boston Info where I can park during a snow emergency.


#### Find any current Alerts
This is used to getting any alerts for the day put out by the Boston government. The alerts can be about any of the the following services:
  * street cleaning
  * trash and recyclying
  * city building hours
  * parking meters
  * tow alerts

Example Request:
> "Alexa, ask Boston Info if there are there any alerts."


#### Find out the latest Three One One
This intent will give you the most recent BOS:311 reports. BOS:311 is an app where residents of Boston can report non-emergency issues like potholes or traffic light outages.

Example Request:
> "Alexa, ask Boston Info what's the most recent three one one?"
>
> "Alexa, ask Boston Info to tell me the 4 most recent three one ones"

### Find any nearby Crime incidents
The crime incidents intent will tell you any recently reported crimes in your area.

Example Requests:
> "Alexa, ask Boston Info what's the crime activity in my area?"
>
> "Alexa, ask Boston Info what is the crime near me?"


#### Leave Feedback for us!
This is used to provide feedback about the skill, including bug reports and suggestions for new intents. You can leave feedback on our skill by telling Alexa directly!

Example Request:
> "Alexa, I have a suggestion for Boston Info."
>
> "Alexa, I'd like to report a bug to Boston Info."


## Intents in Development:
These are intents that are currently in development and which we hope to make available soon. We are also looking for user feedback on what intents would be most helpful or would be most wanted.
- Get your polling location
- Get the Hours for City Buildings
- Find nearby public bathrooms
- Crime incidents intents
- Check the sailing weather on the Charles River
- Find nearby Health Centers
- Check animal control/missing pet notices near you
- Get the Commuter Rail schedule for the day
- Find nearby parks, playgrounds, and other public spaces
- Get notifications about nearby Public Works and construction projects
- Find nearby car shares
- Find nearby food trucks
- Information about Moving permits
- Adding yard waste pick-up days to our existing Trash Info Intent
- An intent that combines the information of our most popular intents into one question/response pattern
- A separate Brookline Info skill

## Want to Help Out?
Boston Info is an Alexa skill designed to provide easy access to information
about municipal services in Boston.

If you'd like to contribute or learn more about what we're working on, please
visit our [wiki page](https://github.com/codeforboston/voiceapp311/wiki). There,
you will find basic information about Alexa development and instructions on
setting up a local version of Boston Info that you can experiment with.
