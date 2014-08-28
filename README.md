#ahud

it's a hud

a simplistic hud for team fortress 2 first started by [kyle](https://github.com/hikyle). ahud draws inspiration from various huds, including, but not limited to, rayshud, yahud, and omphud.


###features

* custom colors
* custom crosshairs
* home server button
* 6v6 and 9v9 scoreboard
* some MvM support
* non-box version

###screenshots

* http://i.imgur.com/aISnlb6.jpg - main menu
* http://i.imgur.com/EhIw9I6.jpg - team select
* http://i.imgur.com/zEhjEy4.jpg - class select
* http://i.imgur.com/n3Wu0iD.jpg - buffed hp
* http://i.imgur.com/5hl5O9F.jpg - low hp
* http://i.imgur.com/XGNavjY.jpg - buffed hp (non-box)
* http://i.imgur.com/j2t8Mj2.jpg - low hp (non-box)
* http://i.imgur.com/lDXTtPm.jpg - default scoreboard
* http://i.imgur.com/jkn9H8W.jpg - 6v6 scoreboard
* http://i.imgur.com/fs8oP55.jpg - tournament spectator hud

more screenshots can be found [here](http://imgur.com/a/569GH)

###installation & setup

extract the materials, resources, and scripts folder inside a newly created folder (named ahud, but it can by anything) inside your custom folder. for a detailed how-to on installing a hud for tf2, check out [this guide](http://huds.tf/guides/?guide=1) on huds.tf

to use the home server button that is on the bottom right of the main page, simply put *alias JoinHomeServer "connect x.x.x.x:xxxx"* in your autoexec.cfg. 

to use the non-box version of ahud, locate *hudplayerhealth.res* and *spectatorguihealth.res* in resources/ui, and *hudanimations_tf.txt* in scripts. delete or backup these 3 files and rename the replacement *xxx_NOBOX.xxx* versions to the original names.

###support

i have only tested this on my windows pc using a 16:9 resolution; so far it seems to work on 16:10. 4:3 resolution support possible in the future (if it doesn't work fine already). no mac or linux support. 

please post any bugs with ahud to the issues page on this repository. there is also a [steam group](http://steamcommunity.com/groups/ahud) you can join to get announcement for updates to ahud.


###testimonials

"*It didn't improve my FPS but it stopped it from dipping.*" - 5pike, UGC Platinum Heavy for Land Before Time
