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
<img width="766" height="536" alt="AnyDeskConnection" src="https://github.com/user-attachments/assets/91d9091b-3b2f-49c6-bb3f-f5cc38231530" />

### Step 2 – Check Windows Event Viewer
- Opened **Event Viewer** → Windows Logs → System
- Identified **Error Code 80** — a memory-related error
- Confirmed the error timestamps align with the reported restart times
<img width="1004" height="550" alt="BugCheckCode80" src="https://github.com/user-attachments/assets/2772ead2-28c6-4b2d-91dc-954b0381b391" />


### Step 3 – Run Windows Memory Diagnostics
- Opened **Windows Memory Diagnostic** tool
- Scheduled a memory test on next system restart
- Reviewed results for RAM faults or memory corruption
<img width="999" height="754" alt="Windows Memory Diagnostic" src="https://github.com/user-attachments/assets/9132d0e0-4e8a-4cf9-8be7-6c94d37665fa" />

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
