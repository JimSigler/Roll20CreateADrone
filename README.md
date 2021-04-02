# Roll20CreateADrone
This is a roll20 script for creating a drone.

## What does it do?
The script allows you to select a token, then use the !createDrone command to create a new token for the given drone, assign it to the selected token (player) and place it on the object layer next to the selected token.

There is a character for each drone that has the appropriate token assigned.  The script looks up that character sheet and assigns the player who owns the selected token as the owner of the next drone token.

I've also created a simple macro that allows a simple selection of drone:

`?{What type of Drone|mosquito,!createDrone mosquito|bumble bee,!createDrone bumble bee|bat,!createDrone bat|hummingbird,!createDrone hummingbird|stinger,!createDrone stinger|scarab,!createDrone scarab|beetle,!createDrone beetle|jammer1,!createDrone jammer1|jammer2,!createDrone jammer2|jammer3,!createDrone jammer3|wolfhound,!createDrone wolfhound }`
