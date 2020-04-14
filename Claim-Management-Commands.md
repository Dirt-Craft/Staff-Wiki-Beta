## Quick Intro
This covers two different protection methods. Any server will have one of the following. To check, open your inventory. If there is a teams GUI, with 3 differently colored people and a map for claiming you are on a server that uses FTB Utilities, otherwise you are on a grief prevention server.
## FTB Utilities
<dl>
<dt> /chunks info </dt>
<dd> Shows who owns the team in the current chunk (Check hover text!) </dd>
<dt> /teams list </dt>
<dd> Lists all teams </dd>
<dt> /teams get </dt>
<dd> Gets a players team </dd>
<dt> /teams info </dt>
<dd> Gets a team info. Shows who is in the team, etc. </dd>
</dl>

## Grief Prevention
<dl>
<dt> /ignoreclaims (/ic)</dt>
<dd> Ignore claims mode. Allows you to bypass claims. </dd>
<dt> /claimflag (/cf) </dt>
<dd> Shows all the claim flags. </dd>
<dt> /deleteclaim (/dc) </dt>
<dd> Deletes the claim you're standing in, even if it's not your claim </dd>
<dt> /basicclaims (/bc) </dt>
<dd> Switches the shovel tool back to basic claims mode. </dd>
<dt> /claimsubdivide (/sc) </dt>
<dd> Switches the shovel tool back to basic claims mode. </dd>
<dt> /adminclaims (/ac) </dt>
<dd> Switches the shovel tool to administrative claims mode </dd>
<dt> /cuboid </dt>
<dd> Toggles 3D cuboid claims mode. </dd>
<dt> /claimgreeting <"message"> </dt>
<dd> Sets the farewell message of your claim. To unset, /claimgreeting ""</dd>
<dt> /claimfarewell <"message"> </dt>
<dd> Sets the greeting message of your claim. To unset, /claimfarewell "" </dd>
<dt> /claimtransfer <player> </dt>
<dd> Transfer the claim you're standing in to a player. </dd>
<dt> /playerinfo <player> </dt>
<dd> Gets information about a player and their claimblocks </dd>
<dt> /claimlist <player> </dt>
<dd> List information about a player's claims. </dd>
<dt> /claiminfo </dt>
<dd> Gets information about a claim you are standing in or by claim id. </dd>
<dt> /adjustbonusclaimblocks <player> <amount> (/acb) </dt>
<dd> Adds or subtracts bonus claim blocks for a player
<dt> /setaccruedclaimblocks <player> <amount> (/scb) </dt>
<dd> Updates a player's accrued claim block total. </dd>
</dl>

## Notes:
when making an admin claim with holograms run these two commands to prevent despawning: <br>
**`/cf entity-spawn minecraft:armor_stand true`** <br>
**`/cf entity-chunk-spawn minecraft:armor_stand true`**

## Additional resources:
[Grief Prevention Wiki](https://github.com/MinecraftPortCentral/GriefPrevention/wiki/Commands#adjustbonusclaimblocks-player-amount-world)