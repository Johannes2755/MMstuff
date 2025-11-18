SillySeason





driver morale change race-to-race:



if expected:		+0

if above expected	+3

if below expected	-3

if crash		-6

if mechanical DNF	-12



DRIVER QUALITY MODIFIER:

(24 - finishing position) / 24



(24 - 16) / 24 = 8/24 = 0.33333



if driver is 5/5 stars = 1.00 - 0.333333 = 0.66667







expected finish: 20th

actual finish: 16th

driver star rating: 5/5





morale: 75

above expected: +3 = 78

driver quality modifier: 10.0 - 3.3 = -6.7



3 - 6.7 = -4 morale change



start at 75 by default, 16 races of -4 morale = 75 - 64 = 11



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



expected finish: 12th

actual finish: 15th

driver is 3.0 stars



morale: 75

below expected: -3 = 72

driver quality modifier: 6 - 3.8 = -2.2



-3 - 2.2 = -5 morale change



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



SILLY SEASON NEGOTIATION: DRIVER-SIDE





STAR RATING DICTATES AVG DESIRED SALARY

36 skill points = 90k per month

72 skill points = 180k per month

108 skill points = 360k per month

144 skill points = 720k per month

180 skill points = 1.44M per month



each year spent unemployed worsens their desired salary by 20%



if any driver spends more than three consecutive years unemployed, then they are set to retire at the end of the 4th year.



CAR QUALITY DICTATES DESIRED EARNINGS



if team has best car: will accept x0.7 desired earnings

if team has 2nd best car: will accept x0.76 desired earnings

if team has 3rd best car: will accept x0.82 desired earnings

if team has 4th best car: will accept x0.88 desired earnings

if team has 5th best car: will accept x0.94 desired earnings

if team has 6th best car: will accept x1.00 desired earnings

if team has 7th best car: will accept x1.00 desired earnings

if team has 8th best car: will accept x1.08 desired earnings

if team has 9th best car: will accept x1.16 desired earnings

if team has 10th best car: will accept x1.24 desired earnings

if team has 11th best car: will accept x1.32 desired earnings

if team has 12th best car: will accept x1.4 desired earnings





Perfect 180 skill driver:	will accept a deal from Steinmann at 1M salary

&nbsp;				will accept a deal from Chariot at 2M salary





STATUS: should be referenced to deal already in place

if unemployed: any status is good



Reserve will only accept a new reserve role based on new salary (scaled by age)

age 20: new reserve at 2x previous salary

age 40: new reserve at 1x previous salary



Else:

Number 2, Equal Status and Number 1 will NOT accept reserve driver under any circumstances





BREAK CLAUSE:

Should only come into effect if more than 11 months remain on the deal





DURATION:

sliding scale based on age

ages 17-24: will not accept 1-year deals

ages 25-32: any duration

ages 33-40: will not accept 3-year deals



UPON SIGNING:

If driver morale is 10% or lower, signing with a new team should clamp their morale up to 50%. Otherwise, current morale + 40%.





\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

TEAM SATISFACTION WITH DRIVERS



upon signing: starts at 75%



driver expectation = (team standings expectation \* 2 if team standings expectation > 1, else team standings expectation \* 4)

race-to-race team satisfaction change = (driver expectation - driver race position)



team expects 8th, driver finishes 13th, then team is 5% less satisfied with them after the race

Races in which the driver "retire" are exempt from team satisfaction calculation



AFTER FINAL RACE (so before contracts are signed), team checks if they can afford a 10% salary hike.



if (income per month < (current salary x1.1f - current salary)), then that driver is removed from their desirable driver list



if they can, then teams calculate how satisfied they are with their driver up for renewal

if the team satisfaction is below 33%, 

&nbsp;	then the team removes their current driver from the "desired driver list"

else if team satisfaction is between 33% and 55%:

&nbsp;	then the team offers a one-year contract at 10% salary hike

else if team satisfaction is between 55% and 77%:

&nbsp;	then the team offers a two-year contract at 10% salary hike

else if team satisfaction is between 77% and 100%:

&nbsp;	then the team offers a three-year contract at 10% salary hike

&nbsp;	

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



TEAM: THE LIST OF DESIRED MAIN DRIVERS

Should only consist of either 

A) unemployed drivers

B) drivers whose current deal has less than a year remaining

C) drivers whose skill rating just went above the skill maximum for the lower division

sort by (potential + current skill)/2, if peak hasn't been reached, otherwise current skill



MARKETABILITY MODIFIER: 0 marketability gives a x0.75 modifier to score, 100 marketability gives a x1.25 modifier to score

paydriver gives a x1.5 modifier to score



by default, the top of the list should be current drivers up for renewal



if the *player* team has a deal signed with a driver, then they will be removed from the desired driver list of all AI-controlled teams

you can only have a deal on with three drivers maximum



if someone has the "rival with driver" personality trait, then the team of the rival driver will remove them from the "desired driver list"

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



APS teams CANNOT hire a driver whose adjusted skill rating is above 159.99

ERS teams CANNOT hire a driver whose adjusted skill rating is above 119.99



Drivers currently in ERS will automatically want out above a skill rating of 119.99

Drivers currently in APS will automatically want out above a skill rating of 159.99



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_





CASE STUDY: Kiyohisa Bashir



reserve at 244k salary



improves to 4.5/5 stars as a main driver, base salary desire now 1.08M

9th best team, expects 1.253M



if income per month > (1.253M - 244k), then Asia Road can afford his demands



ahh, BUT what if a better team also makes an offer?





\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

AT PRE-SEASON TESTING:



if reserve driver skill > either of the two main driver skills:

then they are promoted to a main seat

&nbsp;	REMOVE PAY DRIVER PROVISION THAT BLOCKS THIS





