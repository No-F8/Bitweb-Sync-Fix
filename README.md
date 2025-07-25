# Bitweb Sync Fix

If your Bitweb wallet stalls at block `938000`, use this bootstrap to get past the issue.

---

## 📦 Instructions

1. **Download** `bootstrap.dat` from the release below.  
2. **Place** the file in your Bitweb data directory — the same folder that contains:
   - `peers.dat`, `debug.log`, `mempool.dat`, etc.
3. **Start your Bitweb wallet** — it will automatically detect the file and fast-forward past the broken block.
4. **Once synced**, you can safely delete `bootstrap.dat`.

---

## 🧱 Details

- Includes **raw block data** from **height 937999 to 938010** (12 blocks total).
- No commands or special setup required — works with default Bitweb Core configuration.
