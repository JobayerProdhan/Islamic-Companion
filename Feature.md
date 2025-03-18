# Islamic Daily Companion 

## **📌 Features**

### **1️⃣ Salah Timings Section**

- Displays daily prayer timings fetched from an API.
- Highlights the upcoming prayer.
- Allows users to select their city and country for accurate timings.

### **2️⃣ Quranic Ayah of the Day**

- Fetches a random Quranic verse each day.
- Displays the Arabic text with an English translation.
- Users can click "Next Ayah" to fetch another verse.

### **3️⃣ Daily Hadith**

- Displays a hadith from Sahih Bukhari or Muslim.
- Users can cycle through hadiths.

### **4️⃣ Islamic Duas Collection**

- Displays duas for different occasions (morning, evening, travel, eating, etc.).
- Categorized for easy access.

### **5️⃣ Dark Mode Toggle**

- User-friendly theme switcher.
- Default mode based on system preference.

### **6️⃣ Responsive & Minimal UI**

- Designed using Tailwind CSS for smooth responsiveness.
- Works well on mobile and desktop devices.

---

## **🎨 Design Language**

### **🔵 Color Palette**

| Color            | Usage                                | Hex Code  |
| ---------------- | ------------------------------------ | --------- |
| 🟢 Emerald Green | Primary Accent (Buttons, Highlights) | `#047857` |
| 🟡 Golden Sand   | Secondary Accent (Borders, Titles)   | `#D4AF37` |
| ⚫ Deep Black     | Dark Mode Background                 | `#121212` |
| ⚪ Soft White     | Light Mode Background                | `#F9FAFB` |
| 🟢 Mint Green    | Subtle UI Elements                   | `#A7F3D0` |

### **🖋 Typography**

- **Arabic Text:** Noto Naskh Arabic *(for Quran & Hadiths)*
- **English UI & Text:** Poppins / Inter *(for a modern touch)*

### **📜 UI Components**

- **Header & Navigation** (Clean, modern Islamic aesthetic)
- **Card-Based UI** for displaying Quranic Ayahs, Hadiths, and Duas
- **Salah Timings Grid** with highlighted upcoming prayer
- **Dark Mode Toggle** with a Crescent Moon ☪️ icon

---

## **🔗 API Sources**

### **1️⃣ Salah Timings API** *(Aladhan API)*

📌 **Fetch prayer times based on location**\
🔗 API Link: [https://aladhan.com/prayer-times-api](https://aladhan.com/prayer-times-api)\
📌 **Example API Call:**

```url
https://api.aladhan.com/v1/timingsByCity?city=Dhaka&country=Bangladesh&method=2
```

### **2️⃣ Quran API** *(Quran.com API)*

📌 **Get random Quranic verses**\
🔗 API Link: [https://alquran.cloud/api](https://alquran.cloud/api)\
📌 **Example API Call:**

```url
https://api.alquran.cloud/v1/ayah/255
```

### **3️⃣ Hadith API**

📌 **Fetch Hadith from Bukhari, Muslim, etc.**\
🔗 API Link: [https://hadithapi.com/](https://hadithapi.com/)\
📌 **Example API Call:**

```url
https://api.hadith.sutanlab.id/books/muslim/1
```

### **4️⃣ Dua API**

📌 **Get Islamic Duas for daily life**\
🔗 API Link: [https://documenter.getpostman.com/view/8854915/Szf7znEe](https://documenter.getpostman.com/view/8854915/Szf7znEe)\
📌 **Example API Call:**

```url
https://api.sunnah.com/v1/collections/fortyHadith
```

---

## **🚀 Tech Stack**

- **Frontend:** HTML, CSS, Tailwind CSS, JavaScript
- **Framework:** React (for dynamic content fetching)
- **APIs:** Aladhan, Al-Quran Cloud, Hadith API, Sunnah API

---

## **✅ Summary**

This project, **Islamic Daily Companion**, is designed to provide an elegant and interactive Islamic resource for daily use. With a simple yet modern UI, it incorporates **Salah timings, Quranic Ayahs, Hadiths, Duas, and Dark Mode** for an engaging user experience.

Would you like a **React + Tailwind implementation** for this project? 🚀


