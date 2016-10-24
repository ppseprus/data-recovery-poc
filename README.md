# Data Recovery POC

## The Problem

A few days ago, I've formatted a 2TB external drive that contained approximately 10 years of my life.

I used to be a photographer and most of the stuff gone are raw photographs, however, I also had hours of videos recorded of intimate moments with friends and family.

There's a company which might be able to restore all that, but they are very pricey.

Previously, I had my unfortunate encounters with data recovery tools and the most important things I learned are 1) that no recovery is a 100% successful, and 2) that you almost certanly loose the file system - the structure that kept things together.

With 10 years of visual data, subjects are separated to subfolders, years are split to different folders, locations are stored with the folder names... etc.
Anyone who ever wanted to organise an aweful lot of data, know that there has to be a system to it.
Accessing any file without searching for it for hours is only possible with a well-designed system.

I have to have that back.

I'll attempt to have the files back while also restore the file system.

## The Solution

Most probably I know only as much as the next guy, therefore, this is not about creating a new software. I will not be able to think of anything revolutionary. I will only use the softwares that are already available.

The plan is to use a 32GB SD card to create a test environment to which I copy similar files only to format that very card.
Than I will compare multiple softwares to determine which is the best for my situation.

The outcome shall be a _choice of software_ that I will use to recover the most of what is lost. But this is most probably highly dependant on the original, damaged file system, therefore, _this is rather a kind of blog post than an actual howto_.

## The Data

I have a Nikon, so the main target is the `.NEF` file - the Nikon Electronic File.
The videos have nothing special to them, but I had tons of `.psd` files on the drive too.
The `.jpg` files are in many kinds as for their origin. I have copies of the raw Nikon files as well as compressed copies of the `.psd`s. I also had lots of old photographs scanned.

To be honest, I don't know if these make any difference.

## The Situation

I wanted to to format an SD card...

I had this external drive for almost two years now and to be honest, I don't remember what the original file system was. I own a MacBook Pro, so it is either HFS or a Fat32 file system.

To make things even more complicated, when I realised what I have done, I pulled the drive off the computer so the formatting was interrupted.

Again, I have no idea whether this is a good thing or if I only made things worse.

## The Steps

1. Organise the test data
2. Create a local copy of the test data
3. Format the SD card, using _Disk Utility_
	A. Mac OS Extended (Journaled)
	B. Fat32
4. Copy the test data onto the SD card
5. Format the SD card, using _Disk Utility_
	A. Fat32
	B. ExFat
6. **Interrupt the formatting**
7. Select a program for _the list_
8. Try every possible way of recovery
9. Assess results and note observations

## The Test Data

Root
- **test folder 1**
	- **first level subfolder**
		- **second level subfolder**
			- Photoshop edited `.jpg` files
		- raw `.jpg` files recorded with my phone
	- **roll film scans**
		- raw `.jpg` files created by the scanner
		- `.psd` files of the above
	- a random `.mov` video recording
- a random `.wav` file
- a `.gif` of friends

The total size of the data is 4.22GB.

