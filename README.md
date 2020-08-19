# FoundryVTT - Forien's Copy Environment
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/forien/foundryvtt-forien-copy-environment?style=for-the-badge)
![GitHub Releases](https://img.shields.io/github/downloads/Forien/foundryvtt-forien-copy-environment/latest/total?style=for-the-badge)
![GitHub Releases](https://img.shields.io/github/downloads/Forien/foundryvtt-forien-copy-environment/total?style=for-the-badge)    
**[Compatibility]**: *FoundryVTT* 0.6.0+  
**[Systems]**: *any*  

This module allows for fast copy/save environment data such as core version or list of installed modules and their versions. Supports copying as TXT or saving as JSON.

Module also allows to export (save/backup) current game settings and then import (restore) them. Non-GM users can only import client-side settings.

## Installation

1. Install Forien's Copy Environment using manifest URL: https://raw.githubusercontent.com/Forien/foundryvtt-forien-copy-environment/master/module.json
2. While loaded in World, enable **_Forien's Copy Environment_** module.

### Usage

Go to Settings tab in Sidebar and **right click** on data **below** "General Information" header

![](https://i.gyazo.com/8f41b4e7f52e8f560f9265774a9849db.gif)

## Features

* Copy Environment (core, system and module versions) to clipboard
* Save Environment (including manifest links) as a JSON file
* Export game settings (both 'world' and 'client' scopes)
* Import game settings ('client' ones, and if you are GM also 'world' ones)

*Please note that importing 'world' scope settings en masse as GM might cause some issues to connected players. I advise players should logout before attempt to import World Settings*

## Contact

If you wish to contact me for any reason, reach me out on Discord using my tag: `Forien#2130`


## Support

If you wish to support module development, please consider [becoming Patron](https://www.patreon.com/foundryworkshop) or donating [through Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6P2RRX7HVEMV2&source=url). Thanks!

## License

Forien's Copy Environment is a module for Foundry VTT by Forien and is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

This work is licensed under Foundry Virtual Tabletop [EULA - Limited License Agreement for module development from May 29, 2020](https://foundryvtt.com/article/license/).
