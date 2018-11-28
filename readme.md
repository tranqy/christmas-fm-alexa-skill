# 🎄 Christmas FM Alexa Skill 🎄

As a long time Chirstmas FM listener not being able to listen on home Echo was not going to work. Christmas FM is available via TuneIn, but TuneIn for Alexa is not free. 

This repository is a working, single purpose Alexa skill to stream Chirstmas FM while it's available. 

I started with the Dabble streaming template (Dabble license file still included)

https://dabblelab.com/

I then grabbed the Chirstmas FM stream URL from here

https://christmasfm.com/listenin/

Changed the Stream URL in the lambda function, troubleshot for a minute until I realized we needed to use the https version, then had it streaming just in time to catch Christmas Shoes. 

## Getting Started

1) Clone this repository
2) Install the ASK CLI from Amazon [Here](https://developer.amazon.com/docs/smapi/quick-start-alexa-skills-kit-command-line-interface.html)
3) Configure ASK [Instructions here](https://developer.amazon.com/docs/smapi/quick-start-alexa-skills-kit-command-line-interface.html)
3) Rename ./ask/config_template to ./ask/config
4) Run ask deploy (I use the VS Code plugin from [here](https://marketplace.visualstudio.com/items?itemName=ask-toolkit.alexa-skills-kit-toolkit))
5) Say "Alexa open my chirstmas fm"

## Tips and donations
Christmas FM is a charity station. Please direct all donations to Christmas FM's charity partner, Temple Street Children's University Hospital. 

[Christmas FM Donation Page](https://www.templestreet.ie/Christmasfm/?utm_source=christmasfm.com&utm_medium=main_menu_link)

🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄🎄
