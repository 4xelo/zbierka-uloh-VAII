# Zbierka úloh pre VAII
Tento repozitár je zbierka úloh pre študentov predmetu VAII 
[Fakulty riadenia a informatiky (FRI)](https://www.fri.uniza.sk/). Obsahuje úlohy zo zadaním,
postupom riešenia a samotné výsledné riešenie (úloha može mať, samozrejme viacero správnych 
riešení).

Repozitár obsahuje dva branche:
- _master_ - obsahuje funkčné riešenie úloh
- _starter_ - obsahuje počiatočnú štruktúru súborov danej úlohy

# Docker
V súčasnosti jeden z najpoužívanejších spôsobov virtualizácie, ktorá výrazne zjednošuje vývoj a nasadzovanie rôznych 
aplikácií. Umožňuje veľmi pohodlne nakonfigurovať a zostaviť služby ako lokálne tak aj na serveroch. Umožnuje vytvoriť
jednotné a stabilné prostredie.

Niektoré naše úlohy vyžadujú pre ich vypracovanie webový server s PHP a relačnú databázu. Pre odľahčenie a odstránenie
nutnosti všetko konfigurovať pripájame, ku každej úlohe, ktorá to vyžaduje súbor `docker-compose.yml`. Tento súbor
obsahuje potrebnú nami vytvorenú konfiguráciu, tak aby ste nestrácali zbytočne čas konfiguráciou a inštaláciou
potrebných služieb.

Pre použitie Dockera na lokálnom PC sa používa aplikácia _Docker Desktop_, ktorá je dostupná pre _Linux_, _Windows_ a _MacOS_.
Pár poznámok k jej stiahnutiu:

1.  Ak máte _OS Windows_, potrebuje vyššiu verziu ako je _Home_. Licenciu pre vyššiu verziu ma každý študent zdarma k 
    dispozícií, nakoľko je FRI zaradená do licenčného programu Microsoft Azure DevTools For Teaching. Viac informácií nájdete
    [na oficiálnych stránkach fakulty](https://www.fri.uniza.sk/stranka/softver-a-internet).
2.  Je potrebné vytvorenie konta pre [Docker](https://www.docker.com/)
3.  Až po jeho vytvorení je možné používať aplikáciu [Docker Desktop](https://www.docker.com/products/docker-desktop)
4.  Túto inštaláciu zvládne každý informatik, každopádne pre prípad núdze skúste [oficiálnu dokumentáciu](https://docs.docker.com/desktop/).

Samozrejme, pre spustenie potrebných služieb môžete použiť lubovoľným spôsob.

# Zoznam úloh

Úlohy sú rozdelené podľa toho, ktorú technológiu použivaju a obsahuju označenie nátočnosti (stupnica
od 1 po 5, kde 5 je najväčšia náročnosť)

## CSS

1. [ShowHide](showhide/readme.md) (JS, CSS) - obtiažnosť 1
1. [Tooltip](tooltip-js/README.md) (CSS) - obtiažnosť 2
1. [Tooltip](tooltip-js/README.md) (JS, CSS) - obtiažnosť 2




