# eSTA – Electronic Staging Area (Elektronsko Sprejemno Mesto)

**eSTA** is a mission-critical tactical resource management system designed for **Staging Area Teams (STT)**, incident commanders, and logistics officers. It replaces traditional paper logs and static spreadsheets with a dynamic, real-time digital environment tailored for high-pressure, long-duration emergency interventions.

Built following the **IPS (Intervencijsko Poveljniški Sistem)** framework, eSTA ensures that command decisions are based on a "single source of truth," synchronized across all terminals in the field and headquarters.

---

## 🚀 Key Tactical Capabilities

### 📡 Real-Time Operational Sync
Forget page refreshes. Powered by event-driven architecture, every status change, unit arrival, or sector movement is broadcast to every connected terminal instantly. Whether you are at the reception desk or the command trailer, the picture is the same.

### 🏢 Live Sector & Resource Mapping
* **Tactical Drag-and-Drop:** Move units from "Reception" to specific "Sectors" or "Groups" (Vodi) using an intuitive Kanban-style live interface.
* **Unit Identification:** Track detailed resource types (GVC, AC, GVV-1, etc.), including crew counts and water capacities.
* **Workload & Fatigue Monitoring:** A specialized "Intensity Monitor" tracks active hours vs. standby time to help commanders prevent crew exhaustion.



### 📝 Automated Documentation & Audit Trails
* **Visual Activity Log:** A graphical chronology of every move made during the intervention—perfect for post-incident analysis.
* **Digital Discharge (Odpustni list):** Automated generation of official PDF discharge papers, capturing equipment damage, personnel injuries, and mileage.
* **Strategic Reports:** One-click exports of resource distribution, unit archives, and activity logs to **Excel (.xlsx)** and **PDF**.

---

## 🛠 Strategic Modules

### 1. Reception & Onboarding (Sprejemno Mesto)
The entry gate for the intervention. Capture leader contacts, initial equipment status, and arrival timestamps in seconds.


### 2. Live Command Support (Podpora Vodenju)
The "War Room" view. Distribute forces across geographical sectors, monitor the "Live Edit" mode for quick re-assignments, and view the strategic strength of the entire operation.


### 3. Logistical Monitoring (Monitor Obremenitve)
Detailed analytics of work intensity. View percentage-based workload bars to see which teams have been active the longest and need rotation.


### 4. Archive & Intelligence (Arhiv in Poročila)
A permanent record of every unit that participated. Searchable, filterable, and exportable data for official reporting and financial accounting.

---

## 💻 Tech Stack & Design
The system is designed with a **SaaS-style interface** (built on Tailwind CSS and Inter font) to ensure clarity under stress:
* **Socket.io** for bi-directional live synchronization.
* **SortableJS** for physical resource mapping.
* **DataTables.net** for advanced server-side filtering of massive datasets.
* **jsPDF & SheetJS** for professional document generation.

---

## 📋 IPS Methodology Compliance
The system is built strictly around ICS/IPS principles:
* **Unity of Command:** Clear leadership contacts for every unit and sector.
* **Span of Control:** Visual cues when sectors become over-saturated.
* **Standardized Communication:** Automated logging of unit movements to reduce radio traffic.

---

## 📞 Get in Touch

> **Notice:** This repository is for **presentation purposes only**. The source code is not publicly available to ensure the integrity and security of the systems used by active emergency services.

If you are interested in a demonstration, implementation for your organization, or further collaboration, please reach out tim@timlb.eu.

---
*Developed with focus on reliability, speed, and tactical clarity for the heroes on the front lines.*
