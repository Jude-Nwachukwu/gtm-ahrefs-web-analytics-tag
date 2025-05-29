# Ahrefs Web Analytics GTM Tag Template (Unofficial)

This is an unofficial [Google Tag Manager (GTM)](https://tagmanager.google.com/) custom **tag template** for integrating [Ahrefs Web Analytics](https://ahrefs.com/web-analytics). It allows you to easily install the Ahrefs tracking script and fire custom analytics events — all without writing code.

> Developed by **Jude Nwachukwu Onyejekwe** from [DumbData](https://dumbdata.co)  
> Licensed under the **Apache License 2.0**

---

## 🚀 What This Template Can Do

- ✅ Install the official Ahrefs analytics script dynamically **🚨 This feature is currently unavailable due to the limitations of how GTM custom templates work and the structure of the Ahrefs installation script (attribute).**
- ✅ Track custom events with `AhrefsAnalytics.sendEvent('eventName')`
- ✅ Enable/disable console logging (great for debugging!)

---

## 📥 How to Import This Template in GTM

1. Download or copy the `.tpl` file (available in the `dist/` folder if provided).
2. Open **Google Tag Manager**.
3. Go to **Templates** > **Tag Templates**.
4. Click **New** → select the vertical three-dot menu → **Import**.
5. Choose the `.tpl` file and confirm the import.
6. Save and publish your changes.

---

## ⚙️ How to Configure the Tag

When adding this tag to a GTM container:

1. **Select Tag Type**
   - `Install Tracking Script`: Injects the Ahrefs analytics.js script.
   - `Track Event`: Sends a custom event using Ahrefs's event tracking API.

**IGNORE IMPLEMENTING THE AHREFS SCRIPT USING THIS TAG TEMPLATE**

2. **Fields Based on Tag Type**
   - If **Install Tracking Script** is selected:
     - Enter your **Data Key** from Ahrefs.
   - If **Track Event** is selected:
     - Enter your custom **Event Name**.

3. **Optional Configuration**
   - Enable the checkbox **Disable Console Logging** to suppress console messages during execution.

---

## 📄 License
Apache License 2.0

---

## 💡 Need Help?

If you run into issues, feel free to open an issue or contact [DumbData](https://dumbdata.co) for guidance.

---
