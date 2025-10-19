# HL Analytics Bot — Quick Tutorial

HL Analytics Bot is a **real-time radar** for Hyperliquid.  
It pings you on **Telegram** when big money (whales) comes in or when your **insider wallets** move.

---

## Access requirement (mandatory)

You must hold **at least 50 USD** of the **HLAN** token in your Solana wallet.

- **Ticker:** HLAN  
- **Contract (mint):** `HU3HaYPJBXC64b6rJ6ppKv9xj8BuhJaeUnpLhG1cpump`

Without this, **the bot won’t start**.

---

## Download (Windows)

- **Download the executable (.exe):**  
  https://raw.githubusercontent.com/hhlanalyticsbot/hl-analytics-bot/main/windows_version/HL%20Analytics%20Bot.exe

> If Windows shows a security warning: click **More info → Run anyway**.  
> Or: right-click the **EXE** → **Properties → Unblock → Apply**, then open it.

---

## First-time setup (about 3 minutes)

1) **Connect your wallet**  
   - Open the app → click **Connect Wallet** → Chrome opens → sign with **Phantom** (free, no transaction).  
   - Go back to the app. If you see *Access granted*, you’re good.

2) **Set the “MEGA” threshold**  
   - In **MEGA Threshold (USD)** enter your amount (e.g., `1000000`) → click **Save**.

   **What is MEGA?**  
   It’s the **USD amount** that must be **moved** to trigger an alert:
   - by **one single whale wallet**, **or**
   - by the **market total** (all wallets together, long or short).

3) **Turn on Telegram alerts**  
   - In **Chat ID**, paste your Telegram chat ID.  
   - **Don’t know your Chat ID?** Click **Get Chat ID** — it opens the bot that tells you your ID (send /start and copy the number).  
   - Click **Save & Test** — you should receive “Test OK” on Telegram.  
   - Click **Open Bot** to open **@hl_analytics_alerts_bot** and press **Start** in the chat.

4) **(Optional) Insider wallets**  
   - On the right, paste a wallet address and press **Add**.  
   - If any of these wallets moves at least **MEGA**, you’ll get an **INSIDER move** alert.

5) **Start**  
   - Press **Start Bot**. From now on, alerts will come in.

---

## Alerts you’ll receive

- **MEGA (single wallet)** — one **whale** moves at least **MEGA** (BUY/SELL) in ~60s.  
- **MEGA (market net)** — the **total market flow** (long/short) crosses **MEGA** in ~60s.  
- **INSIDER move** — a wallet from your list crosses the **same MEGA threshold**.

Each alert shows: **pair**, **direction (BUY/SELL or NET)**, **amount**, **time**, and the **wallet** (⭐ if it’s in your insider list).

---

## MEGA threshold tips

- **50,000 – 100,000 USD** → more sensitive (many signals)  
- **1,000,000 – 2,500,000 USD** → balanced  
- **5,000,000+ USD** → only very heavy moves

Set it, try it, and adjust. You can change it any time with **Save**.

---

## Buttons (plain English)

- **Connect Wallet** → links your wallet and unlocks access (checks HLAN ≥ $50).  
- **MEGA Threshold (USD) + Save** → sets the money threshold that triggers alerts.  
- **Chat ID** → where to send Telegram messages.  
- **Get Chat ID** → opens the helper bot that **tells you your ID** (super handy).  
- **Open Bot** → opens our alert bot on Telegram (remember to press **Start**).  
- **Save & Test** → saves and sends a test message to your Chat ID.  
- **Insider wallets → Add / Remove selected** → manage the wallet list you want to track.  
- **Start Bot / Stop Bot** → start or stop the bot.  
- **Reset Session** → disconnect wallet and reset the session.

---

## Quick fixes (most common issues)

- **No test alert arrives**  
  - Open **Open Bot** on Telegram and press **Start**.  
  - Get your ID with **Get Chat ID**, paste it again, then **Save & Test**.

- **Access denied**  
  - Make sure the **connected wallet** holds **≥ 50 USD** of **HLAN**. Click **Connect Wallet** again.

- **Windows blocks the EXE**  
  - **More info → Run anyway**, or **Properties → Unblock**.

---

## Contact

- **X (Twitter):** https://x.com/AnalyticsHl

---

## Legal

For informational purposes only. **Not** financial advice.

