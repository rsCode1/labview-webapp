# LabView Dashboard – Real-Time Processor Testing Visualization

![Dashboard Home Page](https://github.com/rsCode1/labview-webapp/blob/main/labview%20screenshots/labview%20main%20page%20blur.png?raw=true)

## 📌 Overview

This repository showcases the **LabView Dashboard**, a full-stack web application designed and developed during my student position at Intel. The application enhances the efficiency and reliability of processor stress-testing by providing real-time monitoring, dynamic visualization, and streamlined data analysis. Codeless repository.
---

## 💡 Motivation

During processor stress-testing at Intel, significant challenges were identified:

- **Tester malfunctions** causing prolonged downtime.
- **Delayed monitoring**, preventing real-time response.
- **Inefficient resource planning** due to the absence of clear visual insights.

The LabView Dashboard addresses these issues, significantly improving response times, recovery from failures, and planning efficiency.

---

## 🚀 Key Features

- **Real-time log analysis:** Continuously parses vast log data, extracting critical metrics instantly.
- **Dynamic visualization:** Presents intuitive dashboards to track test progress.
- **Anomaly detection:** Quickly identifies overstressed CPUs and test anomalies.
- **Efficient planning:** Provides accurate estimates for improved resource allocation.
- **User-tailored Interface:** Accessible by engineers, technicians, and management.

---

## 🛠️ Tech Stack

- **Frontend:** Angular, ngx-charts
- **Backend:** C# (.NET Worker Service)
- **Database:** MariaDB
- **API:** RESTful API (C#)

---

## 🔧 System Architecture

The system is structured into three primary layers:

1. **Worker Service:**
   - Copies and combines logs.
   - Parses essential metrics and detects anomalies.
   - Uploads processed data into MariaDB.

2. **Backend/API:**
   - Exposes RESTful endpoints for data access.

3. **Frontend (Angular):**
   - Displays real-time test metrics and results.
   - Utilizes interactive charts and cards for visualization.

![System Architecture](https://github.com/rsCode1/labview-webapp/blob/main/labview%20screenshots/architecture.png?raw=true)

---

## 📸 Screenshots

### Dashboard Overview
![Dashboard Overview](https://github.com/rsCode1/labview-webapp/blob/main/labview%20screenshots/labview%20main%20page%20blur.png?raw=true)

### CPU Test Results
![CPU Test Results](https://github.com/rsCode1/labview-webapp/blob/main/labview%20screenshots/labview%20result%20card%20blur.png?raw=true)

### Dark Mode
![Dashboard Overview](https://github.com/rsCode1/labview-webapp/blob/main/labview%20screenshots/labview%20main%20page%20dark.png?raw=true)


---

## 📈 Results & Impact

- **50% reduction** in response time to test failures.
- **75% faster recovery** from tester hardware issues.
- **30% improvement** in lab planning efficiency.
- **100% data accuracy** during monitoring period.
- **98% system uptime**.

Real-time insights enabled rapid identification of overstressed CPUs, significantly reducing downtime and improving overall testing efficiency.

---

## 📚 Academic Reference

The detailed explanation and academic evaluation of this project were documented as part of my graduation paper for my Software Engineering degree.

---



