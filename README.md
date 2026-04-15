![Mod Version](https://api.geode-sdk.org/v1/mods/fleym.nongd/status_badge?stat=version)
![Downloads](https://api.geode-sdk.org/v1/mods/fleym.nongd/status_badge?stat=downloads)
![GD Version](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.geode-sdk.org%2Fv1%2Fmods%2Ffleym.nongd%3Fabbreviate%3Dtrue&query=payload.versions%5B0%5D.gd.win&label=Geometry%20Dash&labelColor=%230c0811&color=%235f3d84&link=https%3A%2F%2Fgeode-sdk.org%2Fmods%2Ffleym.nongd&style=plastic&logo=data%3Aimage%2Fsvg%2Bxml%3Butf8%2C%253Csvg%2520xmlns%253D%2522http%253A%252F%252Fwww.w3.org%252F2000%252Fsvg%2522%2520aria-hidden%253D%2522true%2522%2520role%253D%2522img%2522%2520width%253D%25221.01em%2522%2520height%253D%25221em%2522%2520viewBox%253D%25220%25200%2520716%2520715%2522%253E%253Cpath%2520d%253D%2522M318.756%2520132.079L255.116%2520195.719C250.234%2520200.601%2520250.234%2520208.515%2520255.116%2520213.397L318.756%2520277.036C323.637%2520281.918%2520331.552%2520281.918%2520336.433%2520277.036L400.073%2520213.397C404.954%2520208.515%2520404.954%2520200.601%2520400.073%2520195.719L336.433%2520132.079C331.552%2520127.198%2520323.637%2520127.198%2520318.756%2520132.079ZM459.47%2520224.71L224.71%2520459.47C219.829%2520464.351%2520219.829%2520472.266%2520224.71%2520477.147L288.35%2520540.787C293.232%2520545.669%2520301.146%2520545.669%2520306.028%2520540.787L540.787%2520306.028C545.669%2520301.146%2520545.669%2520293.232%2520540.787%2520288.35L477.147%2520224.71C472.266%2520219.829%2520464.351%2520219.829%2520459.47%2520224.71ZM195.012%2520255.823L131.372%2520319.463C126.491%2520324.344%2520126.491%2520332.259%2520131.372%2520337.14L195.012%2520400.78C199.893%2520405.662%2520207.808%2520405.662%2520212.69%2520400.78L276.329%2520337.14C281.211%2520332.259%2520281.211%2520324.344%2520276.329%2520319.463L212.69%2520255.823C207.808%2520250.942%2520199.893%2520250.942%2520195.012%2520255.823ZM8.3357%2520356.232L356.232%25208.33571C357.209%25207.3594%2520358.791%25207.3594%2520359.768%25208.33571L707.664%2520356.232C708.641%2520357.209%2520708.641%2520358.791%2520707.664%2520359.768L359.768%2520707.664C358.791%2520708.641%2520357.209%2520708.641%2520356.232%2520707.664L8.3357%2520359.768C7.35939%2520358.791%25207.35939%2520357.209%25208.3357%2520356.232Z%2522%2520fill%253D%2522%2523FFFFFF%2522%253E%253C%252Fpath%253E%253C%2521----%253E%253C%252Fsvg%253E)
![Geode Version](https://api.geode-sdk.org/v1/mods/fleym.nongd/status_badge?stat=geode_version)

# Jukebox

<img src="./logo.png" alt="Jukebox logo" />

Jukebox is a song manager for Geometry Dash made with the goal of simplifying the process of swapping in-game songs with any NONGs.

## What is a NONG, anyway?

NONG stands for **Not On NewGrounds**. Basically, it means any song that is not available in-game that was replaced manually through external means.

NONGs have always been a hassle to manage, because some level creators use popular Newgrounds song IDs and replace them with a NONG. So you have to swap those song files around quite a bit if you play a level with the Newgrounds song and a level with a NONG song.

## Start your jukebox!

Jukebox makes the process of managing your songs a breeze. You can download your NONGs using your method of choice. My recommandations are: [Cobalt](https://cobalt.tools/) and [yt-dlp](https://github.com/yt-dlp/yt-dlp), a CLI application. After getting your MP3 file, you can enter a song and author name, for easier management.

> Note that Jukebox copies imported songs in the storage location designated by Geode. You can open this folder from ingame.

Alternatively, you can download songs **ingame** from configurable sources, known as indexes. Jukebox provides the **Song File Hub** index as a base, which is a database of NONGs made specifically for Geometry Dash. Ideally, you should be able to get most of the songs you need from here :) 

> You can add your own indexes if you want, more documentation on this will be provided soon!

## So, how do I begin?

You can open up the Jukebox menu from any level page. Just click on the song name, and the song management screen will open. From here, you can add, remove, download and swap songs.

## Reporting bugs

You can report bugs on the [Song File Hub Discord server](https://discord.gg/maSgd4zpEF)

## Credits

- The Geode team, for creating such an amazing toolkit
- Flafy, for creating Auto Nong and afterwards becoming a co-developer
- The nice lads over at Song File Hub for managing the biggest NONG database in GD
- hiimjasmine, for porting the mod to MacOS
- undefined06855, for helping me with parsing song metadata using FMOD

## Licensing

This mod is licensed under **MIT**, so poke around, everything is free as in speech.
