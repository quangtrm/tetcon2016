# XcodeGhost: iOS Malware via Xcode IDE

This repository contains the slides from the **TetCon 2016** presentation:  
**"XcodeGhost: iOS Malware via Xcode IDE"**  
Presented by **Long Nguyen & Quang Tran**  
**TetCon 2016 | PiggyBird CTF Team | Viettel Cyber Security**

---

## 📌 Overview
This presentation explores **XcodeGhost**, a widespread iOS malware that compromised applications built using a trojanized version of Xcode. Key topics include:
- **Infection mechanism**: How XcodeGhost bypassed Apple's security checks.
- **Impact assessment**: Data exfiltration, phishing risks, and infected applications.
- **Real-world infection statistics**: Global vs. Vietnam-specific cases.
- **Detection & mitigation strategies**: Sinkholing C&C domains, enterprise security measures.

---

## 📂 Files
- 📄 **`XcodeGhost_EN.pdf`** – Presentation slides from TetCon 2016.

---

## 🚀 Key Takeaways
- **XcodeGhost infected numerous popular iOS apps**, including WeChat and CamScanner.
- **Malware exfiltrated device information** such as app version, iOS version, device ID, and location.
- **Phishing risks emerged** from attacker-controlled alert messages displayed via infected apps.
- **DNS sinkholing and application monitoring** were effective in mitigating infections.

---

## 🛡 Defense Strategies
- **Monitor app integrity**: Ensure apps are compiled using legitimate Xcode versions.
- **Enterprise & ISP defenses**: Sinkhole C&C domains to prevent communication.
- **Regular security updates**: Keep applications and devices patched to remove infected versions.
- **User awareness**: Recognize phishing messages and avoid sideloading unverified applications.

---

## 📢 About the Speakers
- **Long Nguyen & Quang Tran** - Security Researchers, PiggyBird CTF Team  
  📍 **Expertise**: Mobile security, malware analysis, vulnerability research  
  ✉️ Contact: [Your Email] | [Viettel Cyber Security](https://viettelcybersecurity.com)

---

## ⚠️ Disclaimer
This repository is for **educational and research purposes only**. The authors and Viettel Cyber Security are not responsible for any misuse of the information.

---

📲 **Stay protected from mobile malware threats like XcodeGhost!**
