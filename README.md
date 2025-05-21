# 🧪 AutoCare QA Test Report – Tanjinur Islam

This is a comprehensive Software Quality Assurance (SQA) test assignment conducted for the AutoCare platform. It covers the website (https://autocare.com.bd) and the Android app (AutoCare – available on Google Play Store).

## 🧭 Objective

To evaluate the usability, functionality, and reliability of the AutoCare platform through exploratory and structured testing. The goal was to identify critical bugs, usability issues, and opportunities for improvement.

---

## 🔍 Product Summary

**AutoCare** is a Bangladeshi digital platform for automotive services and parts. It allows users to:
- Book car and bike services online
- Buy vehicle parts and accessories
- Access blogs, news, and automotive insights
- Allow vendors to register and manage their online automotive businesses

**Target Users:**  
Car and bike owners, auto repair/service seekers, parts buyers, and vehicle-related business vendors in Bangladesh.

---

## ✅ Functional Test Scenarios (18)

| Scenario ID | Module | Description |
|-------------|--------|-------------|
| FS01 | User Registration | Verify registration with valid input creates a user account |
| FS02 | User Login | Verify registered users can log in with correct credentials |
| FS03 | Password Recovery | Verify user can recover passwords using "forgot password" |
| FS04 | Product Search | Verify search bar returns relevant results |
| FS05 | Product Filtering | Verify filters by category, brand, price work correctly |
| FS06 | Add to Cart | Verify user can add products to the cart |
| FS07 | Remove from Cart | Verify user can remove products from the cart |
| FS08 | Checkout Process | Verify order placement with valid payment & shipping info |
| FS09 | Order History | Verify users can view past orders with status |
| FS10 | Profile Update | Verify user can update name, email, and contact info |
| FS11 | Service Booking | Verify user can schedule services with time/date |
| FS12 | Vendor Registration | Verify vendors can register and set up shop |
| FS13 | Vendor Dashboard Access | Verify vendors can manage their dashboard |
| FS14 | Cross-language Behavior | Verify Bangla-English toggle works correctly |
| FS15 | Blog Navigation | Verify blog and news sections load properly |
| FS16 | Button Placement | Verify CTA buttons are placed logically |
| FS17 | Button Functionality | Verify buttons trigger correct actions |
| FS18 | Button Responsiveness | Verify buttons work across screen sizes |

---

## 🧪 Test Cases (13 Examples)

Each test case includes:
- **Test Case ID**
- **Test Steps**
- **Input Data**
- **Expected Result**
- **Actual Result**

Examples:
- TC01: User Registration
- TC02: User Login
- TC03: Password Recovery
- TC04: Product Search
- TC08: Checkout Process
- TC11: Service Booking

✅ Most test cases passed successfully.

---

## 🐞 Bug Reports (21 Bugs)

Each bug includes:
- Bug ID
- Title
- Bug Type (UI, Functional, Security, etc.)
- Severity Level
- Steps to Reproduce
- Expected vs Actual Behavior

Examples:
- BUG01: Twitter icon not updated to "X"
- BUG03: Weak password like "1234" is accepted
- BUG05: Order placed even after failed payment
- BUG07: Can log in after registration without setting password
- BUG21: Unrealistic member count on About Us page

🧷 Severity Levels: High (8), Medium (7), Low (6)

---

## 🎯 Usability / UX Observations (16)

Highlighted areas that impact the user journey, especially for new users.

Examples:
- Double search bars create confusion
- Homepage lacks visual appeal
- No clear “Client Feedback” section
- Labels like “Multivendor” are unclear
- Touch elements cramped on mobile
- Inconsistent phrasing: “Sign UP” vs “Login”

💡 Each observation is paired with a recommendation for improvement.

---

## 🌐 Cross-Browser / Cross-Platform Observations (5)

Tested on:
- Desktop browser (Chrome, Firefox)
- Mobile browser
- Minimized desktop views

Findings:
- Layout breaks in minimized view
- Loading delays across all browsers
- Password/Mobile fields split on multiple screens
- Homepage not fully responsive
- Touch targets too close on mobile

🛠️ Suggestions included for responsive design and spacing improvements.

---

## 🛠️ Tools Used

- **Google Sheets** – Test documentation
- **Chrome, Firefox** – Web testing
- **Android App** – Mobile testing
- **Device** – Xiaomi Redmi 12

---

## 📎 Summary

This QA project allowed me to apply real-world testing skills across platforms, find critical bugs, and suggest usability improvements.  
It strengthened my functional testing, UX evaluation, and cross-platform QA experience.

---

## 👤 Author

**Tanjinur Islam**  
