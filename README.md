# Bitweb Full Bootstrap – July 25, 2025 📦

If your Bitweb wallet is stalling during synchronization or you're setting up a new node, this full bootstrap can help you skip the slow initial sync.

---

## 🔧 What’s Included

This bootstrap archive contains:

- `blocks/` – Full blockchain data  
- `chainstate/` – UTXO state to enable rapid validation  
- `indexes/` – Helps speed up transaction lookup and rescan  
- `hashes/` – Metadata used by wallet  
- `peers.dat` – Peer list to help connect quickly

Snapshot height: **Block ~2,156,000**  
Snapshot date: **25 July 2025**

---

## 📥 Installation Instructions

1. **Close** your Bitweb Core wallet if it's running.
2. **Backup** your wallet and data folder:
   - Make a copy of your `wallets/` directory and `wallet.dat` file if you're not doing a clean install.
3. **Download** the latest `bitweb-bootstrap-20250715.zip` file from the Releases section.
4. **Extract** the contents into your Bitweb data directory:
   - Windows default:  
     `C:\Users\<YourName>\AppData\Roaming\Bitweb\`
   - Linux default:  
     `~/.bitweb/`
5. **Start** your Bitweb wallet — it will begin syncing from the current chain tip without re-downloading old blocks.

---

## ✅ Notes

- This is an **NitroPool official snapshot** taken from our fully synced node.
- Useful for speeding up sync time or recovering from corrupt chainstate.
- If you experience issues with the bootstrap, try starting Bitweb with the `-reindex` flag once.

---

Happy syncing! ⚡  
_Provided by the NitroPool team_
