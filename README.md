## Reporting Issues

Most issues should be reported [upstream](https://gitlab.com/xonotic) where they're more likely to be noticed. Flatpak-specific issues may be reported here or upstream.

## Running the dedicated server

The dedicated server included in this flatpak may be started with `flatpak run --command=xonotic-dedicated org.xonotic.Xonotic`. It requires [additional configuration](https://gitlab.com/xonotic/xonotic/-/tree/master/server) to be usable.

## File locations

Config files, player/server ID keys, custom maps and other data are saved in `~/.var/app/org.xonotic.Xonotic/.xonotic/` (flatpak-specific).
