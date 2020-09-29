# DhandsUI

The official Dhands UI. Profiles for ElvUI, Plater, and Details.

## Adding Custom Font to ElvUI

1. Download the fonts from GitHub
1. Copy/Paste them into World of Warcraft > \_retail_ > Interface > AddOns > ElvUI > Media > Fonts
1. Go back to the "Media" folder and open SharedMedia.lua in a text editor
1. Scroll down to the section with the "AddMedia" lines, and add the following lines:

AddMedia('font', 'Poppins-Medium.ttf', 'Poppins Medium')

AddMedia('font', 'Poppins-SemiBold.ttf', 'Poppins SemiBold')

5. Save the file, and you're done!
