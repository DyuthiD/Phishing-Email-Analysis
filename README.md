#  Phishing-Email-Analysis

## 🎯 Objective
The goal of this task was to analyze a sample phishing email and identify common phishing indicators using header analysis and content inspection. This exercise helps build awareness of email-based cyber threats and improves our ability to recognize social engineering attacks.

---

## 🛠 Tools Used
- Free online phishing email sample
- Online Email Header Analyzer (e.g., MXToolbox , EML Analyzer)
- Virustool Inspection

---

## 🔍 What I Did

### 1️⃣ Collected a Sample Phishing Email
I used a free phishing email sample from online repositories. The email resembled a fake bank alert prompting urgent action.

### 2️⃣ Analyzed the Email for Key Indicators

| Indicator                      | Observation                                                                 |
|-------------------------------|------------------------------------------------------------------------------|
| 🧑‍💻 Sender Email Address      | The display name was "Bank Support" but the email was from a suspicious domain ) |
| 🪪 Email Header Inspection     | SPF failed, and the return path domain did not match the sender domain     |
| 🔗 Link Inspection             | Hyperlinks redirected to domains unrelated to the real bank  |
| ⚠️ Language & Urgency          | Used scare tactics like "Your account will be locked in 24 hours"          |
| 🔠 Spelling/Grammar Issues     | Multiple grammatical errors and formatting inconsistencies                  |

---

## 🚨 Summary of Phishing Traits Found
- **Email spoofing** using a misleading sender address
- **Fake links** redirecting to phishing websites
- **Urgency** and **fear tactics** to manipulate user actions
- **Poor language quality** indicating it wasn't from a professional source
- **SPF/DKIM mismatch** in email headers

---

## 🧠 Key Learning
- Gained practical experience in identifying real phishing characteristics
- Understood how attackers use **social engineering** in phishing emails
- Learned how to use header analysis tools to verify sender authenticity

---

## 📁 Files Included
- `Phishing_Email_Analysis_Report.pdf`: Summary report listing phishing indicators found
- `Sample_Phishing_email.eml`: The sample phishing email content
- `EML_analyser.png`: Screenshot of header analysis using EML Analyzer
- `Mxtoolbox_header_analysis.png`: Screenshot of header analysis using MXToolBox
- `README.md`: Explanation of the task and what was done

---
