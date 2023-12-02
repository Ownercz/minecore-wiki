# Ochrana pozemku

Jako první musíš napsat `/t create název_pozemku` například `/t create ostrava`.  
Nyní máš název pozemku a potřebuješ k němu nastavit samotnou oblast. 

Oblast nastavíš příkazem `/t claim`, to ti claimne oblast 16x16 (1 chunk) kde zrovna stojíš.  
Počet chunků, které můžeš mít u svého pozemku, je maximálně 16. Tedy můžeš zastavět oblast 256x256.

Odebrat kus pozemku můžeš pomocí `/t unclaim`.

### Přidání kamaráda
Nejdřív jdi na svůj pozemek. Kamaráda přidáš příkazem `/t add NICK` , například `/t add Davo` přidá kamaráda s nickem Davo do tvého pozemku. 

Kamarád pak přijme tvé pozvání `/accept`

Odebrání můžeš udělat poté příkazem: `/t kick NICK`

### Přejmenování pozemku
Stůj ve svém pozemku, který chceš přejmenovat, následně napiš `/t set name Brno`. To nastaví jméno tvého pozemku na Brno.

## Kde všude mám pozemek?
Mapu pozemku si můžeš zobrazit pomocí příkazu `/towny map`
Můžeš si taky zapnout/vypnout zobrazení okrajů chunku, díky kterým uvidíš, kde přesně ti končí pozemek příkazem `/res toggle plotborder`.

Zelené = tvůj pozemek, šedé = ničí pozemek, červené = cizí/pvp.

### Admin cmds
/townyadmin town ghasty_test spawn - teleport na ghasty_test town



towny map big
towny map hud


/tw list














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
