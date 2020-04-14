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

Seed (občas překládáno jako semínko, dále se vyskytují pojmy recovery seed, recovery sentence, recovery phrase, seed phrase, mnemonic, mnemonic phrase) je list přesně po sobě jdoucích slov potřebného k obnovení krypto peněženky.

Seed se skládá z předem určených slov (2048 slov na základě návrhu BIP39), které dohromady dávají klíč celé peněženky. Z 24 slov (počet se může lišit) peněženka matematicky odvodí veškeré privátní i veřejné klíče ke všem účtům a adresám.

Tento zápis privátních klíčů je v současné době velmi používán, čemuž odpovídá i kompatibilita většiny peněženek.

Seed by neměl být nikdy sdílen s druhou osobou. Jeho kompromitace představuje kompromitaci veškerých privátních klíčů, veškerých adres, veškerých tokenů a veškerých dat spojených s peněženkou. Pro jeho ochranu se proto používají čím dál více hardwarové peněženky.

Příklad seedu:
> expect raccoon ethics mesh tag wife feed oxygen story rain rural uphold analyst month jacket obscure right invite chapter now saddle goddess round poet

* [List slov z BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt) (EN)
* [Nástroj na generování seedu](https://particl.github.io/bip39/) (EN)

---

### Privátní klíč

Privátní klíč je část šifrovacího klíče, jehož druhou částí je veřejný klíč. Odesilatel zašifruje zprávu svým privátním klíčem a odesilateli poskytne svůj veřejný klíč, pomocí nějž lze zprávu zpět dešifrovat.

Veřejným klíčem se rozumí adresa. Privátním klíčem pak její klíč. Uživatel veřejně poskytuje svoji adresu, své veřejné klíče, operace jsou však podepisovány jeho privátním klíčem.

Klíč je tvořen řadou znaků tvořených čísly a písmeny a jeho délka záleží na použítém šifrování.

Privátní klíč by neměl být nikdy sdílen s druhou osobou. Jeho kompromitace představuje kompromitaci veřejného klíče, adresy, veškerých tokenů a veškerých dat spojených s adresou.

Příklad privátního klíče:
> c6283e9d50f7f0f823adcd8f98d5115045b32dc2048567b9758454086e6f8685

* ["Kryptoměny: K čemu slouží privátní a veřejný klíč?" na Finex.cz](https://finex.cz/kryptomeny-privatni-verejne-klice/) (CZ)

---

### Web3

Viz ["Web3" v sekci Peněženky]({{< ref "/docs/eth-defi/ekosystem/penezenky" >}}).

---

### Wallet2wallet

Wallet2Wallet (přeložitelné jako peněženka do peněženky) je způsob směny tokenů bez použití směnárny. Veškerá data potřebná pro směnu se ukládají přímo na blockchainu a není tedy zapotřebí třetí strany.

Wallet2Wallet může také označovat směnu tokenů, která sice probíhá přes službu třetí strany (směnárnu, burzu), ale směna se odehrává přímo přes rozhraní peněženky. Není tedy potřeba tokeny přesouvat na burzu nebo směnárnu.

 [wallet2wallet.io](https://wallet2wallet.io/) (EN)

---

### Hardwarová peněženka

Hardwarová peněženka je zažízení, které uchovává privátní klíče separetně mimo počítač, izolovaně a offline. Po připojení k podporované softwarové aplikaci jsou načteny veřejné klíče, v případě že je potřeba použít privátních klíčů, je zpráva podepsána přímo uvnitř zařízení a aplikace dostane jen podepsanou zprávu. Privátní klíče tedy nikdy samotné zařízení neopustí.

Většina z těchto zařízení používá takzvanou hierarchical deterministic wallet (na základě jednoho privátního klíče vypočítá peněženka adresy pro více druhů krypto měn, dle BIP32), jako formát privátních klíčů se používá seed.

Hardwarové peněženky se stávají v současné době standardem, převážně z důvodu že se jedná o jednu z nejspolehlivějších a zároveň uživatelsky nejlehčích možností uchovávání privátních klíčů.

Záloha hardwarové peněženky (privátní klíče představované seedem) by neměla být nikdy sdílena s druhou osobou. Její kompromitace představuje kompromitaci veškerých privátních klíčů, veškerých adres, veškerých tokenů a veškerých dat spojených s peněženkou. Pro největší stupeň bezpečnosti je potřeba zálohovat privátní klíče mimo digitální podobu, a to na papír či na kovovou destičku.

##### Seznam hardwarových peněženek

Název | Dostupné modely |     | Popis
---   | ---             | --- | ---
<img src="https://trezor.io/static/images/favicon.ico" width="20" /> [Trezor](https://trezor.io/) | Trezor One, Trezor Model T | CZ | První hardwarová peněženka od SatoshiLabs
<img src="https://www.ledger.com/wp-content/themes/ledger-v2/public/images/ledger.svg" width="20" /> [Ledger](https://www.ledger.com/) | Ledger Nano X, Ledger Nano S | FR | Jeden z nejětších výrobců hardwarových peněženek
<img src="https://shapeshift.io/keepkey/images/logo.png" width="20" /> [KeepKey](https://shapeshift.io/keepkey/) | KeepKey Hardware Wallet Classic | UK | Produkt směnárny ShapeShift
<img src="https://opendime.com/static/images/opendime-logo-nav.png" width="20" /> [OpenDime](https://opendime.com/) | OpenDime | CA | Bitcoin hardware wallet
<img src="https://coldcardwallet.com/static/images/coldcard-logo-nav.png" width="20" /> [Coldcard](https://coldcardwallet.com/) | Coldcard Hardware Wallet | CA | Bitcoin hardware wallet
<img src="https://coolbitx.com/wp-content/uploads/2018/07/CoolBitX_logo-e1563866675472.png" width="20" /> [CoolWallet](https://www.coolwallet.io/) | CoolWallet S | TW | Hardwarová peněženka splečnosti CoolBitX
[BlochsTech](http://www.blochstech.com/) | Bitcoin smart card | DK | Bitcoinová karta
<img src="https://cdn.shopify.com/s/files/1/0969/7224/t/4/assets/logo.png" width="20" /> [BitLox](https://www.bitlox.com/) | BitLox | HK | Hardwarová peněženka
<img src="https://www.secalot.com/wp-content/uploads/2017/05/logo2.png" width="20" /> [Secalot](https://www.secalot.com/) | Secalot dongle | AT | Hardwarová peněženka
<img src="https://cdn.shopify.com/s/files/1/0031/5765/5641/files/ELLIPAL_720x720_cropped2_100x.png" width="20" /> [Ellipal](https://www.ellipal.com/) | ELLIPAL Titan | HK | Hardwarová peněženka
<img src="https://dcentwallet.com/images/logo.svg" width="20" /> [D'CENT](https://dcentwallet.com/) | D'CENT Hardware Wallet | KR | Hardwarová peněženka
<img src="https://cobo.com/_next/static/images/cobo-default-ab59980dea1054a52cf120568de303a9.png" width="20" /> [Cobo](https://cobo.com/) | Cobo | KY | Hardwarová peněženka

* [Hardware-wallets.io](https://hardware-wallets.io/) (EN)

---

## Použití

### Kde koupit Ether?

Možností jak a kde koupit Ether je v současné době nepřeberné množství.

#### Směna Etherea za jiné krypto

Nejjednoduší možností je směnit Ether za jiné krypto. To je možné přes centralizované i decentralizované služby, s nutností registrace ale i bez jakékoliv registrace, plně anonymně. Směna určitého tokenu za jiný může probíhat přes Wallet2Wallet a je podporována nepřeberným množstvím peněženek či webových aplikací.

#### Koupě Etherea přes burzu či směnárnu

Pro nákup Etherea za fiat je nejrozšířenější možností použítí směnárny či burzy. Ty ve většině případů vyžadují od svých zákazníků dodatečné identifikační údaje (jako je občanský průkaz, důkaz o trvalém bydlišti či výpis bankovního účtu) jež jsou zprocesovávány z legislativních důvodů (konkrétně se jedná o KYC - Know Your Customer, poznej svého zákazníka a AML - Anti Money Laundering, proti praní špinavých peněz).

Při výběru této možnosti je zapotřebí předem zjistit jaké dokumenty daná služba vyžaduje, jaké jsou poplatky za zprostředkování obchodu a za samotný výběr a jaký směný kurz daná služba nabízí.

* [Srovnání kurzů pro nákup a prodej](https://kurzy.gwei.cz/) (CZ)

#### Koupě Etherea přes kryptoměnové automaty

Další možností je nakoupit Ethereum přímo přes kryptoměnový automat. Většina těchto automatů nabízí pouze možnost prodeje bitcoinu, ale již existuje i celá řada automatů které nabízí alternativní kryptoměny, dokonce i s možností jejich zpětného výkupu. Tato možnost je plně anonymní, automaty mají však většinou horší kurzy než směnárny a vyšší poplatek za zprostředkování směny.

* [Seznam kryptoměnovýc automatů](https://coinatmradar.com/) (EN)
* [Seznam míst přijímajících krytptoměny včetně krytpoměnových automatů](https://coinmap.org/) (EN)

#### Koupě Etherea od druhého člověka

Jednou z nejlepších možností jak koupit Ether za fiat, bez nutnosti registrace, je přímo od prodávajícího člověka. Směnu je možno dohodnout na specializovaných diskuzních fórech. U této volby se kurz pohybuje smluvně a je velmi důležité dbát na bezpečnost během obchodu. Účastníci by měli zvolit k obchodu veřejně dostupné místo a dbát předchozích referencí.

* [Krypto Veksl - Facebook skupina pro nákup a prodej](https://www.facebook.com/groups/161651711267271/) (CZ)
* [LocalBitcoins](https://localbitcoins.com/) (EN)

---

### Jak používat decentralizované aplikace?

Prvním krokem k používání decentralizovaných aplikací je výběr vhodné peněženky. Pro Ethereum tokeny se hodí ukázkově třeba MetaMask, jež je kompatibilní s celou řadou populárních dApps.

Peněženka vygeneruje uživateli privátní klíče (například v podobě seedu)  - pro generování privátních klíčů a jejich následné uchovávání je vhodné používat hardwarovou peněženku. Z privátních klíčů jsou derivovány veřejné klíče, jež posléze vidí uživatel jako svoji adresu.

Tato adresa slouží k depozitu Etherea. Pro používání dApps je Ether nutný k tomu, aby platil poplatky za transakce, které v rámci dApps probíhají.

Posledním krokem je propojení peněženky s konkrétní decentralizovanou aplikací. Přihlášení většinou probíhá přímo přes rozhraní dané peněženky. V případě používání hardwarové peněženky je potřeba každou transakci v rámci dApps potvrdit přímo daným zařízením.

* [How to use your first Decentralized Application (Dapp)](https://cryptocurrencyhub.io/using-dapps-quick-manual-7384f0db7fe0) (EN)

---

### Bezpečnost a soukromí

Ethereum dovoluje uživatelům značnou část anonymity, ale i možnost svoji adresu veřejně identifikovat. Existují nástroje pro plnou anonymitu nebo token mixéry, které zamíchají tokeny tak, aby nebylo poznat z které adresy pochází.

Pro bezpečnost je nejdůležitější správné uchovávání privátních klíčů. Jejich ztráta či diskreditace vede ke ztrátě veškerých dat spojených s danou adresou.

Základní pravidla bezpečnosti:
* Privátní klíče musí být vždy zálohovány
* S privátníma klíčema je nejlépe pracovat offline, ideálně za pomoci hardwarové peněženky
* Privátní klíče s nikým nesdílet
* Uživatel by měl pro každou službu volit nové, před tím nepoužité heslo
* Pro přihlašování ke službě je dobré používat U2F

* ["Privacy" na EthHub](https://docs.ethhub.io/ethereum-roadmap/privacy/) (EN)

## Historie

Vitalik Buterin poprvé představil Ethereum veřejnosti v roce 2014 v Miami, USA na Bitcoin konferenci. Vývoj byl financován pomocí crowdfundingu na Bitcoinové síti, kdy prodej předtěžených tokenů v celkovém množství 60 milionů Etherů probíhal od 22. července 2014 do 2. září 2014 (42 dní). Během té doby se vybralo 31 000 BTC (v té době přibližně 18,3 milionu dolarů). První blok byl vytěžen 30. července 2015.

### Aktualizace Ethereové sítě (forky)

Název | Blok | Datum
---   | --- | ---
Frontier |	1 |	2015-07-30
Frontier Thawing |	200000 |	2015-09-07
Homestead	| 1150000	| 2016-03-14
DAO Fork	| 1920000	| 2016-07-20
Tangerine Whistle	| 2463000	| 2016-10-18
Spurious Dragon	| 2675000	| 2016-11-22
Byzantium	| 4370000	| 2017-10-16
Constantinople	| 7280000	| 2019-02-28
Istanbul	| 9069000	| 2019-12-06
Muir Glacier	| 9200000	| 2020-01-02

* ["History and Network Upgrades" na EthHub](https://docs.ethhub.io/ethereum-basics/history-and-forks/) (EN)
* ["Ethereum" na české Wikipedii](https://cs.wikipedia.org/wiki/Ethereum) (CZ)

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
