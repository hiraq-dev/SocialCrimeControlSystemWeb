# 🚓 Crime Alert Application  
A Web-Based Social Crime Control System for Public Safety & Law Enforcement

The **Crime Alert Application** is a web-based platform designed to assist law enforcement agencies and the general public in reporting, tracking, and preventing criminal activities. It aims to modernize crime reporting and public safety services in countries like Pakistan, where social crime rates are relatively high and digital reporting systems are still emerging.

This system enables:
- Secure online FIR submission  
- Crime alert reporting by citizens  
- Public data sharing of reported incidents  
- Security-related services (e.g., hiring off-duty officers)  
- Listing most-wanted and missing persons  
- Real-time communication (planned feature)

---

## 📌 Features

### 1. 📝 Online FIR System
A complete digital FIR submission module:
- Victim must create an account (CNIC + password, validated via NADRA)
- Victim provides personal details: name, contact, CNIC, address
- Report details: incident location, description, time/date
- FIR is securely stored in the database and forwarded to relevant authorities
- Victim can view status through the “Data Sharing” section  
- Reduces fake or fraudulent reporting

---

### 2. 🚨 Crime Alert Module
Allows citizens to report suspicious activities anonymously or with identity:
- Name  
- CNIC  
- Place of incident  
- Incident details  
- Evidence: images, documents, videos  

Reports are kept confidential and accessible only to security departments for investigation.

---

### 3. 🔍 Data Sharing (Public)
A public-facing section where verified FIR data is displayed:
Fields shared:
- Date  
- Place  
- Nearest police station  
- Incident summary  

This improves transparency and allows citizens to stay informed about crimes in their area.

---

### 4. 🛡 Security & Support Services
This module provides specialized security services using verified off-duty police officers:

#### a) Public & Private Events
Security for:
- Sports events  
- Corporate events  
- School programs  
- Weddings and private parties  

#### b) Corporate, Retail & Banks
Executive protection, workplace safety, building security.

#### c) Road Construction & Traffic Management  
Controlling traffic flow during:
- Parades  
- Religious gatherings  
- Construction projects  

#### d) Personal Protection  
Bodyguards and VIP protection, secure transport for valuables.

#### e) Construction Sites  
Equipment/material protection, site monitoring.

#### f) Building Security  
Security for offices, malls, hospitals, property management.

#### g) Home Owner Associations  
Patrolling and meeting security for communities.

#### h) Film Sets & Celebrities  
Crowd control, set security, bodyguard services.

---

### 5. 👤 Most Wanted List
A dynamic list of most-wanted criminals.  
Citizens can report sightings through the Crime Alert module.

---

### 6. 🧑‍🧒 Missing Person Directory
Displays missing individuals.  
Users can directly contact authorities if spotted.

---

## ⚙️ System Architecture

### **Frontend**
- ASP.NET MVC (views, controllers, routing)
- Responsive UI for public and police use

### **Backend**
- ASP.NET MVC with repository pattern  
- Database connectivity  
- Secure form handling  
- Account authentication  

### **Database**
Stores:
- FIR reports  
- Crime alerts  
- User accounts  
- Services requests  
- Most wanted & missing persons  

---

## 🚧 Challenges Faced During Development
- Complexity of ASP.NET MVC framework
- Database connectivity, form validation, model binding
- Collecting real FIR/Crime data from Karachi Police
- Handling fake reporting  
- Difficulties integrating online counselling / live chat module
- Time constraints and missing advanced features

---

## 🔐 Security Measures
- Authentication required for FIR submission (CNIC + password)
- Authorization for sensitive data
- Protection of URLs and restricted routes
- Secure data storage (DB-level)

---

## 📈 Planned Features
- Online counseling / live chat system  
- Real-time visitor tracking  
- Dashboard analytics  
- Improved UI/UX  
- Enhanced data visualization  

---

## 🌐 References & Inspiration
- Karachi Police: http://kppolice.gov.pk  
- SpotCrime: https://www.spotcrime.com  
- CrimeReports: https://www.crimereports.com  
- NYPD Crime Stoppers  
- Criminal Justice Resources  

---

## 📄 License
This project is for **academic and research purposes only**.

---

## 👩‍💻 About the Developers
Developed by students to improve public safety through digital innovation and modern crime reporting systems.

