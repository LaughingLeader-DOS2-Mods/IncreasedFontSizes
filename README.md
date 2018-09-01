Increased Font Sizes for Divinity: Original Sin 2 Definitive Edition
=======

A guide for scaling the size of DOS2DE's font directly with the font files. Works as an override, so achievements should stay enabled.

# Support
If you're feeling generous, an easy way to show support is by tipping me a coffee:

[![Tip Me a Coffee](https://i.imgur.com/NkmwXff.png)](https://ko-fi.com/LaughingLeader)

All coffee goes toward fueling future and current development efforts. Thanks!

# Scaling the Fonts

## Setup
1. Download [FontForge](https://fontforge.github.io/en-US/downloads/windows-dl/).
2. Download [Norbyte's Pak Extractor Tool](https://s3.eu-central-1.amazonaws.com/nb-stor/dos/ExportTool/ExportTool-latest.zip)
3. Using the Pak Extractor Tool, extract `Divinity Original Sin 2\DefEd\Data\Game.pak`.
4. Wherever you extracted Game.pak, navigate to this directory: `Public\Game\GUI\fonts` and copy the following files:
	* `COLLEGIATEBLACKFLF.TTF`
	* `QuadraatOffcPro.ttf`
	* `QuadraatOffcPro-Bold.ttf`
	* `QuadraatOffcPro-Italic.ttf`
	* `wts11.ttf`
5. Create the following pathway (by creating the missing folders) in the DOS2 Data directory: `Data\Public\Game\GUI\fonts`
6. Paste the font files you copied in step 4 into this new `fonts` directory.

### Result:  
![Font Overrides](https://i.imgur.com/NksC28ll.png "The new font file overrides.") 

## Font Scaling
The following steps can be applied to each font (.ttf) file: 
1. Open FontForge.
2. Open the font you want to scale.
3. CTRL+A to select everything.
4. Click Element -> Transformations -> Transform... (Shorcut `CTRL + \`)  
![Opening the Transform Menu](https://i.imgur.com/AsTT4c5.png "How to open the Transform menu.")  
5. Select the following options, and click OK:  
![Transforming the Font](https://i.imgur.com/wcrPkWu.png "How to open the Transform menu.")  
6. Ignore whatever warnings/errors you may get. When the transforming is done, click File -> Generate Fonts...
7. Copy the following generation options, and name your font the same name as the original file:
![Generating the Font](https://i.imgur.com/XMdAQgD.png "Generation options.") 
8. Repeat for the other fonts.

# Comparison Screenshots

[![Font Size Comparison](https://thumbs.gfycat.com/FrightenedMiserlyAmericanshorthair-size_restricted.gif)](https://gfycat.com/FrightenedMiserlyAmericanshorthair)

# Frequently Asked Questions
## "How high can the scaling go?"
* Since font sizes are being scaled within the font file itself, anything too high may break the UI in certain ways. 200% in particular lookes bad:  

 [![200% Scale](https://i.imgur.com/PuhMIDkl.png "Font scaling set to 200%.")](https://i.imgur.com/PuhMIDk.png)
 
## "Why is this a guide, and not a release?"
* The fonts used in DOS2 all appear to be copyrighted (and quite expensive), so unfortunately re-distributing them is a no-no. Sorry!
