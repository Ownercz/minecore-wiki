# Ochrana pozemku

Jako první musíš napsat `/t create název_pozemku` například `/t create ostrava`.  
Nyní máš název pozemku a potřebuješ k němu nastavit samotnou oblast. 

Oblast nastavíš příkazem `/t claim`, to ti claimne oblast 16x16 (1 chunk) kde zrovna stojíš.  
Počet chunků, které můžeš mít u svého pozemku, je maximálně 16. Tedy můžeš zastavět oblast 256x256.

Odebrat kus pozemku můžeš pomocí `/t unclaim`.
Odebrat kompletně pozemek můžeš pomocí `/t delete`.

### Přidání kamaráda
Nejdřív jdi na svůj pozemek. Kamaráda přidáš příkazem `/t add NICK` , například `/t add Davo` přidá kamaráda s nickem Davo do tvého pozemku. 

Kamarád pak přijme tvé pozvání `/accept`

Odebrání můžeš udělat poté příkazem: `/t kick NICK`

### Přejmenování pozemku
Stůj ve svém pozemku, který chceš přejmenovat, následně napiš `/t set name Brno`. To nastaví jméno tvého pozemku na Brno.

## Kde všude mám pozemek?
Mapu pozemku si můžeš zobrazit pomocí příkazu `/towny map`.
Můžeš si taky zapnout/vypnout zobrazení okrajů chunku, díky kterým uvidíš, kde přesně ti končí pozemek příkazem `/res toggle constantplotborder`.

Neustálé vypisování mapy do chatu můžeš zapnout/vypnout `/res toggle map`.

Zelené = tvůj pozemek, šedé = ničí pozemek, červené = cizí/pvp.

## Seznam pozemků
/t list - klikneš a můžeš se portnout

## uvítací zpráva
/t set board
/t set board none - smazat

### Admin cmds
/townyadmin town ghasty_test spawn - teleport na ghasty_test town
/townyadmin unclaim - unclaim pozemku


towny map big
towny map hud


/tw list


# Long towny list
- https://wiki.ccnetmc.com/Guides/TownyCommands

```
/townyadmin
/townyadmin
Shows Memory, Threads, War status, Health regen setting, Time, Whether daily-timer/taxes are on.
? - Shows /ta commands.
delete {playername} - Deletes a player's towny data.
town {town}
add {resident} .. {resident} - Admin command to invite/add a resident to a town.
remove {resident} .. {resident} - Admin command to remove a resident from a town.
kick {resident} - Admin command to remove a resident from a town.
rename {newname} - Admin command to rename a town.
pawn - Admin command to spawn at at town spawn.
utpost # - Admin command to spawn at any towns outposts.
delete - Admin command to delete a town.
nation
{nationname} add {town} - Admin command to invite/add a town to a nation.
{nationname} rename {newname} - Admin command to rename a nation.
{nationname} delete - Admin command to delete a town.
reset - resets the towny config.yml to its current default.
toggle
war - Turn on/off towny war.
neutral - Turn on/off a nation's ability to declare neutrality.
npc {residentname} - Toggles a player's resident file to isNPC=true, this exempts the player from taxes/upkeep.
debug - Turns on/off debug mode.
devmode - Turns on/off special devmode for when towny's devs join your server to find a bug.
withdraw - Turns on/off town/nation's ability to withdraw money from their town/nation banks.
set
capital {townname} - A command for admins to be able to change a nations capital. Town to be set must already be a member of the nation.
mayor
{town} {resident} - Admin command to set a resident as mayor of a town.
{town} npc - Admin command to set a town to have an npc mayor.
givebonus {town} {#} - Gives extra townblocks to a town.
reload - Reloads towny's config.yml.
backup - Creates a backup.
newday - Causes a new day to happen, this does not stop the next new day from happening when it was already scheduled.
unclaim
rect {radius} - Admin command to unclaim an area.
purge {# as in days} - Deletes old residents.
```






# Tradování s villagery
  - Funguje jako v klasickém MC s tou výjimkou, že villagera není možné vystrašit nebo jiným způsobem přesvědčit, aby vám dal slevy.
  - Máme to takto nastaveno, protože chceme udržet vybalancovanou hru, která vás bude bavit.

#  ChestSort
  **Jedná se o VIP výhodu (essentials,silver,gold)!**
  - Tato výhoda vám umožní pár klinutím:
  - Uspořádat si svůj inventář
  - Uspořádat jakoukoliv bednu nebo barel
  - Vzít si vše z inv do bedny a zpět

  **Zkratky na uspořádání inv a beden:**
  - Dvojté levé kliknutí (do prázdného místa v inv)
  - Shift + levé kliknutí (do prázdného místa v inv)
  - Shift + pravé kliknutí (do prázdného místa v inv)

  **Zkratky pro přemístění věcí:**
  - Z inventáře do bedny
  - Dvojté levé kliknutí (mimo inventář)
  - Z bedny do inventáře
  - Dvojté pravé kliknutí (mimo inventář)
  - Zapnutí vypnutí zkratek - /chestsort

# Shopy
**Vytvoření shopu**
  - Polož bednu, ve které chceš mít obchod.
  - Drž v ruce item, se kterým chceš obchodovat. 
  - Napiš /shop create **(počet itemů)** **(výkupní cena)** **(prodejní cena)** 
  - Například /shop create 1 10 20
  - Tedy budu **vykupovat** 1 kus za **10** a **prodávat** ho budu za 20. #profit
  - Klepni na bednu, ve které chceš mít obchod.

**Odebrání shopu**
- /shop remove a fláknout bednu

#  Jobs
- Stačí napsat **/jobs** a vše se ti vypíše do chatu.
