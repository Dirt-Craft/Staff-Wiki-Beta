## Info Commands
<dl>
  <dt> /seen (username) </dt>
  <dd> Shows when user was last on and some other info. </dd>
  <dt> /realname (username) </dt>
  <dd> Reveals actual username. </dd>
  <dt> /ru check (username) </dt>
  <dd> Checks someones playtime. </dd>
  <dt> /note (username) (text) </dt>
  <dd> Sets a note, which can be checked and the staff will be notified of every time they join the server. </dd>
  <dt> /removenote (username) (text) </dt>
  <dd> Removes a specific note. </dd>
  <dt> /clearnotes (username) </dt>
  <dd> Removes all notes. </dd>
  <dt> /checknotes (username) </dt>
  <dd> Shows all notes. </dd>
</dl>

## Management Commands

### Teleportation
<dl>
  <dt> /tphere (username) </dt>
  <dd> Teleports someone to you. </dd>
  <dt> /tp (username) </dt>
  <dd> Teleports you to someone. </dd>
  <dt> /spawn other (name) </dt>
  <dd> Teleports someone to spawn. </dd>
</dl>

### Inventory & Experience
<dl>
  <dt> /invsee (username) </dt>
  <dd> Shows modifiable user inventory, even when offline. </dd>
  <dt> /inv view (username) </dt>
  <dd> Shows modifiable user inventory, even when offline. Also shows armour. </dd>
  <dt> /clear (username) </dt>
  <dd> Clears a users inventory. </dd>
  <dt> /exp give (username) (amount) </dt>
  <dd> Gives xp. Add an L to the number to add levels. </dd>
  <dt> /exp remove (username) (amount) </dt>
  <dd> Removes xp. Add an L to the number to remove levels. </dd>
  <dt> /exp set (username) (amount) </dt>
  <dd> Sets the experience to a certain value. use "l" to set it to levels. </dd>
  <dt> /exp set (username) </dt>
  <dd> Shows users experience. </dd>
</dl>

### Economy
Do not spawn in cash for yourself. This is highly frowned upon, Just spawn in items if you want something.
<dl>
  <dt> /eco add (username) (amount) </dt>
  <dd> Gives a player some cash. </dd>
  <dt> /eco remove (username) (amount) </dt>
  <dd> Removes some cash from a player. </dd>
  <dt> /eco set (username) (amount) </dt>
  <dd> Sets a players cash. </dd>
</dl>

### Advancements

#### PARAMS
- everything - all advancements
- from - a specific advancement and all of its child advancements
- only - just the id specified
- through - the specific id, all of its parent advancements, and all of its child advancements
- until - give specific advancement and all of its parent advancements <br>
IDS: https://minecraft.gamepedia.com/Advancements
<dl>
  <dt> /advancement grant (username) (param) (advancement id) </dt>
  <dd> Grants an advancement to a player. </dd>
  <dt> /advancement revoke (username) (param) (advancement id) </dt>
  <dd> Revokes an advancement from a player. </dd>
</dl>

### Other
<dl>
  <dt> /sudo (username) </dt>
  <dd> Forces the player to run a command. </dd>
</dl>

### Mod specific

#### Baubles
<dl>
  <dt> /baubles clear (username) </dt>
  <dd> Clears a players bauble inventory. </dd>
</dl>