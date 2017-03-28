
#helpful
Helpful for OpenSim v0.1 by djphil (CC-BY-NC-SA 4.0)

##### USER ACCOUNTS LEVELS (usseraccounts -> UserLevel)
-   0 = GOD_NOT: This is the level given to users by default
-   1 = GOD_LIKE: Rename objects without modify permission
- 100 = GOD_CUSTOMER_SERVICE
 - Toggle character geometry
 - Take copy
 - Owner To Me
 - Set To Linden Content
 - Claim Public Land
- 150 = GOD_LIAISON: Enable land auction
- 200 = GOD_FULL: allow user to get admin level (advanced => request admin)
 - (Difference from GOD_LIAISON not apparent)
- 250 = GOD_MAINTENANCE (Difference from GOD_FULL not apparent)

##### USER ACCOUNTS FLAGS (usseraccounts => UserFlags)
- 200 = Resident:Payment info on account
- 300 = Testing:Payment info on account
- 400 = Testing:No payment info on account
- 600 = Member Estatute:Payment info on account
- 800 = Linden Contracted

##### PROFILE WANT TO MASKS (profileWantDoMask vs. profileWantToMask)
- Bit 0:   1 = Build
- Bit 1:   2 = Explore
- Bit 2:   4 = Meet
- Bit 3:   8 = Group
- Bit 4:  16 = Buy
- Bit 5:  32 = Sell
- Bit 6:  64 = Be Hired
- Bit 7: 128 = Hire

Total = 255

##### PROFILE SKILLS MASKS (profileCanDoMask vs. profileSkillsMask)
- Bit 0:  1 = Textures
- Bit 1:  2 = Architecture
- Bit 2:  4 = Event Planning 
- Bit 3:  8 = Modeling
- Bit 4: 16 = Scripting
- Bit 5: 32 = Custom Characters

Total = 63

##### CLASSIFIEDS CATEGORY (category)
- 1 = Shopping
- 2 = Land Rental
- 3 = Property Rental
- 4 = Special Attraction
- 5 = New Products
- 6 = Employment
- 7 = Wanted
- 8 = Service
- 9 = Personal

##### CLASSIFIEDS FLAGS (classifiedsflags)
-  4 = PG content
-  8 = Mature content
- 32 = Publish each week

##### EVENTS CATEGORY (category)

- 18 = Discussion
- 19 = Sports
- 20 = Live Music
- 22 = Commercial
- 23 = Nightlife/Entertainment
- 24 = Games/Contests
- 25 = Pageants
- 26 = Education
- 27 = Arts and Culture
- 28 = Charity/Support Groups
- 29 = Miscellaneous

##### REGION FLAGS (regions -> flags)
-  0       = None
-  1 << 0  = AllowDamage
-  1 << 1  = AllowLandmark
-  1 << 2  = AllowSetHome
-  1 << 3  = ResetHomeOnTeleport
-  1 << 4  = SunFixed
-  1 << 5  = SunFixed
-  1 << 6  = SunFixed
-  1 << 7  = BlockLandResell
-  1 << 8  = Sandbox
-  1 << 9  = NullLayer
-  1 << 10 = SkipAgentAction
-  1 << 11 = SkipUpdateInterestList
-  1 << 12 = SkipCollisions
-  1 << 13 = SkipScripts
-  1 << 14 = SkipPhysics
-  1 << 15 = ExternallyVisible
-  1 << 16 = MainlandVisible
-  1 << 17 = PublicAllowed
-  1 << 18 = BlockDwell
-  1 << 19 = NoFly
-  1 << 20 = AllowDirectTeleport
-  1 << 21 = EstateSkipScripts
-  1 << 22 = RestrictPushObject
-  1 << 23 = DenyAnonymous
-  1 << 24 = DenyIdentified
-  1 << 25 = DenyTransacted
-  1 << 26 = AllowParcelChanges
-  1 << 27 = AbuseEmailToEstateOwner
-  1 << 28 = AllowVoice
-  1 << 29 = BlockParcelSearch
-  1 << 30 = DenyAgeUnverified

More coming soon ...
