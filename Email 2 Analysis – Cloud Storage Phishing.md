
## 📧 Phishing Email Analysis #2 – “Cloud Storage Payment Failed”

### 🔎 Overview
This email impersonates a cloud storage provider and uses fear-based messaging to manipulate users into updating their payment information on a likely phishing website.

---

### 📸 Screenshot  
![Phishing Email Screenshot](screenshots/email2.png)

---

### 🚩 Suspicious Indicators

- **From Address:** `totalsecurity@auqzjtcy...firebaseapp.com` – suspicious, not from a known cloud provider domain
- **Display Name:** "Cloud Storage" – vague and impersonates legitimate service
- **Urgency and Threat Language:** “Your photos and videos will be deleted!!!” – fear-based manipulation
- **Payment Urgency:** Pushes user to “update your payment information” quickly
- **Fake Visual Elements:** Storage usage meter is fake and used to increase panic
- **No Personalization:** No name, no user ID – clearly mass sent
- **Suspicious Hosting:** Firebaseapp.com often used in phishing kits

---

### 🛠️ Tools I used

- **VirusTotal** – to scan any button or URL for malware/phishing
- **urlscan.io** – to preview and trace the link destination
- **MXToolbox** – to inspect the email domain for validation records
- **Gmail “Show Original”** – to check headers for SPF/DKIM and server info

---

### ✅ Verdict

This email is a textbook phishing attempt using emotional urgency, fake data loss threats, and impersonation of a trusted service. It should be reported, flagged as spam, and avoided at all costs.

---

