# References
\* = priority \
() = notes/comments \
<> = required arguement \
[] = optional arguement 
# System

## Bot Internals

- [x] Make the Bot Run\*
- [x] Logging
- [ ] Command Handler\*
- [ ] Database\*
- [ ] Sharding (required at 2500, should be started at 1000 servers.)
- [ ] Web Dashboard

## Management

- [ ] Reaction Roles
- [ ] Lockdown System\*
- [ ] Level System
- [ ] Profile System
- [ ] User Blocking

# Commands

## Owner

- [ ] eval \<securecode> \<input>\*
- [ ] shutdown <securecode> \*
- [ ] say <text>
- [ ] announce <securecode> <text>
- [ ] rules\*
- [ ] rule\* <rule number>
- [ ] verifRules\*
- [ ] wipedata <securecode> <server/user id>\*
- [ ] togglepremium <securecode> [server-id] <time>\*
- [ ] reload [category] (if not it reloads everything) (better for updating the bot without having to do a full restart) 
- [ ] reloadplugin <plugin>

## Administration

- [ ] setannouncechannel <channel-id/channel-mention>
- [ ] reactionrole <create/edit/resend/delete/add/pause>
- [ ] slowmode <slowmode-time>\*
- [ ] lockdown [message]\*
- [ ] lock <channel-id/channel-mention> [message]\*
- [ ] unlock <channel-id/channel-mention> [message]\*
- [ ] lockdownchannel <add/remove> <channel-id/channel-mention>\*

## Moderation

- [ ] warn <user> <reason>\*
- [ ] deletewarn <user> <warnid>\*
- [ ] mute <user> <time> <reason>\*
- [ ] unmute <user> <reason>\*
- [ ] ban <user> <reason>\*
- [ ] tempban <user> <time> <reason>\*
- [ ] kick <user> <reason>\*

## Levels

- [ ] rank [user]
- [ ] addxp <user> <xp>
- [ ] removexp <user> <xp>
- [ ] setlevel <user> <level>
- [ ] resetuser <user>
- [ ] pausexp

## Profile Settings

- [ ] setbio \<input>
- [ ] setpronouns \<input>
- [ ] setgender \<input>
- [ ] setsexuality \<input>
- [ ] setplatforms <PC/Mobile/XBOX/Playstation/Nintendo Switch>

## Roleplay

- [ ] preferences <command> [on/off]
- [ ] hug <user>
- [ ] kiss <user>
- [ ] cuddle <user>
- [ ] boop <user>
- [ ] bonk <user>
- [ ] highfive <user>
- [ ] nuzzle <user>
- [ ] pounce <user>
- [ ] lick <user>
- [ ] pet <user>
- [ ] nom <user>
- [ ] bite <user>
- [ ] slap <user>
- [ ] kill <user>

## Fun

- [ ] ship <user1> <user2>
- [ ] animal [animal-name]
- [ ] joke
- [ ] rps <rock/paper/scissors>
- [ ] pokemon <pokemon-name>
- [ ] meme
- [ ] randomcolour
- [ ] 8ball <question>
- [ ] choose <entry1>, <entry2>, [entry3], [entry4], [entry5], [entry6]
- [ ] dice [4/6/8/10/12/20]
- [ ] coinflip

## Misc
  
- [ ] avatar [user] 
- [ ] banner [user] 
- [ ] botinfo (will not include hardware information)
- [ ] distance <city1/coord1>, <city2/coord2> 
- [ ] iss
- [ ] timezone
- [ ] dictionary <word>
- [ ] erasedata (doesn't erase warns)
- [ ] serverinfo
- [ ] uptime
