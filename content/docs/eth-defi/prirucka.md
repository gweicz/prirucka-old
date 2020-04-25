---
title: Příručka pro začátečníky
weight: 1
url: /prirucka
---

# Ethereum & DeFi pro začátečníky

## Co je Ethereum?

*Ethereum* je celosvětová platforma pro decentralizované aplikace na bázi open-source softwaru.

Na platformě Ethereum můžete psát kód, který spravuje digitální hodnoty, běží přesně tak, jak je naprogramovaný, a je dostupný kdekoli na světě.

* ["Co je Ethereum" na Ethereum.org](https://ethereum.org/cs/what-is-ethereum/) (CZ)
* ["What is Ethereum" na EthHub](https://docs.ethhub.io/ethereum-basics/what-is-ethereum/) (EN)
* ["Ethereum" na české Wikipedii](https://cs.wikipedia.org/wiki/Ethereum) (CZ)

## Co jsou to decentralizované finance (*DeFi*)?

*"DeFi"* je zkratka anglického výrazu *"Decentralized Finance"*, tedy v překladu *"Decentralizované finance"* (nebo také *"Otevřené finance"*). Jde o hnutí, které chce pomocí decentralizace a chytrých kontraktů proměnit staré finanční produkty v transparetní a trustless (nevyžadující důvěru) protokoly, které spolu budou komunikovat bez prostředníků. 

Jinak řečeno - cílem DeFi je vytvářet produkty, které běžně známe z tradičních finančních světů – možnost například půjčit si peníze nebo naopak půjčit někomu peníze, investovat, apod. Jediný rozdíl však je, že vše se vytváří na blockchainu – není tedy třeba tradičních postupů a nástrojů, jako bank, burz, apod. ale naopak – vše běží za pomocí smart kontraktů a interakce s nimi.

* ["DeFi: Finanční systém 2.0" na Alza.cz](https://www.alza.cz/defi-financni-system-2-0) (CZ)
* ["The Definitive Guide to DeFi" na Exodus.io](https://www.exodus.io/blog/what-is-defi/) (EN)
* [DeFi.network](https://defi.network/) (EN)

## Základní pojmy

### Ether (ETH)

Ether (ETH nebo Ξ) je nativní kryptoměna používaná v síti Ethereum a slouží k odměňování těžarů (minerů), kteří zabezpečují transakce. V nejbližší době se plánuje aktualizace protokolu, tak že se výpočetně náročná tězba nahradí méné náročnou pomocí mechanismu *Proof of Stake* (*"důkaz o držení"*) a každý ověřovatel, který bude držet Ether a zabezpečovat síť bude získávat poměrnou odměnu v Ethereu.

Ether má ale i další použítí, jako je například ukládání hodnoty (např. Při půjčování kolaterálu), směnné médium (např. V obchodu a platbách) a účetní jednotka (např. Na digitálních trzích).

* ["What is Ether" na EthHub](https://docs.ethhub.io/ethereum-basics/what-is-ether/) (EN)
* ["Monetary Policy" na EthHub](https://docs.ethhub.io/ethereum-basics/monetary-policy/) (EN)
* [Gwei.io](https://gwei.io/) (EN)

---

### Gas

Gas je jednotka, která vyjadřuje určité množství výpočetního výkonu. V Ethereum síti je používán k definování množství výpočetního výkonu a úložného prostoru, který je potřeba ke zpracování a uložení transakce na blockchain. Nejmenší jednotkou je 1 GWEI, což je jedna miliardtina etherea (1*10^-9).

Cenu gas(u) určuje odesílatel transakce. Čím víc je ochoten odesílatel transakce nabídnout těžařům za zpracování transakce, tím rychleji se transakce provede, protože těžaři jsou motivováni odměnou, kterou dostanou za gas.

Pro příklad, transakce, při které přesouváte pouze ethery a nespouští se žádný chytrý kontrakt, spotřebuje 21000 Gasu. Pokud nabídnete těžařům 4 GWEI/gas, celkový poplatek za tuto transakci bude 84000 GWEI (0.000084 ETH).

##### Gas jednotky

| Jednotka |     Množství na 1 ETH     |
| :------: | :-----------------------: |
|   ETH    |             1             |
|  Finney  |           1,000           |
|  Szabo   |         1,000,000         |
|   Gwei   |       1,000,000,000       |
|   Mwei   |     1,000,000,000,000     |
|   Kwei   |   1,000,000,000,000,000   |
|   Wei    | 1,000,000,000,000,000,000 |

* [ETHGas.io](https://ethgas.io/) (EN)
* [Aktuální ceny gasu](https://www.ethgasstation.info/) (EN)

---

### Chytrý kontrakt (*Smart contract*)

Zatímco slovo *„kontrakt“* evokuje právní dohodu; v Ethereu jsou *„chytré kontrakty“* jen kousky kódu, které běží na blockchainu a je zaručeno, že budou produkovat stejný výsledek pro všechny, kdo je provozují. Lze je použít k vytvoření široké škály decentralizovaných aplikací (tzv. *dApps*), které mohou zahrnovat hry, digitální sběratelské předměty, online hlasovací systémy, finanční produkty a mnoho dalších.

* ["Chytrý kontrakt" na české Wikipedii](https://cs.wikipedia.org/wiki/Chytr%C3%BD_kontrakt) (CZ)

---

### Decentralizovaná aplikace (*dApp*)

Aplikace, které využívají pro převod hodnoty či své fungování chytré kontrakty.

---

### ERC-20 (token)

ERC-20 je standard chytrého kontraktu pro tokeny v síti Ethereum, který usnadňuje práci vývojářům decentralizovaných aplikací.

* ["Co jsou ERC20 tokeny?" na CryptoSvět](https://cryptosvet.cz/co-jsou-erc20-tokeny/) (CZ)

---

### Povolení (*Token allowance*)

Každý ERC-20 token má zabudovanou ochranu - manipulovat s ním může jen taková decentralizovaná aplikace, které to dovolíte.

* [TokenAllowancce.io](https://tokenallowance.io/) (EN)

---

### Seed

{{< todo >}}

---

### Privátní klíč

{{< todo >}}

---

### Web3

Viz ["Web3" v sekci Peněženky]({{< ref "/docs/eth-defi/ekosystem/penezenky" >}}).

---

### Wallet2wallet

{{< todo >}}

---

### Hardwarová peněženka

{{< todo >}}

* [Hardware-wallets.io](https://hardware-wallets.io/) (EN)


## Použití

### Kde koupit Ether?

{{< todo >}}

---

### Jak používat decentralizované aplikace?

{{< todo >}}

---

### Bezpečnost a soukromí

{{< todo >}}

* ["Privacy" na EthHub](https://docs.ethhub.io/ethereum-roadmap/privacy/) (EN)

## Historie

{{< todo >}}

* ["History and Network Upgrades" na EthHub](https://docs.ethhub.io/ethereum-basics/history-and-forks/) (EN)

## Budoucnost

### Vývoj Etherea

{{< todo >}}

---

### ETH2.0 & Proof of Stake

Ethereum 2.0, Serenity nebo také jenom Eth2 jsou všechno názvy pro velký síťový update, který sebou přinese technologické upgrady ve formě Shardingu, Proof of Stake nebo nového virtuálního stroje (eWASM). Je důležité zmínit, že všechny tyto technologické upgrady se neodehrají v jeden okamžik - místo toho budou postupně implementovány. Níže jsou popsány jednotlivé fáze, které budou postupně přinášet ony zmíněné technologické upgrady.



#### ETH2.0

##### Fáze 0 - Beacon Chain

Hlavním technologickou změnou, která přijde ve fázi 0 je tzv. Beacon Chain. Beacon Chain bude mít jako hlavní úkol spravovat Proof of Stake protokol a všechny shard chainy. Do těchto dvou úkolů lze zahrnout např.:

- spravování validátorů v síti a jejich vklady
- nominace vybraného navrhovatele pro každý shard v každém kroku
- organizování validátorů do výborů, aby hlasovali o navrhovaných blocích
- uplatňování pravidel konsensu
- uplatňování odměn a sankcí na validátory
- být hlavním bodem, pomocí kterého budou shardy zaznamenávat svůj stav a zároveň, aby byli umožněny transakce mezi jednotlivými shardy

V momentě, kdy bude Fáze 0 dokončena budou aktivní 2 Ethereum chainy. Pro ujasnění je budeme nazývat jako Eth1 chain (aktuální, PoW chain) a Eth2 chain (nový Beacon Chain). Během této Fáze 0 budou moci uživatelé přesunou své ethery z Eth1 chainu do nového Eth2 chainu a stát se tak validátory. Tento přesun je už nevratný, takže pokud přesunete své ethery do Eth2 chainu, nepůjde je už přesunout zpět. 

Důvod proč někdo může chtít přesunout své ethery je ten, že se může stát validátorem transakcí a získávat tak úroky ze svého vkladu. Minimální množství, které uživatel musí přesunou do Eth2 chainu je 32 ETH. Behěm doby, kdy bude Fáze 0 aktivní se budou všechny uživatelské transakce a smart kontrakty vykonávat stále na Eth1 chainu.



##### Fáze 1 - Shard Chainy

Shard chainy jsou hlavním prostředkem ke zvýšení škálovatelnosti celé sítě a v této fázi jich bude konkrétně nasazeno 64. Hlavní výhodou shard chainů je schopnost paralelně zpracovávat transakce. V praxi to znamená, že síť bude schopna zpracovat více transakcí za sekundu.

Hlavním problémem škálovatelnosti, se kterým se nynější blockchainy, včetně Etherea, potýkají, je: že každý node (uzel) v síti musí ověřit a provést každou transakci. Rozdíl v Eth2 bude v tom, že vámi odeslaná transakce se zpracuje a potvrdí validátory pouze na jednom shard chainu a ostatní shard chainy se o ní dozví pomocí tzv. crosslinků (crosslink představuje odkaz na nějaký blok v jiném shard chainu).

{{< screen "/eth-defi/beaconchain-shards.png" "https://ethos.dev/beacon-chain/" >}}

Ve Fázi 0, 1 a 2 bude stále hlavní PoW chain (Eth1) aktivní zatímco bude probíhat testování a přechod na Eth2 chain. To znamená, že se budou odměny vyplácet jak validátorům na Eth2, tak na PoW chainu.



##### Fáze 2 - Uvedení do pohybu

Fáze 2 je bodem, ve kterém se začne spojovat funkčnost celého systému. Shard chainy se přemění z jednoduchých datových zásobníků do stavu, kdy budou schopny zpracovávat smart konktrakty pomocí virtuálních strojů. Decentralizované aplikace si budou muset vybrat shard chain, na kterém poběží, protože komunikace mezi shard chainy nebude synchronní.



#### Proof of Stake

Proof of Stake je druh konsensus algoritmu, ve kterém validátoři hlasují o dalším bloku, který má být přidaný do blockchainu. Váha jejich hlasu závisí na velikosti vkladu. Na Proof of Stake je pohlíženo jako na vylepšení Proof of Work (PoW), protože jeho používání nevyžaduje takovou spotřebu elektřiny a zároveň je například také lépe zabezpečen vůči různým typům 51% útoků.

Chcete-li se účastnit hlasování (tj. stát se validátorem) potřebujete nashromáždit určitý počet etherů. Takto nashromážděné ethery se vám posléze úročí a zároveň dostáváte poplatky z transakcí, které jste ověřili.



* ["Ethereum 2.0 Phases" na EthHub](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth-2.0-phases/) (EN)
* ["The Beacoin Chain Explainer na Ethos.dev"](https://ethos.dev/beacon-chain/) (EN)
* ["Proof of Stake (PoS) na EthHub"](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/proof-of-stake/) (EN)

## Další zdroje

* [EthHub](https://ethhub.io/) (EN)
* [Ethereum.org](https://ethereum.org/cs/) (CZ)
