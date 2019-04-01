## FAQ
* [General Questions](#general-questions)
  * [Why are some characters missing?](#why-are-some-characters-missing)
  * [Can you do a version of this that's compatible with ________?](#can-you-do-a-version-of-this-thats-compatible-with)
  * [May I contribute my own art for portraits and such?](#may-i-contribute-my-own-art-for-portraits-and-such)
  * [Can you do a sprite of (some character) for (some situation)?](#can-you-do-a-sprite-of-some-character-for-some-situation)
  * [I found a problem! Can you fix it?](#i-found-a-problem-can-you-fix-it)
* [Troubleshooting](#troubleshooting)
  * [Portraits Not Working](#portraits-not-working)
  * [Outfits Not Loading](#outfits-not-loading)

## General Questions

### Why are some characters missing?
Because I made this mod with [Longevity's](https://www.nexusmods.com/stardewvalley/mods/649?tab=files) DNPCC in mind. I didn't want the outfits to have a huge overlap and also the sprites they have are wonderful! We do not have permission to upload their artwork, so if you want to combine the two outfit sets, you will have to add them to the mod and only use it personally. [Content patcher instructions are here](https://github.com/Pathoschild/StardewMods/tree/stable/ContentPatcher#readme).

### Can you do a version of this that's compatible with?
Maybe! I don't have a ton of free time, so if I do it'll probably be a long time. Leave me a request in the posts section. Also, if you really would like to do a crossover version with your favorite mod and you want to create it, you totally have permission on my end (don't forget to ask the other mod author of whichever mod you want to combine it with). I will happily add it to the mod.

### May I contribute my own art for portraits and such?
YES! Please! Comment in the posts section or send me or paradigmnomad a DM with your wonderful artwork and we'll add it to the next update.

Alternatively, check out these awesome packs that pair well with SVO:
[Seasonal Anime Portraits (Add-on)](https://www.nexusmods.com/stardewvalley/mods/3202) by [FlashShifter](https://www.nexusmods.com/stardewvalley/users/46021252)
[Too Many Elliott Portraits - Fixed Originals - Forward-Facing - Topless - Seasonal - Flower Festival](https://www.nexusmods.com/stardewvalley/mods/3488?tab=description) by [LumenDeLumine](https://www.nexusmods.com/stardewvalley/users/8477362)

### Can you do a sprite of (some character) for (some situation)?
Maybe! Again, leave a request in the posts and I might do it. I am also totally accepting people submitting their designs for outfits if you want to send it to me.

### I found a problem! Can you fix it?
Yes. Let me know what it is via the bugs/reports section on the Nexus page. Alternatively, if you know the fix feel free to send a PR to this repository.

## Troubleshooting

### Portraits not working
Make sure you have launched the mod at least once to generate the config.json inside of the [CP] Seasonal Villager Outfits folder.
Open the config.json and you'll see an entry titled `PortraitStyle`. Make sure inbetween the quotation marks `"` you type either `standard` or `dcburger` (for HD portraits). Leaving this blank will use the games vanilla files.

There is a known issue with ScaleUp making the DCBurger portraits not show up correctly. This is a ScaleUp issue, not an SVO issue.

### Outfits not loading
Not every NPC has an outfit for every season/weather. If something isn't changing this is most often the case but you can always check the SMAPI console to see if there was an error loading and report it in the bugs section on Neuxs if so. 

