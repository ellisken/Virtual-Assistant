# Virtual-Assistant
A virtual assistant is a software agent that can perform tasks or services for an individual.The term
”chatbot” is also used to refer to virtual assistants.

Virtual assistants use Artificial Intelligence to match user text input to executable commands.
It can provide a wide variety of services, These includes:
<ul>
<li>Weather information of any place</li> 
<li>Play multimedia files such as audio songs and video songs</li> 
<li>Open Applications such as Web browsers, Media players(like vlc), text editors, etc</li>
<li>Open directories in linux, Date and time</li> 
<li>Search anything on Google</li> 
<li>Open websites of user’s choice</li>
</ul>

# Setup

This program uses <b>GNUstep speech engine</b> for the purpose of text to speech.
To use this feature few commands are needed:

say converts text to audible speech using the GNUstep speech engine.

```
$ sudo apt-get install gnustep-gui-runtime
$ say "hello"
```
Firefox is needed to perform browser tasks such as opening google and youtube.

```
$ sudo apt-get install firefox
```

# Weather

This feature requires curl.To use this feature you need to first install curl as follows-

```
$ sudo apt-get install curl
```
# Music

Virtual assistant can play any audio or video files of your choice.
For playing media files vlc is needed.
Get it here 
```
$ sudo apt-get install vlc
```
Please configure your working directory location before using this feature in config file (value of HOME_DIR)
```

# Youtube Search

Virtual assistant can search anything on youtube.
Just type -
```
search youtube for Music
```
This will show all the videos on youtube related to Music.
Music is an example here, you can use anything you want to search.

# Contributing Guide
<ul>
<li>This repository is strictly based on C language. No contributions other than C will be accepted.</li>
<li>When contributing to this repository, please first inform or discuss the change(s) you wish to make via an issue. This helps in letting   others know what you're working on.</li>
<li>Before you push your changes to GitHub, make sure that your code compiles and runs without any errors or warnings.</li>
<li>New features are always welcome and as of now this project is under development.</li>
</ul>


# License

ritwik12/Virtual-Assistant is licensed under the
GNU General Public License v3.0

Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.



