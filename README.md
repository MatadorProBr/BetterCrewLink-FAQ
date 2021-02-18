[![GPL-3.0 License][license-shield]][license-url] [![Appveyor Build][appveyor-shield]][appveyor-url] [![Donate][paypal-shield]](paypal-url)

<br />
<p align="center">
  <a href="https://github.com/OhMyGuus/BetterCrewLink">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center"> <a href="https://github.com/OhMyGuus/BetterCrewLink">BetterCrewLink</a> a <a href="https://github.com/ottomated/CrewLink">CrewLink</a> fork with <a href="https://github.com/MatadorProBr/BetterCrewLink-FAQ#extra-features-in-this-fork">extra features</a> & <a href="https://discord.gg/qDqTzvj4SH"> better support</h3></a>


  <p align="center">
    Free, open, Among Us proximity voice chat.
    <br />
    <a href="https://github.com/OhMyGuus/CrewLink/issues">Report Bug</a>
    ·
  <a href="https://github.com/OhMyGuus/CrewLink/issues">Request Feature</a>
    ·
    <a href="#installation">Installation Instructions</a>
  </p>
  <p align="center">
    <b><a href="https://github.com/MatadorProBr/BetterCrewLink-FAQ#donations">Donate to BetterCrewLink</a></b></br>
  (all donations will be used for the apple developer license and extra servers)</br>
  <br />
   <b><a href="https://paypal.me/ottomated">Donate to ottomated (offical CrewLink)</a></b>
  </p>
</p>
<hr />

<p>
  
<b>Notes:</b><br />

 - For problems with this fork, you can send a message on the discord (ThaGuus#2140 - owner of BetterCrewLink) and he will do his best to resolve it.

 - To get the most of BetterCrewLink use the voice server: <a href="https://bettercrewl.ink">`https://bettercrewl.ink`</a>

</p>
<a href="https://discord.gg/qDqTzvj4SH"> <img src="https://i.imgur.com/XpnBhTW.png" width="150px" /> </a>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Extra features in this fork](#extra-features-in-this-fork)
* [Installation](#installation)
* [Possible Questions](#possible-questions)
* [Create a Server](#create-a-server)
* [Development](#development)
  * [Prerequisites](#prerequisites)
  * [Setup](#setup)
* [Contributing](#contributing)
* [Donations](#donations)
* [Informations](#informations)
* [License](#license)

## About the Project

**CrewLink:** This project implements proximity voice chat in Among Us. Everyone in an Among Us lobby with this program running will be able to communicate over voice in-game, with no third-party programs required. Spatial audio ensures that you can only hear people close to you.

**BetterCrewLink:** A modified version of [CrewLink](https://github.com/ottomated/CrewLink) with improved things such as: optimizations for CPU (solves robotic voices), more settings (listening to people on the cameras), support for mobile BETA ([via app](https://play.google.com/store/apps/details?id=io.bettercrewlink.app)) and more.

## Extra features in this fork
```
- OBS browsersource overlay.
- Hear people in vision only.
- Walls block audio. 
- Volume sliders.
- It doesn't break when someone leaves/disconnects.
- It works on any network even with upnp disabled (Strict NAT)
- More fun settings like hearing through cameras.
- You can actually disable the overlay.
- 32bit support, windows 7 support.
- U can change the volume of alive players after u died.
- U can set BetterCrewLink to topmost.
- Settings actually sync between players and not half.
- CPU usage is lower than original CrewLink.
- U can actually press the mute key/deafen key while clicked on BetterCrewLink.
- Your mouse doesn't start to lagg because of the buggy input hook.
- Changing the speaker setting does actually something unlike original CrewLink where it is always using the default output.
- Compatible with CrewLink 2.0 
- Microphone echo cancellation.
- Microphone noise suppression.
- More overlay positions and you can set the overlay to the top/bottom and you can set it so it shows everyone even when they aren't talking.
- You can set the lobby up so only death people can talk (normal lobbies but then with death talk)
- Support for mobile (BETA)
```
If you want to suggest something that could be added, talk to the owner of BetterCrewLink via Discord: ThaGuus#2140


## Installation

**PC:**

[Click here](https://github.com/OhMyGuus/BetterCrewLink/releases/latest) and go to the Downloads section and click on Download from Github or Download from mirror (you can download either one, they will download the same program), open the program, join or create a room on Among Us and that's it.

or 

Use a web version: https://web.bettercrewl.ink (remember that you will need someone in the room to have the BetterCrewLink application installed on the PC, it must be on the PC with the "Mobile Host" option enabled) 

In my opinion I recommend you use the web version if your PC is a very bad PC, because from what I had in my experience with BetterCrewLink people who download BetterCrewLink and use it with a very weak PC (practically on a very weak laptop) no had a good experience, he suffered from robotic voices constantly, so in my opinion if you have a very weak PC, ask your friend who has a medium or good PC to download and use BetterCrewLink, activate the "Mobile Host" option that is in the settings and then just enter the site, accept microphone permission, put the same name in Among Us and the code too and click on "Connect", enter the room and you're done.

**Android:**

You will need a person using BetterCrewLink on the PC and with the "Mobile Host" option enabled (to activate and just go in the settings and go down until you find the Mobile Host option) and the person on the cell phone will need to have the application from the [Play Store](https://play.google.com/store/apps/details?id=io.bettercrewlink.app) and when you open the application, allow the permissions it will ask for, put the same name and code that is in Among Us, click on "Connect", enter the room and that's it.

**iOS:**

For now there is no support for iOS, but you can bring support for iOS, but the project needs $100 to pay Apple's license to put the app on the App Store, so if you have money and feel like helping [donate via Patreon](https://patreon.com/OhMyGuus), [donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=KS43BDTGN76JQ) or [donate via Buy Me a Coffee](https://www.buymeacoffee.com/OhMyGuus).

or

Use a Web version (until they get $100 to put the app on the App Store): https://web.bettercrewl.ink and when you open the website, allow the permission of the microphone it will ask for, put the same name and code that is in Among Us, click on "Connect", enter the room and that's it.


## Possible Questions

* Q: How it works?
  * A: BetterCrewLink looks at your Among Us memory RAM to get data from your location and with that sends it to the server and the server sends the voice to others who are close to you.

* Q: Is BetterCrewLink a virus?
  * A: No, Windows ends up kind of "blocking" the file because its script is used a lot in viruses to destroy your PC, if you still aren't convinced, [click here](https://www.virustotal.com/) and place the BetterCrewLink file, so it will do a scan of the file with "all" antivirus (some antivirus will say it is a trojan or something, but as I said this script is used a lot in common with viruses)

* Q: How to use BetterCrewLink Mobile?
  * A: You will need a person using BetterCrewLink on the PC and with the "Mobile Host" option enabled (to activate and just go in the settings and go down until you find the Mobile Host option) and the person on the cell phone will need to have the application from the [Play Store](https://play.google.com/store/apps/details?id=io.bettercrewlink.app).

* Q: Does BetterCrewLink work with Steam, Microsoft Store, Epic Game and Cracked versions?
  * A: Yes.

* Q: Can I play with my CrewLink friend with BetterCrewLink?
  * A: Yes, as long as you are on the same server, but if your friend activates a personalized Lobby Settings option that you don’t have in CrewLink, the function will only work for those with BetterCrewLink and for CrewLink users the option will not work, that is my recommendation and that you speak for your friends or people in the room to download BetterCrewLink.

* Can I play on a BetterCrewLink server using CrewLink?
  * Yes, the server works for BetterCrewLink users and with CrewLink users, but it is always recommended that users using the BetterCrewLink server use BetterCrewLink for greater compatibility.

* Q: How to resolve this error: 
ERROR
Couldn't connect to Among Us.
Please re-open CrewLink as Administrator.
Need help? Get support

  * A: Right click on the BetterCrewLink icon and then wait a while and a screen will appear with two options "Yes" and "No" you click Yes and that's it, now BetterCrewLink will work normally (whenever you open BetterCrewLink, you will have to do this step, otherwise it will be giving the error again)

* Q: Does BetterCrewLink update whenever there is an update?
  * A: Yes, they have an updater that whenever you open the program, it will check for any updates, if there is one it will automatically start updating to the latest version.

* Q: Why are robotic voices still going on? 
  * A: Most of the time BetterCrewLink solves the problem of robotic voices that happen with the normal CrewLink, if not, disable some settings in the BETA/DEBUG category, if that also doesn't work, close some programs on your PC that consume a lot of CPU, but if that doesn't work either, go to a PC parts store and buy a better CPU.

## Create a Server

See [OhMyGuus/BetterCrewLink-server](https://github.com/OhMyGuus/BetterCrewLink-server) to learn how to create a BetterCrewLink server (creating a server using BetterCrewLink code instead of CrewLink will bring a lot more support to BetterCrewLink and the server will also work with normal people using CrewLink)

## Development

You only need to follow the below instructions if you are trying to modify this software. Otherwise, please download the latest version from the [github releases](https://github.com/OhMyGuus/BetterCrewLink/releases).

Server code is located at [OhMyGuus/BetterCrewLink-server](https://github.com/OhMyGuus/BetterCrewLink-server). Please use a local server for development purposes.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* [Python](https://www.python.org/downloads/)
* [node.js](https://nodejs.org/en/download/)
* yarn
```sh
npm install yarn -g
```

### Setup

1. Clone the repo
```sh
git clone https://github.com/OhMyGuus/BetterCrewLink.git
cd CrewLink
```
2. Install NPM packages
```sh
yarn install
```
3. Run the project
```JS
yarn dev
```

<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are greatly appreciated.

1. [Fork this Project](https://github.com/OhMyGuus/BetterCrewLink/fork)
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Donations

If you like the project, you have money and want to help them continue the project, donate to them, [donate via Patreon](https://www.patreon.com/OhMyGuus), [donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=KS43BDTGN76JQ) or [donate via Buy Me a Coffee](https://www.buymeacoffee.com/OhMyGuus).

## Informations

The voice proximity chat was originally done by [CrewLink](https://github.com/ottomated/CrewLink) - [ottomatted](https://github.com/ottomated) but was modified by [BetterCrewLink](https://github.com/OhMyGuus/BetterCrewLink) - [OhMyGuus](https://github.com/OhMyGuus) with improvements, features and others, this FAQ was made by a user or a fan of the project, the FAQ is not official and any questions you have between on the [BetterCrewLink Discord](https://discord.gg/qDqTzvj4SH) to ask for support, this FAQ was made to help people searching on GitHub how to use a voice proximity chat (since the BetterCrewLink fork does not appear) and I had no intention of plagiarizing anything from BetterCrewLink and also all the information was taken from there and all links are official from BetterCrewLink/CrewLink.

</p>
<a href="https://discord.gg/qDqTzvj4SH"> <img src="https://i.imgur.com/XpnBhTW.png" width="150px" /> </a>

## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

[license-shield]: https://img.shields.io/github/license/OhMyGuus/BetterCrewLink.svg?style=flat-square
[license-url]: https://github.com/MatadorProBr/BetterCrewLink-FAQ/blob/main/LICENSE
[appveyor-shield]: https://img.shields.io/appveyor/build/OhMyGuus/bettercrewlink
[appveyor-url]: https://ci.appveyor.com/project/OhMyGuus/bettercrewlink
[paypal-url]: https://www.paypal.com/donate?hosted_button_id=KS43BDTGN76JQ
[paypal-shield]: https://img.shields.io/badge/Donate-PayPal-green.svg
