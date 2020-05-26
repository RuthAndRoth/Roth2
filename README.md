# Roth2 Mesh Avatar Project

Roth2 is a low-poly mesh body specifically designed for OpenSimulator. It is built to use standard Second Life(TM) UV maps using scratch-built open source mesh by Shin Ingen, Ada Radius and other contributors from the OpenSimulator Community.

* Github Repository: https://github.com/RuthAndRoth/Roth2
* Discord Discussion Channel: https://discordapp.com/channels/619919380154810380/619919380691550240
* Discord Discussion Channel Invitation (open to all): https://discord.gg/UMyaZkc
* MeWe Community Page: https://mewe.com/group/5bbe0189a5f4e57c73569fb9
* Second Life Groups: "RuthAndRoth" and "Ruth and Roth Community"
* Second Life Marketplace - RuthAndRoth:  https://marketplace.secondlife.com/stores/228512
* OpenSim Group: OSGrid RuthAndRoth
* OpenSim Region: OSGrid RuthAndRoth hop://login.osgrid.org/RuthAndRoth/128/128/26
* OpenSim Kitely Market - RuthAndRoth: https://www.kitely.com/market/store/55043173/RuthAndRoth

## Bakes on Mesh

Roth2 v2 is a single layer mesh that is designed to work well with Bakes on Mesh.  It still has a simplified alpha capability and skin textures may be applied, but in Bakes on Mesh mode system layer alpha masks can be worn to give more control over hidden areas.

## Current Release

Roth2 is currently under development, preparing for a v2 release soon.

## Previous Release

Previous releases of Roth2 may be found in the old Ruth repo on Github and
in a number of places both in Second Life and OSGrid as listed above.

What was formerly called Roth 2.0 RC#1 is now referred to as Roth2 v1 in the current version naming scheme.

## Personal Directories

We have moved all personal directories under the new top-level directory
'Contrib'.  These continue to be used as they always have, as a place for
team members to put things that are still under development before (or until)
they are merged into the master release directories.

## Upload Collada (.dae) and other Artifacts

Since not everyone is set up to perform Blender exports to get the Collada
files for uploading we maintain recent exported .dae files. These correspond
to the .blend file(s) in the Mesh directory.

There is also an OpenSim IAR file that can be used to pre-load OpenSim grids.
These are usually updated at releases. They will help maintain consistent UUIDs
for the assets to minimize duplication when meshes and related assets are used
in world.

## Licenses

Roth2 is AGPL licensed, other contents of this repository are also
AGPL licensed unless otherwise indicated.  See LICENSE.md for specific details.

# Changes from Roth 2.0

The Ruth2 and Roth2 repositories have been extracted from the original Ruth 2.0
repo, retaining all Git history of the files that have been moved.  Some common
files will be moved later to a common repo.  Below is the list of changes for the
files present in this repo:

* Contrib/Shin Ingen/Roth/Uploads -> Artifacts/Collada
  * Artifacts/Collada/osRoth2.0_9k_RC\#1.dae -> Artifacts/Collada/ro2_9k_v1.dae
  * Artifacts/Collada/osRoth2.0_9k_RC\#1_Boxers.dae Artifacts/Collada/ro2_9k_v1_Boxers.dae
  * Artifacts/IAR/R2-Roth-RC1.iar -> Artifacts/IAR/Roth2-v1.iar
* Contrib/Shin\ Ingen/Roth/osRoth2.0_9k_RC#1.blend -> Mesh/ro2_9k_v1.blend
* Licenses.txt -> LICENSE.md
* Mesh/Avatar Roth -> Mesh
  * Mesh/osRoth2_CurrentRelease_DevKit_RC#1.blend -> Mesh/ro2_DevKit_v1.blend
  * Mesh/osRoth2_CurrentRelease_Source_RC#1.blend -> Mesh/ro2_Source_v1.blend
* Mesh/Avatar Roth/IARs -> Artifacts/IAR
* Mesh/Avatar Roth/Scripts -> Scripts
* Mesh/Avatar Roth/Textures -> Textures

## Reference Files

The original Ruth repo contained a number of reference files archived from
various places around the Internet.  Some of those have become hard to find
due to link rot and sites vanishing.

Those archived files are now in their own repo https://github.com/RuthAndRoth/Reference.
