## 📱 Donation App Prototype – Intern Dashboard (Round 1 Task)

A **basic Flutter UI prototype** for an intern fundraising dashboard. This app simulates a portal where fundraising interns can track their progress, view leaderboards, and read announcements — all using mock data.

> ⚠️ This project is UI-only. No backend or database integration is included.

---

## 🏗️ Features Implemented

### 📌 Screens Built:

1. **Login / Sign-Up Page**  
   - Static UI for user entry (no authentication logic)

2. **Dashboard Page**  
   - 👤 Intern Name display  
   - 🔐 Dummy Referral Code (e.g., `soumaditya2025`)  
   - 💰 Total Donations Raised (e.g., `₹5,000`)  
   - 🏆 Rewards/Unlockables (static cards/icons)

3. **Leaderboard Page**  
   - Simple list of **5 mock interns** with donation scores  
   - Clean list UI design

4. **Announcements Page**  
   - Static content simulating updates or messages

---

## 🧪 Bonus Features (Optional Enhancements)

- ✅ Smooth UI transitions  
- ✅ Responsive layout for different devices  
- ✅ Clean UI design using Google Fonts  
- ✅ Mock state management (without backend)  
- ⏳ Potential to store mock data via local JSON  

---

## 📦 Dependencies Used

```yaml
dependencies:
  flutter:
    sdk: flutter
  google_fonts: ^6.1.0
  flutter_bloc: ^8.1.3  # (if used)
