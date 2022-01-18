# RavenFall-Bot

A bot for a Twitch game called Ravenfall.  
  
Run without download from here: <https://valen-h.github.io/RavenFall-Bot/ravenbot.html>  

## Settings

* **D** - Dungeons Enabled.
* **D(x)** - Enable Dungeons and respond to `x` (RegExp) sent by anyone (including non-bots).
* **R** - Raids Enabled.
* **R(x)** - Enable Raids and respond to `x` (RegExp) sent by anyone (including non-bots).
* **J** - AutoJoin Enabled.
* **J(x)** - Enable AutoJoin and join as `x` [`x` must by _alphanumeric_ and **not capitalized!**].

## Notes

### AutoFilling

> `a,,,` becomes `a,a,a,a`.  
> `a,,b,` becomes `a,a,b,b,b,b` when provided 6 channels.  
> `a` becomes `a,a,a` for 3 channels etc...  

### Misc

> * The use of D(!dungeon), R(!r) allow the player to enter dungeons/raids only after other people have entered instead of going solo.  
> * If you change any settings you need to re-submit.
