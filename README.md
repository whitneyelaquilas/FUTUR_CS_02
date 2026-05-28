# 📧 Phishing Email Detection & Awareness System

## 📌 Overview

This project simulates a real-world cybersecurity task: **detecting, analyzing, and classifying phishing emails** using manual inspection and security tools. The goal is to help organizations and individuals recognize phishing attempts, understand attacker techniques, and respond appropriately.

The project includes:
- Analysis of **3 email samples** (Phishing, Suspicious, Safe)
- Use of **VirusTotal**, **MXToolbox**, and manual inspection techniques
- Business-friendly explanations for non-technical users
- Clear **prevention guidelines** and **incident response steps**

---

## 🎯 Objectives

- Identify phishing indicators (spoofed sender, fake domains, malicious links, dangerous attachments)
- Classify emails as **Safe**, **Suspicious**, or **Phishing**
- Explain phishing techniques in simple, business-friendly language
- Provide actionable awareness and prevention guidelines for employees

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| [VirusTotal](https://www.virustotal.com) | Scan URLs and attachments across 90+ security vendors |
| [MXToolbox](https://mxtoolbox.com) | Check DNS, MX, DMARC, and domain reputation |
| Google Messageheader (simulated) | Analyze email headers for spoofing |
| Manual inspection | Sender address, subject line, attachments, urgency cues |

---

## 📂 Email Samples Analyzed

| Sample | Classification | Key Indicators |
|--------|----------------|----------------|
| PayPal Impersonation | 🚫 **Phishing** | Fake domain (`paypa1.com`), shortened malicious link (bit.ly flagged by VirusTotal), urgency threat |
| HR Benefits Email | ⚠️ **Suspicious** | Suspicious domain, double-extension attachment (`bonus_form.pdf.exe`), no personalisation |
| Tech Today Newsletter | ✅ **Safe** | Legitimate domain, plain links, unsubscribe option, no urgency |

---

## 🔍 Key Findings

### 🚫 Phishing Email (PayPal)
- **Fake domain:** `paypa1.com` (typosquatting)
- **Shortened link:** `bit.ly` → redirected to fake PayPal login page
- **VirusTotal result:** 1/92 vendors flagged as phishing
- **Risk:** Credential theft

### ⚠️ Suspicious Email (HR Benefits)
- **Fake domain:** `company-updates.co`
- **Malicious attachment:** `bonus_form.pdf.exe` (double extension hiding an executable)
- **Risk:** Ransomware, keylogger, remote access

### ✅ Safe Email (Tech Today)
- **Legitimate domain:** `techtoday.com`
- **Plain-text links:** No URL shortening
- **Unsubscribe option:** Present and functional
- **VirusTotal result:** 0/92 detections

---

## 📊 Classification Summary

| Sample | Key Indicators | Classification |
|--------|----------------|----------------|
| PayPal | Fake domain, urgent threat, malicious link | 🚫 Phishing |
| HR Benefits | Suspicious domain, double-extension attachment | ⚠️ Suspicious |
| Tech Today | Correct domain, plain links, no urgency | ✅ Safe |

---

## 🧠 Phishing Techniques Explained (Business-Friendly)

| Technique | Description |
|-----------|-------------|
| **Typosquatting** | Fake domains like `paypa1.com` instead of `paypal.com` |
| **URL Shortening** | bit.ly links hide malicious destinations |
| **Urgency & Fear** | "Your account will be locked in 24 hours" |
| **Spoofed Sender** | Fake "From" address with trusted display name |
| **Double Extensions** | `invoice.pdf.exe` hides the real `.exe` |
| **Brand Impersonation** | Fake logos and formatting of trusted brands |

---

## 🛡️ Prevention Guidelines for Employees

### ✅ Before Clicking Anything
- Check the sender's full email address (not just display name)
- Hover over links to see the real destination
- Never open unexpected attachments without verification
- Look for spelling/grammar mistakes
- Verify unusual requests via a different channel (phone call, separate email)

### 🚩 Red Flags to Memorise
- "Your account will be suspended"
- "Click here to verify"
- Shortened links (bit.ly, tinyurl) in official emails
- Generic greeting ("Dear Customer")
- Request for password or MFA code

---

## 🚨 What to Do If You Suspect or Fall for Phishing

### If you suspect (haven't clicked)
- Do NOT click links or open attachments
- Report to IT/security team
- Delete the email

### If you clicked a link (no credentials entered)
- Close the browser tab
- Run a full antivirus scan
- Report to IT

### If you entered your password
- Change your password immediately
- Enable MFA if not already active
- Check for unauthorised activity
- Notify IT

### If you opened a malicious attachment
- Disconnect from the network immediately
- Do NOT restart the computer
- Contact IT immediately

---


## 📁 Repository Contents
