Roth2 - Open Source Mesh Avatar for Virtual Worlds
Prepared: 2020-05-24

Roth2 is a low-poly mesh body specifically designed for OpenSimulator. It is built to use standard Second Life(TM) UV maps using a scratch-built open source mesh by Shin Ingen, Ada Radius and other contributors from the OpenSimulator Community.

============================================================
BAKES ON MESH

Roth2 v2 is provided as a single mesh that is designed to work well with Bakes on Mesh. It has a simple alpha capability without needing separate mesh parts and alpha masks can be worn to give more control over hidden areas. rather than use Bakes on mesh, skin textures may be applied, but you should then add a full body alpha mask to hide the underlying system avatar.

The "Roth2 v2 Mesh Avatar" box contents are designed so that they form a complete initial avatar using Bakes on Mesh. You can switch to your own shape, skin, eyes and hair and/or use the HUD to change your appearance. Some example skins, hair, clothing  and a range of alpha masks are provided in the "Roth2 v2 Extras" box.

============================================================
HUD

Roth2 v2 uses a single combination HUD for alpha masking, skin and eye texture applier and other features. The skins and eyes that are available are set via a notecard (!CONFIG) in the Contents of the HUD which can be edited to incorporate your own skins (10 slots are available) and/or eye textures (5 slots are available).

============================================================
BOX CONTENTS

Roth2 v2 - Mesh Avatar - This is the normal distribution box and is designed so that once unpacked its contents can be "worn". It does not contain basic "classic" avatar shape, skin, eyes or hair so that the users own existing underlying avatar setup is used. The extras box contains examples of the basic avatar items to select from if needed.
* !README, !LICENSE and !CHANGES
* Roth2 v2 Full (Body+Feet+Hands+Head)
* Roth2 v2 Eyes
* Roth2 v2 HUD
* Initial skin, shape, basic eyes and basic hair
* Dark gray underwear

Roth2 v2 - Extras - This is a box of useful extra elements and options.
* !README-EXTRAS and !LICENSE
* Roth2 v2 Body (only)
* Roth2 v2 Feet
* Roth2 v2 Hands
* Roth2 v2 Head
* Roth2 v2 Headless (Body+Feet+Hands)
* Roth2 v2 Head+Vneck (section of body)
* Roth2 v2 Elf Ears
* Dark grey underwear top jacket length version
* Alpha masks
* Sample hair
* HUD debug script

Roth2 v2 - Resources - This box is not normally needed. It contains textures and other resources with original UUIDs as used within the other assets.. This can be useful of moving the assets across grid, or to repair elements.
* !README-RESOURCES and !LICENSE
* All skin and eye textures used in default HUD

Roth2 v2- Mesh Uploads - This box is not normally needed.  It contains mesh for all Roth2v2 elements as originally uploaded and before attaching a root prim or any texturing.
* !README-MESH-UPLOADS and !LICENSE
* Collada (.dae) Mesh for all Roth2 v2 elements as originally uploaded and before part renaming, attaching a root prim or any texturing.

============================================================
KNOWN ISSUES AND TROUBLESHOOTING

There may be a small gap or seem at the neck joint between the mesh body and the classic avatar or addon mesh heads.

Not all the appearance sliders will work on the mesh body and parts.

Roth2 v2 with attached Bento head will work with most shapes. The headless body, to use with system head or other mesh head, will work well with the sliders except body fat, and extremes to neck length and thickness, because of the neck seam. There are a few head sliders that don't work: Head Shape, Ear Angle, Jowls, Chin Cleft. Things on the list for another release sometime down the road: figure out the neck issue, improve pointy ears.

Foot skin problems? For best result, paint over the system toenails and remove as much detail as you can from your foot skin that is probably designed for the system avatar's duck feet.

HUD issues? The Extras box contains a HUD debug script. Add this to the HUD contents to allow for a long mouse press to bring up menu with diagnostic and further options.

============================================================
RUTHANDROTH COMMUNITY

Please contribute via the GitHub Repository and send your feedback by posting to the Discord Channel.

* Github Repository: https://github.com/RuthAndRoth/Roth2
* Discord Discussion Channel: https://discordapp.com/channels/619919380154810380/619919380691550240
* Discord Discussion Channel Invitation (open to all): https://discord.gg/UMyaZkc
* MeWe Community Page: https://mewe.com/group/5bbe0189a5f4e57c73569fb9
* Second Life Marketplace: https://marketplace.secondlife.com/stores/228512
* Second Life Groups: "RuthAndRoth" and "Ruth and Roth Community"
* OpenSim Group: OSGrid RuthAndRoth
* OpenSim Region: OSGrid RuthAndRoth hop://login.osgrid.org/RuthAndRoth/128/128/26

============================================================
CREDITS

* Original Roth 2.0 RC#1 mesh by Shin Ingen with rigging and vertex weight maps by Ada Radius.
* Roth2 v2 is based on Roth 2.0 RC#1 (now referred to as Roth2 v1).
* Repository management and testing by Fred Beckhusen, Outworldz LLC (Ferd Frederix), Ai Austin and Serie Sumei.
* Revised mesh, rigging and vertex weight maps by Ada Radius.
* UV map is CC-BY Linden Lab.
* Skin templates by Chip Midnight:  http://forums-archive.secondlife.com/109/72/40762/1.html
* Skins included in the HUD:
   - Eloh Elliot Skins
   - Adamek Titanium Skins
* T-Shirt Texture by Robin (Soujourner) Wood: https://www.robinwood.com/Catalog/Technical/SL-Tuts/SLPages/RSW-TShirt.html
* Linda Kellie Designs - Tintable Bra and Panties - Creative Commons CC0 https://zadaroo.com/wp-content/uploads/2012/12/templates-bra-and-panties.zip
* HUD mesh, textures and scripts by Serie Sumei using modifications to original scripts by Shin Ingen.
* Elf Ears: AGPL by Fred K. Beckhusen (avatar: Ferd Frederix) and Ai Austin.
* R2 Logo by Serie Sumei based on original by Shin Ingen: https://github.com/RuthAndRoth/Extras/tree/master/Textures/Logo
* Thanks to all contributors as listed in the LICENSE text file.
