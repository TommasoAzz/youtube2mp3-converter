# youtube2mp3-converter for Linux/Ubuntu
## Simple and dumb script to download videos from **YouTube** and convert them to **.mp3** files.

Just two simple script file:
* **install_script**;
* **youtube2mp3-converter**.

What they do is just automating the process of using the programs that this script uses for getting its job done.

### Dependencies
* ffmpeg
* python
* youtube-dl

### How to install youtube2mp3-converter
1. Download both the script files from this repository
1. Put them both in the same directory
1. Type **install_script** and press **ENTER** (you'll get asked to type your password, as there are some commands that require admin authorization)

### How to use the script once it's installed
Just type: **youtube2mp3-converter \[filename\]** and press **ENTER**<br />
**filename** has to be a text file with this simple syntax:

any.youtube.linkNo1/11charsCodeThatYoutubeUsesToIdentifyVideos
any.youtube.linkNo2/11charsCodeThatYoutubeUsesToIdentifyVideos
any.youtube.linkNo3/11charsCodeThatYoutubeUsesToIdentifyVideos<br />
...<br />
any.youtube.linkNo1000/11charsCodeThatYoutubeUsesToIdentifyVideos<br />
(blank line)

* You can literally put how many YouTube links you wish in that file. The program will handle them.
* The file **has to end with a blank line**. That's important otherwise the last video of the list **won't be downloaded**!

### Some important stuff
1. I'm neither the owner nor the writer of all the dependencies. They were all found on the Internet.
1. Sometimes files don't get downloaded correctly (you can see it because they don't convert to .mp3 as they remain partial video files). Just delete those broken files and download them again.
1. Never leave .mp3 files in the folder where you are currently downloading some videos (the file name of these files will get cut, I said it, *it's a really dumb program*)
1. Sometimes **youtube-dl** can't download some videos. Just accept it, use some other tool if you really need that song downloaded.
1. Feel free to make this tool less dumb, if you wish.
1. Hope it helped you, bye!
