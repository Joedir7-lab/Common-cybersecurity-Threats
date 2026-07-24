# Assignment 3: Understanding Common Cyber Threats

## Part A: Definitions

**1. What is a cyber threat?**  
A cyber threat is any potential danger that could harm computer systems, networks, or data. It doesn’t have to happen yet - it’s just the possibility that something bad could occur.

**2. What is a vulnerability?**  
A vulnerability is a weakness or flaw in software, hardware, or even human behavior. It’s like an open door that a threat can use to get in.

**3. What is a cyber attack?**  
A cyber attack is when someone actually tries to exploit a vulnerability to damage a system, steal data, or disrupt services.

**4. Explain the difference between a threat, a vulnerability, and an attack.**  
Think of a house:
- **Threat** = A burglar walking around your neighborhood. They *could* break in.
- **Vulnerability** = You left your window unlocked. That’s the weakness.  
- **Attack** = The burglar actually climbs through the window and steals something.  
So: Threat is the possibility, Vulnerability is the weakness, Attack is the action.

---

## Part B: Research

### **1. Phishing**
**What it is**: Tricking people with fake emails, texts, or websites to get personal info like passwords or card details.  

**How it works**: Attackers pretend to be a trusted company. They send a link that looks real. When you click and log in, they steal what you type.  

**Real-life example**: 2020 Google Docs Phishing. People got emails saying "Someone shared a Google Doc with you". The link led to a fake login page and thousands of Google accounts were stolen.  

**How to protect yourself**: 
- Check the sender’s email address carefully
- Don’t click links from unknown emails
- Enable 2-Factor Authentication
- Hover over links to see the real URL

### **2. Malware**
**What it is**: Malicious software made to damage or spy on a device. Includes viruses, trojans, and spyware.  

**How it works**: You download it by clicking a bad attachment or fake app. Once installed, it can delete files, record keystrokes, or send your data to hackers.  

**Real-life example**: Emotet (2014-2021). It spread through infected Word documents and stole banking info from millions of computers before being taken down by police.  

**How to protect yourself**:
- Keep antivirus software updated
- Don’t download files from unknown sources
- Update your OS and apps regularly
- Backup important files

### **3. Ransomware**
**What it is**: Malware that locks your files and demands money to unlock them.  

**How it works**: It encrypts all your documents and photos. A message pops up asking for Bitcoin payment with a countdown timer.  

**Real-life example**: Colonial Pipeline (2021). Hackers shut down a major US fuel pipeline with ransomware. The company paid $4.4 million to get operations back.  

**How to protect yourself**:
- Keep offline backups of important data
- Don’t open suspicious email attachments
- Use endpoint protection and firewalls
- Patch software vulnerabilities quickly

### **4. Social Engineering**
**What it is**: Manipulating people instead of computers to get access to info or systems.  

**How it works**: Attackers build trust by pretending to be IT support, a boss, or a friend. They convince you to give up passwords or transfer money.  

**Real-life example**: 2020 Twitter Hack. Attackers called Twitter employees pretending to be from IT. They got login credentials and used them to hack celebrity accounts to run a Bitcoin scam.  

**How to protect yourself**:
- Verify anyone asking for sensitive info, even over the phone
- Security awareness training
- Don’t overshare personal details online
- Use multi-person approval for money transfers

### **5. Denial-of-Service (DoS/DDoS)**
**What it is**: Flooding a website or server with so much traffic that it crashes and real users can’t access it.  

**How it works**: DoS = one computer. DDoS = thousands of infected computers called a "botnet" all attack at once.  

**Real-life example**: Dyn DNS Attack (2016). The Mirai botnet attacked Dyn, a company that runs website addresses. Sites like Netflix, Twitter, and Reddit went offline for hours.  

**How to protect yourself**:
- Use DDoS protection services like Cloudflare
- Set up traffic rate limits and firewalls
- Have backup servers
- Keep IoT devices patched so they can’t join botnets

---

## Part C: Critical Thinking

**1. Which cyber attack do you think is the most dangerous today, and why?**  
I think **Ransomware** is the most dangerous today.  
Reason: It hits both individuals and critical organizations like hospitals, schools, and pipelines. Unlike data theft where you might not know you were hit, ransomware shuts everything down immediately. It also makes money for criminals, so attacks keep increasing. Even with backups, the downtime can cost millions and risk lives in hospitals.

**2. If you were the IT manager of a bank, which three security measures would you implement first to protect customers?**  
1. **Multi-Factor Authentication (MFA) for all accounts** - Even if a password is stolen in a phishing attack, hackers still can’t log in without the second code.
2. **Employee Security Training + Phishing Simulations** - Most bank breaches start with a person clicking something. Training staff to spot social engineering is the cheapest and most effective defense.
3. **24/7 Monitoring + Regular Backups** - Constant monitoring to detect attacks early, and daily offline backups so if ransomware hits, we can restore customer data without paying.# Common-cybersecurity-Threats