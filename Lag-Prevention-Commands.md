## LaggyChunks Commands

<dl>
  <dt> /LC E </dt>
  <dd> Shows chunks in your current world with the highest entity count. </dd>
  <dt> /LC T </dt>
  <dd> Shows chunks in your current world with the highest tile entity count. </dd>
</dl>

## Remove Entities Commands
All players should be given notice before these commands are used
<dl>
  <dt> /RE -h </dt>
  <dd> Removes all hostile entities. </dt>
  <dt> /RE -i </dt>
  <dd> Removes all dropped items. </dt>
  <dt> /RE -x </dt>
  <dd> Removes all experience orbs. </dt>
  <dt> /RE -b </dt>
  <dd> Removes all bosses. </dt>
</dl>

## Lag Profiling

<dl>
  <dt> /gc </dt>
  <dd> Shows extremely basic server info. </dd>
  <dt> /Profile E (Time in Seconds) </dt>
  <dd> Profiles the server for laggy entities. Default 30 seconds. </dd>
  <dt> /Spark Start --only-ticks-over 400 </dt>
  <dd> Starts a Spark Profiler on the server. </dd>
  <dt> /Spark Stop </dt>
  <dd> Ends the Spark Profiler and provides a link to the results. </dd>
</dl>

## Other Lag Prevention Commands

<dl>
  <dt> /UnloadChunks </dd>
  <dd> Alias: /UC <br> Unloads all chunks. </dd>
  <dt> /clwhitelist</dd>
  <dd> Add an item to the clearlag item whitelist </dd>