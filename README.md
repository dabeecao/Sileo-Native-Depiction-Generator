# About
Native Depiction Generator is used to create native depiction files to use for the Sileo application. The script uses a JSON file with placeholder text inside and when the script runs it creates a copy of that file and replaces the placeholder text with infomation that the users enters. 

# FaQ
Q: How can I run this script?<br />
 A: Download Python 3 for your operating system and run the script. If you are using a terminal enter "python3 generator.py".<br />
Q: How can I add the depiction file to my package for Sileo?<br />
 A: Upload the generated file to your repo's directory and open your Packages file and add the key SileoDepiction to it.<br />
    Example: http://example.com/native-depictions/nativedepictionfile<br />
    Read more at https://developer.getsileo.app/native-depictions<br />
Q: Why is there only 1 template?<br />
 A: More templates will be added sometime in the future.<br />
Q: Why can I only add 1 screenshot?<br />
 A: Multiple screenshot support will be added in the future so for now you will need to edit the depiction file and add it yourself.<br />
Q: Why can't I add version/changelog history?<br />
 A: Version/changelog history support will be added in the future so for now you will need to edit the depiction file and add it yourself.

# Changelog
0.2:
 + Now Removes placeholder text.
 + Added more error handling.
 + Added support for header image.
 + Fixed typos.<br />
0.1:
 + Initial Release.
 
# To Do
 - Add support for multiple screensots.
 - Add version/changelog history support.
 - Add more templates.