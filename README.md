# DhandsUI

The official Dhands UI. Profiles for ElvUI, Plater, and Details.

## Adding Custom Fonts to ElvUI

1. Download the fonts from GitHub
1. Copy/Paste them into World of Warcraft > \_retail_ > Interface > AddOns > ElvUI > Media > Fonts
1. Go back to the "Media" folder and open SharedMedia.lua in a text editor
1. Scroll down to the section with the "AddMedia" lines, and add the following lines:

AddMedia('font', 'Poppins-Medium.ttf', 'Poppins Medium')

AddMedia('font', 'Poppins-SemiBold.ttf', 'Poppins SemiBold')

5. Save the file, and you're done!

## Plater Setup

1. When you first log in, ElvUI will have a popup asking you whether you want to use Plater or ElvUI nameplates. Select Plater.
1. Open Plater by typing `/plater`, then click the "Profiles" tab.
1. Click "Import Profile", paste the contents of `plater.txt`, and click "Okay"

## ElvUI Setup

1. When you first log in, you should see the ElvUI install panel. Click the "Setup cvars" and "Setup chat" buttons, and skip the rest of the steps.
1. After the reload, open ElvUI by typing `/ec` and click the "Profiles" tab in the bottom left. Then click "Import Profile" at the top, and paste the contents of `elvui.txt`
1. When the import is done, go back to the ElvUI options panel, and navigate to "General > Media". Set CombatText Font and Name Font to Poppins SemiBold.
1. Last, right click the "Loot/Trade" chat tab in the bottom right of your screen. Select "Unlock Window" and drag the tab over to the left chat panel.

## Details Setup

1. Click the settings icon on the Details window.
1. Click the "Profiles" tab button.
1. Click the "Import Profile" button, paste the contents of `details.txt`, then click "Okay"
