Enums v0.1 for OpenSim by djphil (CC-BY-NC-SA 4.0)

<small>Enums.md is take from libopenmetaverse Enums.cs</small>

##### AssetType - The different types of grid assets
- Unknown 			= -1  : Unknown asset type
- Texture 			=  0  : Texture asset, stores in JPEG2000 J2C stream format
- Sound 			=  1  : Sound asset
- CallingCard 		=  2  : Calling card for another avatar
- Landmark 			=  3  : Link to a location in world
- Script 			=  4  : Legacy script asset, you should never see one of these
- Clothing 			=  5  : Collection of textures and parameters that can be worn by an avatar
- Object 			=  6  : Primitive that can contain textures, sounds, scripts and more
- Notecard 			=  7  : Notecard asset
- Folder 			=  8  : Holds a collection of inventory items. "Category" in the Linden viewer
- LSLText 			=  10 : Linden scripting language script
- LSLBytecode 		=  11 : LSO bytecode for a script
- TextureTGA 		=  12 : Uncompressed TGA texture
- Bodypart 			=  13 : Collection of textures and shape parameters that can be worn
- SoundWAV 			=  17 : Uncompressed sound
- ImageTGA 			=  18 : Uncompressed TGA non-square image, not to be used as a texture
- ImageJPEG 		=  19 : Compressed JPEG non-square image, not to be used as a texture
- Animation 		=  20 : Animation
- Gesture 			=  21 : Sequence of animations, sounds, chat, and pauses
- Simstate 			=  22 : Simstate file
- Link 				=  24 : Asset is a link to another inventory item
- LinkFolder 		=  25 : Asset is a link to another inventory folder
- MarketplaceFolder =  26 : Marketplace Folder. Same as an Category but different display methods
- Mesh 				=  49 : Linden mesh format
- Settings 			=  56 : ...

##### FolderType - The different types of folder
- None 					= -1   : None folder type
- Texture				=  0   : Texture folder type
- Sound 				=  1   : Sound folder type
- CallingCard 			=  2   : Calling card folder type
- Landmark 				=  3   : Landmark folder type
- Clothing 				=  5   : Clothing folder type
- Object 				=  6   : Object folder type
- Notecard 				=  7   : Notecard folder type
- Root 					=  8   : The root folder type
- LSLText 				=  10  : LSLText folder
- BodyPart 				=  13  : Bodyparts folder
- Trash 				=  14  : Trash folder
- Snapshot 				=  15  : Snapshot folder
- LostAndFound 			=  16  : Lost And Found folder
- Animation 			=  20  : Animation folder
- Gesture 				=  21  : Gesture folder
- Favorites 			=  23  : Favorites folder
- EnsembleStart 		=  26  : Ensemble beginning range
- EnsembleEnd 			=  45  : Ensemble ending range
- CurrentOutfit 		=  46  : Current outfit folder
- Outfit 				=  47  : Outfit folder
- MyOutfits 			=  48  : My outfits folder
- Mesh 					=  49  : Mesh folder
- Inbox 				=  50  : Marketplace direct delivery inbox ("Received Items")
- Outbox 				=  51  : Marketplace direct delivery outbox
- BasicRoot				=  52  : Basic root folder
- MarketplaceListings	=  53  : Marketplace listings folder
- MarkplaceStock		=  54  : Marketplace stock folder
- Settings				=  56  : Settings folder
- Suitcase				=  100 : Hypergrid Suitcase folder

##### InventoryType - Inventory Item Types, eg Script, Notecard, Folder, etc
- Unknown 		= -1  : Unknown
- Texture 		=  0  : Texture
- Sound 		=  1  : Sound
- CallingCard 	=  2  : Calling Card
- Landmark 		=  3  : Landmark
- Script 		=  4  : Script [Obsolete("See LSL")]
- Clothing 		=  5  : Clothing [Obsolete("See Wearable")] 
- Object 		=  6  : Object, both single and coalesced
- Notecard 		=  7  : Notecard
- Category 		=  8  : ...
- Folder 		=  8  : Folder
- RootCategory 	=  9  : ...
- LSL 			=  10 : An LSL Script
- LSLBytecode	=  11 : [Obsolete("See LSL")]
- TextureTGA	=  12 : [Obsolete("See Texture")]
- Bodypart 		=  13 : [Obsolete]
- Trash 		=  14 : [Obsolete]
- Snapshot 		=  15 : ...
- LostAndFound 	=  16 : [Obsolete]
- Attachment 	=  17 : ...
- Wearable 		=  18 : ...
- Animation 	=  19 : ...
- Gesture 		=  20 : ...
- Mesh 			=  22 : ...
- Settings 		=  25 : ...

##### WearableType - Types of wearable assets
- Shape		= 0   : Body shape
- Skin 			  : Skin textures and attributes
- Hair 			  : Hair
- Eyes 			  : Eyes
- Shirt 		  : Shirt
- Pants 		  : Pants
- Shoes 		  : Shoes
- Socks 		  : Socks
- Jacket 		  : Jacket
- Gloves 		  : Gloves
- Undershirt 	  : Undershirt
- Underpants 	  : Underpants
- Skirt 		  : Skirt
- Alpha 		  : Alpha mask to hide parts of the avatar
- Tattoo 		  : Tattoo
- Physics   	  : Physics
- Universal 	  : Universal
- Invalid	= 255 : Invalid wearable asset

More coming soon ...
