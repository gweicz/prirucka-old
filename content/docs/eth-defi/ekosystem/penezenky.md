---
title: Peněženky
url: /defi/penezenky
weight: 10
---

# Peněženky

## Základní srovnání

* [**Smart-contract peněženky**](#smart-contract-peněženky) - peněženky nové generace, držení prostředků a veškerá aktivita se děje v rámci [chytrého kontraktu]({{< ref "/prirucka#chytrý-kontrakt-smart-contract" >}}) a vy jen ovládáte tento kontrakt lokálním klíčem na svém zařízení, který má k tomuto kontraktu přístupová práva
   * :white_check_mark: pro většinu lidí bezpečnější a výrazně jednodušší (není potřeba operovat se [*seedem*]({{< ref "/prirucka#seed" >}}))
   * :white_check_mark: možnost zvýšit bezpečnost pomocí HW peněženky či dalších lidi / zařízení
   * :white_check_mark: flexibilita - možnost nastavit časové nebo objemové limity, možnost peněženku uzamknout či delegovat práva někomu jinému
   * :x: další vrstva, která může být napadnutelné - např. zranitelnost smart-kontraktu
   * :x: dobré využívat jen ty peněženky, které mají řádné audity a jsou prověřené (zde uvádíme ty nejpoužívanější a nejbezpečnější)


* **Klasické peněženky** - všechny ostatní peněženky, kde plně ovládáte [*privátní klíč*]({{< ref "/prirucka#privátní-klíč" >}})
   * :white_check_mark: ten kdo ovládá peněženku má plnou kontrolu nad danou adresou bez omezení
   * :white_check_mark: bezpečnější, pokud máte plán na všechny situace které můžou nastat - úmrtí, ztráta seedu, prozrazení seedu atp.
   * :x: obtížné na používání - uživatel musí vědět co dělá
   * :x: riziko ztráty privatního klíče nebo seedu
   * :x: neflexibilní


## Rozhraní

### Web3
Standartizované rozhraní pro interakci Ethereum peněženky a webové stránky. Toto rozhraní umožňuje vývojářům dělat webové služby, pomocí kterých uživatelé mohou komunikovat s chytrými kontrakty dané decentralizované aplikace. Na desktopu jsou tyto peněženky většinou ve formě doplňku do prohlížeče - na mobilních zařízeních naopak prohlížeč integrují uvnitř aplikace. Zdaleka nejpoužívanější Web3 peněženkou je [MetaMask](#metamask).

### WalletConnect
Umožňuje ovládání peněženky a odesílání transakcí z jiné aplikace - např. pomocí mobilní peněženky se přihlásíte v prohlížeci do dApp - každá transakce kterou uděláte bude vyžadovat potvrzení v mobilní peněžence

- Web: [walletconnect.org](https://walletconnect.org/)


## Smart-contract peněženky

### Argent

Mobilní peněženka k jejíž obnově nepotřebujete seed, lze ji obnovit pomocí tzv. Guardians, což mohou být např. přátelé a rodina nebo dokonce i HW peněženka. Argent zároveň za vás při posílání transakcí zaplatí tzv. [Gas]({{< ref "/prirucka#gas" >}}) (poplatek za transakci) a umožňuje směnu tokenů.

Ideální peněženka pro začátečníky.

- Web: [argent.xyz](https://www.argent.xyz/)
- Platformy: Android, iOS
- Kompatibilní hardwarová peněženka: Trezor, Ledger
- Web3: :x: / WalletConnect: :white_check_mark:

<a href="https://www.argent.xyz/"><img src="/img/eth-defi/argent.png" width="500" /></a>

---

### Gnosis Safe

Pravděpodobně nejbezpečnější smart-contract wallet pro náročnější použití - používá ji mnoho Ethereum projektů na ochranu admin přístupu ke svým aplikacím.

- Web: [gnosis-safe.io](https://gnosis-safe.io/)
- Platformy: Web, Android, iOS
- Kompatibilní hardwarová peněženka: Trezor & Ledger (via MetaMask)
- Web3: :x: / WalletConnect: :white_check_mark:

<a href="https://gnosis-safe.io/"><img src="/img/eth-defi/gnosis-safe.png" width="500" /></a>

---


### Monolith

Smart-contract wallet propojená s platební kartou a v budoucnu i bankovním účtem. Umožňuje snadné nabití Monolith platební karty (vedené EUR / GBP) pomocí ETH či ERC-20 tokenu a placení a utrácení kdekoliv kde přijímají Visa.

- Web: [monolith.xyz](https://monolith.xyz/)
- Platformy: Android, iOS
- Web3: :x: / WalletConnect: :x: (připravuje se)

<a href="https://monolith.xyz/"><img src="/img/eth-defi/monolith.png" width="500" /></a>

---

## Multi-platformní peněženky

### MetaMask

Peněženka podporována drtivou většinou decentralizovaných aplikací (DApps). Nabízí doplněk do prohlížeče (Chrome, Firefox), vás autorizuje do určité DAppky. Lze přepínat mezi hlavní Ethereum sití a testovacími. Nabízí i mobilní aplikaci, které obsahuje Web3 browser.

- Web: [metamask.io](https://metamask.io/)
- Platformy: Prohlížeč (Chrome, Firefox, Brave), Android, iOS
- Kompatibilní hardwarová peněženka: Ledger, Trezor
- Web3: :white_check_mark: / WalletConnect: :x:

<a href="https://metamask.io/"><img src="/img/eth-defi/metamask.png" width="500" /></a>

---

### Coinomi

Jednoduchá peněženka podporující kromě Etheru a ERC-20 i téměř všechny další kryptoměny. 

- Web: [coinomi.com](https://www.coinomi.com/)
- Platformy: Windows, macOS, Linux, Android, iOS
- Kompatibilní hardwarová peněženka: Ledger, Trezor
- Web3: :white_check_mark: / WalletConnect: :white_check_mark:

<a href="https://www.coinomi.com/"><img src="/img/eth-defi/coinomi.png" width="500" /></a>

---

## Mobilní peněženky

### Trust Wallet

Klasická multi-kryptoměnová mobilní peněženka s integrovaným Web3 prohlížečem a pokročilými funkcemi. Jedná se o oficiální peněženku burzy [Binance](https://www.binance.com/en).

- Web: [trustwallet.com](https://trustwallet.com/)
- Platformy: Android, iOS
- Kompatibilní hardwarová peněženka: není
- Web3: :white_check_mark: / WalletConnect: :white_check_mark:

<a href="https://trustwallet.com/"><img src="/img/eth-defi/trustwallet.png" width="500" /></a>

---

### Status

Status je end-to-end šifrovaný messenger, peněženka a Web3 browser v jednom.

- Web: [status.im](https://status.im/)
- Platformy: Android, iOS
- Kompatibilní hardwarová peněženka: není
- Web3: :white_check_mark: / WalletConnect: :x:

<a href="https://status.im/"><img src="/img/eth-defi/status.png" width="500" /></a>

---

## Webové peněženky

Peněženky přístupné jen z webového prohlížeče bez jakkékoliv instalace.

### MyEtherWallet

Pokročilejší Ethereová peněženka, která dovolí zvolit si vlastní derivation path. Je možné ji použít pro kteroukoliv Ethereum-založenou síť (např. Kovan, Ethereum Classic). Vhodná na používání nestandardních derivation path. Umožňuje směnu tokenů.

- Web: [www.myetherwallet.com](https://www.myetherwallet.com/)
- Kompatibilní hardwarová peněženka: Trezor, Ledger, KeepKey, FINNEY, BitBox, XWallet, Secalot
- Web3: :white_check_mark: / WalletConnect: :x:

<a href="https://www.myetherwallet.com/"><img src="/img/eth-defi/mew.png" width="500" /></a>

---

### MyCrypto

Pokročilejší Ethereová peněženka, obdoba MyEtherWallet. Také dovolí zvolit si vlastní derivation path a je možné ji použít pro kteroukoliv Ethereum-založenou síť (např. Kovan, Ethereum Classic). Pro změnu sítí v rámci jedné derivation path (vhodné pro claimováni forknutých tokenů či hledání tokenů odeslaných na nesprávnou síť) je snadno použitelná. Umožňuje směnu tokenů.

- Web: [mycrypto.com](https://mycrypto.com/)
- Kompatibilní hardwarová peněženka: Trezor, Ledger, Safe-T mini
- Web3: :white_check_mark: / WalletConnect: :white_check_mark:

<a href="https://mycrypto.com/"><img src="/img/eth-defi/mycrypto.png" width="500" /></a>


