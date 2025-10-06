
## 📧 Phishing Email Analysis #1 – “Congrats! You're Qualified..”

### 🔎 Overview
An email targeting crypto subscribers with an urgent token airdrop offer, attempting to collect wallet credentials under the guise of a reward.

---

### 📸 Screenshot  
![Phishing Email Screenshot](https://github.com/jimidorcas/Phishing-analysis-portfolio/blob/main/email1.jpg)

---

### 🚩 Suspicious Indicators

- **Urgency:** “Claim before the deadline”, “Unclaimed tokens will be redistributed”
- **Incentive:** Free $MILK token offered just for being a subscriber
- **Request to Connect Wallet:** “Connect your wallet with the secure link” – common tactic for wallet draining scams
- **No legitimate sender information or contact details**
- **No unsubscribe button** – usually present in newsletters

---

### 📧 Sender Domain Inconsistency

A major red flag was the **email sender domain**:

- Legitimate emails from *Milk Road* always come from **@milkroad.com**
- This phishing email was sent from **@substack.com**
- This mismatch is a classic sign of spoofing or impersonation

---

### 🛠️ Tools I used

- **VirusTotal** – to scan the airdrop URL for malware or phishing content
- **urlscan.io** – to analyze URL behavior and redirection
- **MXToolbox** – to verify the sender’s domain has SPF/DKIM
- **Gmail “Show Original”** – to inspect email headers for signs of spoofing

---

### ✅ Verdict

This email uses **social engineering** to trick users into connecting their crypto wallets by offering fake rewards. It is a **clear phishing attempt** that should be reported and avoided.
