# Status Report Webpage Content (Editable)

> **Instructions:** Edit the text and image paths below. I will sync these changes to the live website.

## Header
**Title:** Shubble Android Audit
**Subtitle:** Prepared for Daniella Louw
**Date:** Status Report • May 21, 2024

---

## Executive Summary
We have performed a "Basics-Check" on the Android version of the Shubble app and identified several critical issues that need immediate attention. Additionally, the iOS build remains blocked due to an Apple ID payment issue.

---

## 1. Android Basics-Check Findings

### 🚨 Critical Issues (Must Fix)
**Missing Age Gate:** There is currently NO age verification logic in the app. While there is a date picker, it does not verify if the user is 18+.

*   **T&Cs Checkbox:** The text is not clickable, making it hard to select.
*   **Inconsistent Errors:** Messages lack professional capitalization (e.g., "please select your birthdate").
*   **Typos:** "Nexts" button on startup screen.

![Nexts Typo](assets/nexts_typo.png)

### 🛑 Booking Flow Analysis
**Critical UI Failure:** The "Book Now" button is pushed below the fold, making it unclickable on many devices.

![Booking UI Issues](assets/uploaded_image_1764632090827.png)

**Features to Retain:** Despite the UI issues, the logic for Pickup Time, Special Instructions, and Extras is solid and will be kept in the new version.

---

## 2. UI/UX Overhaul Needed
We identified specific areas where the visual design falls short of the premium standard we are aiming for.

### App Icon
**Problem:** Low resolution and dated.
**Solution:** Design a new, high-res icon that reflects safety and family.
![Current App Icon](assets/current_app_icon.png)

### Phone Number Input
**Problem:** Hard to read, no country code formatting.
**Solution:** Implement standard input with flag selector.
![Phone Input UX](assets/phone_input_ux.png)

### Onboarding Navigation
**Problem:** Tiny "Skip/Next" buttons placed inconsistently.
**Solution:** Large, sticky footer buttons.
![Onboarding Navigation](assets/onboarding_navigation_ux.png)

### Date Picker
**Problem:** Clunky calendar requires too many taps for birth year.
**Solution:** Modern scroll-wheel picker.
![Date Picker](assets/default_date_picker.png)

### Location Selection
**Problem:** Dragging a pin is inaccurate.
**Solution:** Add "Search Bar" (Google Places) for instant address selection.
![Location Selection](assets/current_location_selection_ux.png)

---

## 3. iOS Status: BLOCKED
**ACTION REQUIRED:**
The Apple Developer enrollment is paused. We require the password for `daniellalouw81@gmail.com` to complete the $99 payment. iOS testing is blocked until this is resolved.

We cannot proceed with iPhone testing until this is resolved.

---

## 4. Strategic Recommendation
**December On-Site Sprint (Somerset West)**
Leverage the upcoming December visit for a dedicated 2-week on-site sprint.
Goal: Separate and rigorously refine the Rider and Driver apps side-by-side with the operations team.

[BUTTON: Approve Strategy]

---

## Footer
Shubble Vision Prototype • Confidential
