# Automation

Automation Groups get started guide thing

### Prerequisites
You will need to make any of the projects mentioned under the tools section using any of the tools below, this is to make sure uk at least the basics of the most sinmplest ways of automation.
All of the simple projects will give u an idea of how fun automation is.

## The Tools
### IFTTT
IFTTT is mostly a free way to get a basic idea of automation and unless u live under a rock u already know about this
But if u dont check these [this](https://www.youtube.com/watch?v=p5McvkJYL2s) 

IFTTT also has many more options if u want to do more advanced tasks on the web
to know how to make more advanced IFTTT applets check their [Documentation](https://platform.ifttt.com/docs) 

### MacroDroid
*MacroDroid is the easiest way to automate your daily tasks on your Android smartphone or tablet. Via the smart user interface MacroDroid offers a simple solution to make automated tasks on your device in just a few taps.*

This is the most easiest Way to get started with basic android automation
Install it from [here](https://play.google.com/store/apps/details?id=com.arlosoft.macrodroid&hl=en_IN)

If you cant figure out how to use this basic tool: [TUTORIAL](https://www.youtube.com/watch?v=8YL9cWCykKc)
You need to at least know how to use variables and timers in macrodroid to move to the next tool

### Tasker (Paid)
Tasker is The most powerfull android automation tool which can be used by the most useless to actual devs to test apis or prototype certain behavior or just to even prank people if ur still in 2012

* Tasker has the power to export the automation profiles as seperate apps and install them on phones as stand alone apps.
these apps can be published on playstore, but its really better not to.

I recommend buying the app from gplay instead of getting a cracked version as this supports its development.
The recent Tasker have given it more power than ever and with endless potential.
* install it [here](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en_IN)

#### Tasker+JavaScript
If ur a javaScript dev you can write scripts that perform android actions using JavaScript.
but async/await cant be used with the Tasker JavaScript functions.

Just so that u get a the slighest idea what tasker can do check [this](https://www.youtube.com/watch?v=bINUcn0QXvg)
* [Get Started](https://www.youtube.com/watch?v=EVNUGUv-lIY)

### Termux Api (Pointless but just for the sake of it)
Using Shell script u can use the termux api to automate ur phone tasks

### Node-Red
Node-red is mainly used for server sided automation tasks but can also be used to auto mate tasks on ur computer (or even phone if u run this on termux like a sociopath)
node-red can be used to establish a communication between ur anything with internet and where ever ur running node-red
u can check it out [here](https://www.youtube.com/watch?v=GeN7g4bdHiM)
more [links](https://www.youtube.com/watch?v=2_ev1NCTVgg)

### Android SDK
if ur an android dev or not u can always make an app using android studio and android sdk to really auto make anything on ur phone Duh

### Scripting Languages
You can always use scripting languages like python or javascript or shellscripting too for automation on any device


#### The Projects
as this is just a get started guid all of these projects can be made in tasker or macrodroid.
ideal case use tasker

* #### Clipboard Searcher
- googles things by coping them
```
- Detects wwhen u copy a text and asks u in the notification if u would like to google it
- Logs everything that a user copies to clipboard into a log.txt file or a google sheet
```

* #### Emergency Finder
- find ur phones exact location by texting it from nother phone
```
- Texts u back the location of ur phone when u text it a specific phrase like 'where r u'
- Logs every run into a log.txt file or a google sheet
```

* #### Morning Facts
- reminds u every morning that the only notification u will get is about a fact about a random number
```
- Notifies a nerd facts about a random number every morning
- makes an api call to http://numbersapi.com/ to get the facts
- Logs every fact into a log.txt file or a google sheet
```

* #### Backup thing
- backs up any folder
```
- backs up a folder of ur choice when it detects a new file is added to the folder (this maybe more complicated than it sounds)
```

* #### Hide?
- Hides ur porn
```
- Closes chrome or whatever browser u use when u put ur phone facing down or unplug ur headphones or disconnect ur bluetooth earphones
- or if u have it all offline for whatever reason close whatever player u use and maybe hide it all from gallery
```

* #### Make sure I wake up
- Whatever it takes to wake up the user at a set time
```
- Whatever it takes to wake up the user at a set time
```
