# Unpack

When you want to unpack a compressed file, for several format you need to know a lot of ambiguious parameters witch you never remember.

So, in every incompression, you search in man pages, by duckduckgoing, by checking documentation, or alos with the exellent [tldr](https://github.com/tldr-pages/tldr) or [eg](https://github.com/srsudar/eg) to just find this two fucking options: `tar xf`. But this isn’t a good solution.
![Xkcd n°1168](http://imgs.xkcd.com/comics/tar.png)

Because you just want to type `unpackForMeThisFuckingArchiveDumyComputerIDind’tCareAboutHisFormat <archivename>` I made this script witch I just call, for more simplicity, `unpack`. He also defuse tarbombs and create a special folder when there is more than just one file on the archive.

That’s it.
