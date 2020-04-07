# PreciousStones

[Spigot](https://www.spigotmc.org/resources/preciousstones.5270/) - v10.7.2

**Source language:** English

## Settings

**Prefix:** `preciousstones.`  
**Variable Regex:** `{[\w.-]+}`  
**Ignore keys:**

```
commandDebug
commandOn
commandOff
commandAll
commandAllow
commandAllowall
commandRemove
commandRemoveall
commandTake
commandAllowed
commandCuboid
commandCuboidOpen
commandCuboidClose
commandWho
commandSetname
commandSetradius
commandSetvelocity
commandDisable
commandEnable
commandExpand
commandContract
commandDensity
commandToggle
commandVisualize
commandMark
commandInsert
commandClear
commandReset
commandSetinterval
commandSnitch
commandSnitchClear
commandTranslocation
commandTranslocationList
commandTranslocationDelete
commandTranslocationRemove
commandTranslocationUnlink
commandTranslocationImport
commandMore
commandCounts
commandLocations
commandInfo
commandDelete
commandSetowner
commandChangeowner
commandList
commandReload
commandFields
commandEnableall
commandDisableall
commandClean
commandRevert
commandBypass
commandHide
commandUnhide
commandRent
commandBuy
commandRentClear
commandRentRemove
commandBlacklisting
commandMigrate
commandGive
commandPlace
fieldSignRent
fieldSignBuy
fieldSignShare
commandSetLimit
commandPull
```

## Manual changes

There was a duplicated key (`noPstonesFound`) that caused the generator to crash (interestingly, they have different values). One of the values was removed.
There was also two other duplicated keys (`showOwner`, `_owner`), but that had the same value in both, so one of them was removed.

## Other information

This plugin uses color placeholders (`{red}`, `{aqua}`, etc...) instead of the actual color codes.  
For the sake of simplicity, these have been passed down to Triton as placeholders, but a future update in the generator should automatically convert these to color codes.
