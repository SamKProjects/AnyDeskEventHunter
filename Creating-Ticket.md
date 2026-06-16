# 🎫 Freshservice Help Desk Ticket – Computer Frequently Restarts Without Warning

## 📋 Ticket Details

| Field        | Value                        |
|--------------|------------------------------|
| **Title**    | Computer Frequently Restarts Without Warning! |
| **Priority** | Low                          |
| **Status**   | Open                         |
| **Urgency**  | Medium                       |
| **Impact**   | Low                          |
| **Group**    | Help Desk Monitoring Team    |
| **Category** | Hardware / Computer / PC     |

---

## 📝 Ticket Description

> The user's computer randomly restarts without warning. This appears to have happened
> after recent hardware changes to the computer. The computer stays on for 1–3 hours,
> then resets.

---

## 🔒 Private Note

> 🔐 **Private Note (Internal Only)**
>
> Connecting to the user's desktop with AnyDesk to see the issue occurring.

---

## 🛠️ Troubleshooting Steps

### Step 1 – Remote Into User's Desktop
- Connected to the user's machine via **AnyDesk** for remote observation
- Monitored system behavior to confirm the random restart pattern

### Step 2 – Check Windows Event Viewer
- Opened **Event Viewer** → Windows Logs → System
- Identified **Error Code 80** — a memory-related error
- Confirmed the error timestamps align with the reported restart times

### Step 3 – Run Windows Memory Diagnostics
- Opened **Windows Memory Diagnostic** tool
- Scheduled a memory test on next system restart
- Reviewed results for RAM faults or memory corruption

---

## ✅ Outcome

Memory diagnostic results confirmed a hardware memory issue tied to the recent hardware 
changes. Ticket updated with findings and escalated for hardware replacement if needed.

---

## 🧰 Tools Used

![Freshservice](https://img.shields.io/badge/Freshservice-00B388?style=flat&logo=freshworks&logoColor=white)
![AnyDesk](https://img.shields.io/badge/AnyDesk-EF443B?style=flat&logo=anydesk&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)

---

> 💡 *This is a simulated help desk project created to demonstrate real-world IT support 
> skills including ticketing, remote access, event log analysis, and memory diagnostics.*
