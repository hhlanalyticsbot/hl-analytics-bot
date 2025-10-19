HL Analytics Bot — Quick Tutorial (TXT)

HL Analytics Bot is a real-time radar for Hyperliquid.
It notifies you on Telegram when big money (whales) moves or when your insider wallets act.

------------------------------------------------------------
ACCESS REQUIREMENT (MANDATORY)
------------------------------------------------------------
You must hold at least 50 USD of the HLAN token in your Solana wallet.
Ticker: HLAN
Contract (mint): HU3HaYPJBXC64b6rJ6ppKv9xj8BuhJaeUnpLhG1cpump
Without this, the bot won’t start.

------------------------------------------------------------
DOWNLOAD (WINDOWS)
------------------------------------------------------------
Get the executable (.exe):
https://github.com/hhlanalyticsbot/hl-analytics-bot/releases/latest/download/HL%20Analytics%20Bot.exe

If Windows shows a security warning: click “More info → Run anyway”.
Or: right‑click the EXE → Properties → Unblock → Apply, then open it.

------------------------------------------------------------
FIRST-TIME SETUP (≈ 3 MINUTES)
------------------------------------------------------------
1) Connect your wallet
   - Open the app → Connect Wallet → Chrome opens → sign with Phantom (free, no transaction).
   - Go back to the app. If you see “Access granted”, you’re ready.

2) Set your “MEGA” threshold
   - In MEGA Threshold (USD) enter an amount (e.g., 1000000) → Save.
   - What is MEGA? It’s the USD amount that must be moved to trigger an alert:
     • by one single whale wallet, OR
     • by the market total (all wallets together, long or short).

3) Enable Telegram alerts
   - Paste your Chat ID in the Chat ID field.
   - Don’t know your Chat ID? Click “Get Chat ID” — it opens a helper bot that tells you your ID (send /start and copy the number).
   - Click “Save & Test” — you should receive a “Test OK” message on Telegram.
   - Click “Open Bot” to open @hl_analytics_alerts_bot and press “Start” in the chat.

4) (Optional) Insider wallets
   - Paste any wallet address and press “Add”.
   - If an insider moves at least MEGA, you’ll get an “INSIDER move” alert.

5) Start
   - Press “Start Bot”. Alerts will begin to arrive.

------------------------------------------------------------
ALERTS YOU’LL RECEIVE
------------------------------------------------------------
• MEGA (single wallet) — one whale moves at least MEGA (BUY/SELL) in ~60s.
• MEGA (market net) — the total market flow (long/short) crosses MEGA in ~60s.
• INSIDER move — a wallet from your insider list crosses the same MEGA threshold.
Each alert shows the pair, direction (BUY/SELL or NET), amount, time, and the wallet (⭐ if it’s one of your insiders).

------------------------------------------------------------
MEGA THRESHOLD TIPS
------------------------------------------------------------
• 50,000 – 100,000 USD → more sensitive (many signals)
• 1,000,000 – 2,500,000 USD → balanced
• 5,000,000+ USD → only very heavy moves
Adjust anytime and press “Save”.

------------------------------------------------------------
BUTTONS (PLAIN ENGLISH)
------------------------------------------------------------
• Connect Wallet — links your wallet and unlocks access (checks HLAN ≥ $50).
• MEGA Threshold (USD) + Save — sets the money threshold that triggers alerts.
• Chat ID — where to send Telegram messages.
• Get Chat ID — opens the helper bot that tells you your ID.
• Open Bot — opens our alert bot on Telegram (remember to press Start).
• Save & Test — saves and sends a test message to your Chat ID.
• Insider wallets → Add / Remove selected — manage the wallet list you monitor.
• Start Bot / Stop Bot — start or stop the bot.
• Reset Session — disconnect the wallet and reset the session.

------------------------------------------------------------
QUICK FIXES
------------------------------------------------------------
• No test alert arrives:
  - Open “Open Bot” on Telegram and press “Start”.
  - Get your ID with “Get Chat ID”, paste it again, then “Save & Test”.
• Access denied:
  - Ensure the connected wallet holds ≥ 50 USD of HLAN. Click “Connect Wallet” again.
• Windows blocks the EXE:
  - “More info → Run anyway”, or Properties → Unblock.

------------------------------------------------------------
CONTACT
------------------------------------------------------------
X (Twitter): https://x.com/AnalyticsHl

------------------------------------------------------------
LEGAL
------------------------------------------------------------
For informational purposes only. Not financial advice.
