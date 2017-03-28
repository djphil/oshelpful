
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
- 0 = None (0)
- Bit  0:          1 = AllowDamage              (1 << 0)
- Bit  1:          2 = AllowLandmark            (1 << 1)
- Bit  2:          4 = AllowSetHome             (1 << 2)
- Bit  3:          8 = ResetHomeOnTeleport      (1 << 3)
- Bit  4:         16 = SunFixed                 (1 << 4)
- Bit  5:         32 = SunFixed                 (1 << 5)
- Bit  6:         64 = SunFixed                 (1 << 6)
- Bit  7:        128 = BlockLandResell          (1 << 7)
- Bit  8:        256 = Sandbox                  (1 << 8)
- Bit  9:        512 = NullLayer                (1 << 9)
- Bit 10:       1024 = SkipAgentAction          (1 << 10)
- Bit 11:       2048 = SkipUpdateInterestList   (1 << 11)
- Bit 12:       4096 = SkipCollisions           (1 << 12)
- Bit 13:       8192 = SkipScripts              (1 << 13)
- Bit 14:      16384 = SkipPhysics              (1 << 14)
- Bit 15:      32768 = ExternallyVisible        (1 << 15)
- Bit 16:      65536 = MainlandVisible          (1 << 16)
- Bit 17:     131072 = PublicAllowed            (1 << 17)
- Bit 18:     262144 = BlockDwell               (1 << 18)
- Bit 19:     524288 = NoFly                    (1 << 19)
- Bit 20:    1048576 = AllowDirectTeleport      (1 << 20)
- Bit 21:    2097152 = EstateSkipScripts        (1 << 21)
- Bit 22:    4194304 = RestrictPushObject       (1 << 22)
- Bit 23:    8388608 = DenyAnonymous            (1 << 23)
- Bit 24:   16777216 = DenyIdentified           (1 << 24)
- Bit 25:   33554432 = DenyTransacted           (1 << 25)
- Bit 26:   67108864 = AllowParcelChanges       (1 << 26)
- Bit 27:  134217728 = AbuseEmailToEstateOwner  (1 << 27)
- Bit 28:  268435456 = AllowVoice               (1 << 28)
- Bit 29:  536870912 = BlockParcelSearch        (1 << 29)
- Bit 30: 1073741824 = DenyAgeUnverified        (1 << 30)

Total = 2147483647

More coming soon ...
