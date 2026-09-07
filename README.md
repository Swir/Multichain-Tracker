<div align="center">

# ⛓️ Multichain Tracker

**CLI wallet tracker for multiple EVM networks by Swir**  
**Konsolowy tracker portfela dla wielu sieci EVM autorstwa Swir**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Ethereum](https://img.shields.io/badge/Network-Ethereum-627EEA?logo=ethereum)
![BNB](https://img.shields.io/badge/Network-BNB%20Chain-F0B90B)
![Polygon](https://img.shields.io/badge/Network-Polygon-8247E5)
![Author](https://img.shields.io/badge/Author-Swir-ff4fa3)

</div>

---

## 🇬🇧 English

Multichain Tracker is a Python command-line utility for checking native wallet balances across BNB Chain, Ethereum and Polygon. It queries public blockchain explorer APIs and can also retrieve market prices through CoinGecko and display recent transaction information.

### ✨ Features
- BNB Chain native balance
- Ethereum native balance
- Polygon native balance
- blockchain-explorer API integration
- recent transaction lookup
- CoinGecko market-price lookup
- colored terminal output with Colorama

### 🔑 Configuration
Before running the program, provide your own API keys in the configuration constants inside `main`:

```text
BSCT_API_KEY
ETH_API_KEY
MATIC_API_KEY
```

Never commit real private API keys, seed phrases or wallet private keys to a public repository.

### 🚀 Run

```bash
git clone https://github.com/Swir/Multichain-Tracker.git
cd Multichain-Tracker
pip install requests colorama
python main
```

---

## 🇵🇱 Polski

Multichain Tracker to konsolowe narzędzie Python do sprawdzania natywnych sald portfela w sieciach BNB Chain, Ethereum i Polygon. Program korzysta z API eksploratorów blockchain oraz CoinGecko i może prezentować informacje o ostatnich transakcjach.

### ✨ Funkcje
- saldo BNB Chain
- saldo Ethereum
- saldo Polygon
- integracja z API eksploratorów blockchain
- podgląd ostatnich transakcji
- pobieranie cen z CoinGecko
- kolorowy terminal dzięki Colorama

### 🔑 Konfiguracja
Przed uruchomieniem wpisz własne klucze API w odpowiednich stałych w pliku `main`. Nigdy nie publikuj kluczy prywatnych portfela ani seed phrase.

### 🚀 Uruchomienie

```bash
pip install requests colorama
python main
```

> This project is a read-only tracking utility and does not require wallet private keys. / Do monitorowania publicznego adresu portfela nie są potrzebne klucze prywatne.

## 👤 Author / Autor
Developed by **Swir**.
