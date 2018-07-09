Helpful v0.1 for OpenSim by djphil (CC-BY-NC-SA 4.0)

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
- 200 = Resident: Payment info on account
- 300 = Testing: Payment info on account
- 400 = Testing: No payment info on account
- 600 = Member Estatute: Payment info on account
- 800 = Linden Contracted

##### USER ACCOUNTS TYPES:
- 0 = Normal user (Resident)
- 1 = Trial Member
- 2 = Charter Member
- 3 = Linden Labs Employee

##### USER ACCOUNTS BIT FLAGS:
-  1 (0x01): Allow external services like Google to index the user profile
-  2 (0x02): The content of the profile is "mature" and should not appear on web pages children can access
-  4 (0x04): The avatar has provided payment info and is therefore identified
-  8 (0x08): The avatar has made at least one successful payment using their payment info
- 16 (0x10): The avatar is online (This flag has no effect in the database, it is dynamically managed)
- 32 (0x20): The avatar has been age verified using some external service (like LL's Aristotle)

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
- 0 = None (0): No flags set
- Bit  0:          1 = AllowDamage              (1 << 0): Agents can take damage and be killed
- Bit  1:          2 = AllowLandmark            (1 << 1): Landmarks can be created here
- Bit  2:          4 = AllowSetHome             (1 << 2): Home position can be set in this sim
- Bit  3:          8 = ResetHomeOnTeleport      (1 << 3): Home position is reset when an agent teleports away
- Bit  4:         16 = SunFixed                 (1 << 4): Sun does not move
- Bit  5:         32 = TaxFree                  (1 << 5): No object, land, etc. taxes
- Bit  6:         64 = BlockTerraform           (1 << 6): Disable heightmap alterations (agents can still plant foliage) 
- Bit  7:        128 = BlockLandResell          (1 << 7): Land cannot be released, sold, or purchased
- Bit  8:        256 = Sandbox                  (1 << 8): All content is wiped nightly
- Bit  9:        512 = NullLayer                (1 << 9): 
- Bit 10:       1024 = SkipAgentAction          (1 << 10): 
- Bit 11:       2048 = SkipUpdateInterestList   (1 << 11): 
- Bit 12:       4096 = SkipCollisions           (1 << 12): No collision detection for non-agent objects
- Bit 13:       8192 = SkipScripts              (1 << 13): No scripts are ran
- Bit 14:      16384 = SkipPhysics              (1 << 14): All physics processing is turned off
- Bit 15:      32768 = ExternallyVisible        (1 << 15): 
- Bit 16:      65536 = MainlandVisible          (1 << 16): 
- Bit 17:     131072 = PublicAllowed            (1 << 17): 
- Bit 18:     262144 = BlockDwell               (1 << 18): 
- Bit 19:     524288 = NoFly                    (1 << 19): Flight is disabled (not currently enforced by the sim)
- Bit 20:    1048576 = AllowDirectTeleport      (1 << 20): Allow direct (p2p) teleporting
- Bit 21:    2097152 = EstateSkipScripts        (1 << 21): Estate owner has temporarily disabled scripting
- Bit 22:    4194304 = RestrictPushObject       (1 << 22): 
- Bit 23:    8388608 = DenyAnonymous            (1 << 23): Deny agents with no payment info on file
- Bit 24:   16777216 = DenyIdentified           (1 << 24): Deny agents with payment info on file
- Bit 25:   33554432 = DenyTransacted           (1 << 25): Deny agents who have made a monetary transaction
- Bit 26:   67108864 = AllowParcelChanges       (1 << 26): 
- Bit 27:  134217728 = AbuseEmailToEstateOwner  (1 << 27): 
- Bit 28:  268435456 = AllowVoice               (1 << 28): Region is Voice Enabled
- Bit 29:  536870912 = BlockParcelSearch        (1 << 29): 
- Bit 30: 1073741824 = DenyAgeUnverified        (1 << 30): 

Total = 2147483647

##### LAND FLAGS (land -> LandFlags)
- Hex        0:          0 = None (0): No flags set
- Hex        1:          1 = AllowFly: Allow avatars to fly (a client-side only restriction)
- Hex        2: 	     2 = AllowOtherScripts: Allow foreign scripts to run
- Hex        4:          4 = ForSale: This parcel is for sale
- Hex        8:          8 = AllowLandmark: Allow avatars to create a landmark on this parcel
- Hex       10:         16 = AllowTerraform: Allows all avatars to edit the terrain on this parcel
- Hex       20:         32 = AllowDamage: Avatars have health and can take damage on this parcel. If set, avatars can be killed and sent home here
- Hex       40:         64 = CreateObjects: Foreign avatars can create objects here
- Hex       80:        128 = ForSaleObjects: All objects on this parcel can be purchased
- Hex      100:        256 = UseAccessGroup: Access is restricted to a group
- Hex      200:        512 = UseAccessList: Access is restricted to a whitelist
- Hex      400:       1024 = UseBanList: Ban blacklist is enabled
- Hex      800:       2048 = UsePassList: Unknown
- Hex     1000:       4096 = ShowDirectory: List this parcel in the search directory
- Hex     2000:       8192 = AllowDeedToGroup: Allow personally owned parcels to be deeded to group
- Hex     4000:      16384 = ContributeWithDeed: If Deeded, owner contributes required tier to group parcel is deeded to
- Hex     8000:      32768 = SoundLocal: Restrict sounds originating on this parcel to the parcel boundaries
- Hex    10000:      65536 = SellParcelObjects: Objects on this parcel are sold when the land is purchsaed
- Hex    20000:     131072 = AllowPublish: Allow this parcel to be published on the web
- Hex    40000:     262144 = MaturePublish: The information for this parcel is mature content
- Hex    80000:     524288 = UrlWebPage: The media URL is an HTML page
- Hex   100000:    1048576 = UrlRawHtml: The media URL is a raw HTML string
- Hex   200000:    2097152 = RestrictPushObject: xxx
- Hex   400000:    4194304 = DenyAnonymous: xxx
- Hex   800000:    8388608 = LindenHome: xxx
- Hex  2000000:   33554432 = AllowGroupScripts: xxx
- Hex  4000000:   67108864 = CreateGroupObjects: xxx
- Hex  8000000:  134217728 = AllowAPrimitiveEntry: xxx
- Hex 10000000:  268435456 = AllowGroupObjectEntry: xxx
- Hex 20000000:  536870912 = AllowVoiceChat: xxx
- Hex 40000000: 1073741824 = UseEstateVoiceChan: xxx
- Hex 80000000: 2147483648 = DenyAgeUnverified: xxx

Total = 4278190079 

##### REGION ACCESS (regions -> access)
- 0 = Min: Minimum access level, no additional checks
- 7 = Trial: Trial accounts allowed
- 13 = PG: PG rating
- 21 = Mature: Mature rating
- 254 = Down: Simulator is offline
- 255 = NonExistent: Simulator does not exist

##### GROUP ROLE POWERS (os_groups_roles -> Powers)
- 0 = None (0): No flags set
- Bit  1:                 2 = Invite                (1 << 1): Can send invitations to groups default role
- Bit  2:                 4 = Eject                 (1 << 2): Can eject members from group
- Bit  3:                 8 = ChangeOptions         (1 << 3): Can toggle 'Open Enrollment' and change 'Signup fee'
- Bit  4:                16 = CreateRole            (1 << 4): Can create new roles
- Bit  5:                32 = DeleteRole            (1 << 5): Can delete existing roles
- Bit  6:                64 = RoleProperties        (1 << 6): Can change Role names, titles and descriptions
- Bit  7:               128 = AssignMemberLimited   (1 << 7): Can assign other members to assigners role
- Bit  8:               256 = AssignMember          (1 << 8): Can assign other members to any role
- Bit  9:               512 = RemoveMember          (1 << 9): Can remove members from roles
- Bit 10:              1024 = ChangeActions         (1 << 10): Can assign and remove abilities in roles
- Bit 11:              2048 = ChangeIdentity        (1 << 11): Can change group Charter, Insignia, 'Publish on the web' and which members are publicly visible in group member listings
- Bit 12:              4096 = LandDeed              (1 << 12): Can buy land or deed land to group
- Bit 13:              8192 = LandRelease           (1 << 13): Can abandon group owned land to Governor Linden on mainland, or Estate owner for private estates
- Bit 14:             16384 = LandSetSale           (1 << 14): Can set land for-sale information on group owned parcels
- Bit 15:             32768 = LandDivideJoin        (1 << 15): Can subdivide and join parcels
- Bit 16:             65536 = JoinChat              (1 << 16): Can join group chat sessions
- Bit 17:            131072 = FindPlaces            (1 << 17): Can toggle "Show in Find Places" and set search category
- Bit 18:            262144 = LandChangeIdentity    (1 << 18): Can change parcel name, description, and 'Publish on web' settings
- Bit 19:            524288 = SetLandingPoint       (1 << 19): Can set the landing point and teleport routing on group land
- Bit 20:           1048576 = ChangeMedia           (1 << 20): Can change music and media settings
- Bit 21:           2097152 = LandEdit              (1 << 21): Can toggle 'Edit Terrain' option in Land settings
- Bit 22:           4194304 = LandOptions           (1 << 22): Can toggle various About Land > Options settings
- Bit 23:           8388608 = AllowEditLand         (1 << 23): Can always terraform land, even if parcel settings have it turned off
- Bit 24:          16777216 = AllowFly              (1 << 24): Can always fly while over group owned land
- Bit 25:          33554432 = AllowRez              (1 << 25): Can always rez objects on group owned land
- Bit 26:          67108864 = AllowLandmark         (1 << 26): Can always create landmarks for group owned parcels
- Bit 27:         134217728 = AllowVoiceChat        (1 << 27): Can use voice chat in Group Chat sessions
- Bit 28:         268435456 = AllowSetHome          (1 << 28): Can set home location on any group owned parcel
- Bit 29:         536870912 = LandManageAllowed     (1 << 29): Can modify public access settings for group owned parcels
- Bit 30:        1073741824 = LandManageBanned      (1 << 30): Can manager parcel ban lists on group owned land        
- Bit 31:        2147483648 = LandManagePasses      (1 << 31): Can manage pass list sales information
- Bit 32:        4294967296 = LandEjectAndFreeze    (1 << 32): Can eject and freeze other avatars on group owned land
- Bit 33:        8589934592 = ReturnGroupSet        (1 << 33): Can return objects set to group
- Bit 34:       17179869184 = ReturnNonGroup        (1 << 34): Can return non-group owned/set objects
- Bit 35:       34359738368 = LandGardening         (1 << 35): Can landscape using Linden plants
- Bit 36:       68719476736 = DeedObject            (1 << 36): Can deed objects to group
- Bit 37:      137438953472 = ModerateChat          (1 << 37): Can moderate group chat sessions
- Bit 38:      274877906944 = ObjectManipulate      (1 << 38): Can move group owned objects
- Bit 39:      549755813888 = ObjectSetForSale      (1 << 39): Can set group owned objects for-sale
- Bit 40:     1099511627776 = Accountable           (1 << 40): Pay group liabilities and receive group dividends
- Bit 41:     2199023255552 = ...                   (1 << 41): ...
- Bit 42:     4398046511104 = SendNotices           (1 << 42): Can send group notices
- Bit 43:     8796093022208 = ReceiveNotices        (1 << 43): Can receive group notices
- Bit 44:    17592186044416 = StartProposal         (1 << 44): Can create group proposals
- Bit 45:    35184372088832 = VoteOnProposal        (1 << 45): Can vote on group proposals
- Bit 48:   281474976710656 = ReturnGroupOwned      (1 << 48): Can return group owned objects

Total = 351843720888319

##### DEFAULT EVERYONE GROUP POWERS
- Bit 16:             65536 = JoinChat              (1 << 16): Can join group chat sessions
- Bit 27:         134217728 = AllowVoiceChat        (1 << 27): Can use voice chat in Group Chat sessions
- Bit 28:         268435456 = AllowSetHome          (1 << 28): Can set home location on any group owned parcel
- Bit 40:     1099511627776 = Accountable           (1 << 40): Pay group liabilities and receive group dividends
- Bit 43:     8796093022208 = ReceiveNotices        (1 << 43): Can receive group notices
- Bit 44:    17592186044416 = StartProposal         (1 << 44): Can create group proposals
- Bit 45:    35184372088832 = VoteOnProposal        (1 << 45): Can vote on group proposals

Total = 62672565501952

More coming soon ...
