# 2FA Market - Android APK Source & Build Guide
======================================================

এই প্রজেক্টটি **https://2famarket.afac.store/** ওয়েবসাইটটিকে একটি সম্পূর্ণ নেটিভ Android APK অ্যাপ হিসেবে বিল্ড করার জন্য প্রস্তুত করা হয়েছে।

### প্রজেক্ট কনফিগারেশন:
- **App Name:** 2FA Market
- **Package Name:** store.afac.twofamarket
- **Target URL:** https://2famarket.afac.store/
- **Version:** 1.0.0 (Build 1)
- **Min SDK:** Android 5.0 (API 21)
- **Target SDK:** Android 14 (API 34)
- **Special Features:** 
  - WhatsApp Admin Deep-linking (8801939219493)
  - Swipe to Refresh (টেনে রিলোড)
  - Dark Mode Cyber Theme
  - Offline Safety Banner
  - Full Cookie/Session Storage

---

## 🚀 এপিকে (APK) তৈরি করার সহজ উপায় (৩টি পদ্ধতি)

### পদ্ধতি ১: মোবাইল ক্রোম দিয়ে সরাসরি ১-ক্লিকে ইনস্টল (Recommended & Easiest)
1. আপনার অ্যান্ড্রয়েড মোবাইলে Google Chrome ব্রাউজার দিয়ে এই অ্যাপ্লিকেশনে প্রবেশ করুন।
2. ব্রাউজারের উপরে ডানদিকের ৩-ডটে (⋮) চাপ দিন।
3. **"Install App"** বা **"Add to Home screen"** চাপুন।
4. কয়েক সেকেন্ডের মধ্যে গুগল প্লে সার্ভিসের মাধ্যমে সরাসরি একটি অফিশিয়াল WebAPK ইনস্টল হয়ে যাবে। কোনো জটিলতা নেই!

### পদ্ধতি ২: Android Studio দিয়ে সরাসরি সাইন করা .apk ফাইল তৈরি
1. জিপ ফাইলটি আনজিপ করুন।
2. **Android Studio** ওপেন করুন এবং **"Open an Existing Project"** সিলেক্ট করে আনজিপ করা ফোল্ডারটি নির্বাচন করুন।
3. গ্রেডল সিঙ্ক শেষ হওয়া পর্যন্ত অপেক্ষা করুন (১-২ মিনিট)।
4. উপরের মেন্যু থেকে **Build > Build Bundle(s) / APK(s) > Build APK(s)** চাপুন।
5. বিল্ড শেষ হলে নিচে "locate" বাটনে ক্লিক করলে আপনার তৈরি করা **app-debug.apk** ফাইলটি পেয়ে যাবেন!
6. ফাইলটি আপনার অ্যান্ড্রয়েড ফোনে নিয়ে ইনস্টল করে নিন।

### পদ্ধতি ৩: অনলাইন ক্লাউড বিল্ডার (কম্পিউটার ছাড়াও)
- **WebToApp / AppsGeyser / Hermit:** সরাসরি URL `https://2famarket.afac.store/` দিয়ে তাৎক্ষণিক APK ডাউনলোড করতে পারেন।

---
Developed for 2FA Market Community.
