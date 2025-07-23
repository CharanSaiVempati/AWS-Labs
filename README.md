# AWS-Labs
# ☁️ Cloud Technet - AWS Lab Practice Portal

A web-based portal for accessing AWS lab credentials and managing session time accurately across multiple users using synchronized lab slot logic.

---

## 📁 Project Structure

- `index.html` – Main portal page showing AWS console link, credentials, and a live countdown timer.
- `thankyou.html` – Redirect page shown after session expiry with refresh checking logic.
- `aws_logo_image.png` – AWS logo used for branding.

---

## 🔧 Key Features

- ✅ Live countdown timer based on fixed lab slot (not user's access time).
- ✅ Copy buttons with **blinking animation** effect for feedback.
- ✅ "Session Expired" button shown after countdown ends.
- ✅ Refresh logic in `thankyou.html` to detect updated lab links.
- ✅ Instructions section with proper **Do's and Don’ts**.
- ✅ Responsive and mobile-friendly layout.

---

## 🕒 Lab Slot Timing

Each lab day includes **3 slots**:

| Slot | Time          | Duration |
|------|---------------|----------|
| 1    | 10:00 AM      | 3 hours  |
| 2    | 01:30 PM      | 3 hours  |
| 3    | 05:00 PM      | 3 hours  |

- The lab session countdown starts **from the beginning of the current slot**, not when a user opens the page.
- Timer continues even if the user reloads or opens in a different browser.

---

## 🚫 Do's & Don'ts

### ✅ Do:
- Follow the timer. It’s synchronized globally.
- Use provided credentials only during valid slot time.

### ❌ Don’t:
- Do not refresh the page to reset the timer.
- Avoid opening the page in multiple browsers.
- Do not try to manipulate the timer with scripts or extensions.

---

## ⚙️ Technologies Used

- HTML5
- CSS3 (with animations)
- Vanilla JavaScript

---

## 📸 Screenshot

![Portal Logo](aws_logo_image.png)

---

## 📩 Support

If you have issues or suggestions, contact your training coordinator or system administrator.
