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

{{< todo >}}

* ["Ethereum 2.0 Phases" na EthHub](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth-2.0-phases/) (EN)


## Další zdroje

* [EthHub](https://ethhub.io/) (EN)
* [Ethereum.org](https://ethereum.org/cs/) (CZ)