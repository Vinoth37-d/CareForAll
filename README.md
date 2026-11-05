# CareForAll - Complete Senior Healthcare Platform

An elder-friendly, bilingual (**Tamil + English**) medicine reminder and tracking web application designed specifically for senior citizens and family caregivers.

![CareForAll Design](styles.css)

---

## 🌐 Full Website Navigation (6 Interactive Views)

1. **Home (`Home`):** Welcoming landing page explaining the mission, interactive live morning dose card preview, and feature highlights.
2. **Dashboard (`Dashboard`):** Full **Medicine Tracker** matching your reference design:
   * **KPI Status Bar:** `04 Today's Medicines` | `02 Acknowledged` | `02 Upcoming` | `00 Missed`
   * **Active Due Banner:** Highlighted alert when a dose is due right now with voice instructions and confirmation.
   * **Tabs:** `Today (pending)` | `Morning` | `Afternoon` | `Night` | `All Medicines`
   * **Medicine Cards:** Dosage, tablet count, meal instructions in English & Tamil, purple time badges (`🕒 11:05:00`), date range badges (`📅 1/15/2026 - 1/22/2026`), and `🔊 Listen` + `✓ Mark Taken` actions.
3. **Voice Assistant (`Assistant`):** Interactive voice console with pulsing glowing sphere:
   * *"What is my next medicine?"* (எனது அடுத்த மருந்து என்ன?)
   * *"Read all today's medicines"* (இன்றைய அட்டவணையை படி)
   * *"Did I take morning medicine?"* (காலை மருந்து சாப்பிட்டேனா?)
   * *"Test voice & chime"* (குரல் மற்றும் ஒலி சோதனை)
4. **Caregiver Hub (`Caregiver Hub`):** Multi-senior profile management:
   * Switch between elderly family members (*Grandpa Ramasamy*, *Grandma Lakshmi*).
   * Register new seniors with age, health condition, and emergency contact.
   * One-click phone calling (`tel:`) and WhatsApp notification messages.
   * Medical data backup: Download JSON export and restore.
5. **Calendar & Reports (`Calendar & Reports`):**
   * Full monthly calendar matrix. Click any day to view scheduled prescriptions and taken status.
   * 92% Compliance score & 5-day perfect streak.
6. **Healthcare Plans (`Plans`):** Transparent pricing options (Senior Citizen Essential - Free, Family Caregiver Plus - Pro, Elder Home & Assisted Care).

---

## 🎙️ Bilingual Voice Reminders (தமிழ் & English)
* Powered by browser-native **Web Speech API** (`speechSynthesis`).
* Calibrated to **0.85 speech rate** (slower, clear, and easy for senior citizens to comprehend).
* Natural Tamil and English phrases include medicine name, dosage, tablet count, and meal relations.

---

## 🔔 Chimes & Notifications
* **Web Audio API:** Synthesizes a soothing two-tone hospital/reminder chime (works completely offline).
* **Browser Notifications API:** Native desktop notifications when a dose is due.

---

## 🚀 How to Open and Run

Because this is built with clean, modern **HTML5, CSS3, and JavaScript**:
* **Direct Run:** Double-click [`index.html`](file:///c:/Users/sures/OneDrive/Documents/CAREFORALL/index.html) in your browser.
* **Local Server (Optional):**
  ```powershell
  python -m http.server 8080
  ```
  Then visit `http://localhost:8080`.
