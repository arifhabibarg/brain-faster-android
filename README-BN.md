# Brain Faster Android APK

এই প্রজেক্টটি আপনার দেওয়া ওয়েবসাইটকে Android WebView অ্যাপে চালায়।

## অ্যাপের তথ্য
- নাম: Brain Faster
- আইকন: আপনার দেওয়া লোগো
- ওয়েব অ্যাপ: https://ais-dev-gaiv3bsjwsalyph4fjafgq-477147497474.asia-southeast1.run.app/

## APK তৈরি (GitHub Actions দিয়ে)
1. ZIP ফাইলটি Extract করুন।
2. GitHub-এ নতুন একটি repository তৈরি করুন (যেমন `brain-faster-android`)।
3. এই ফোল্ডারের সব ফাইল repository-তে upload করে `main` branch-এ commit করুন।
4. Repository-র **Actions** tab খুলুন।
5. `Build Brain Faster APK` workflow শেষ হলে run-টি খুলুন।
6. নিচের **Artifacts** থেকে `Brain-Faster-APK` ডাউনলোড করুন।
7. ZIP extract করে `app-debug.apk` Android ফোনে install করুন।

## গুরুত্বপূর্ণ
- এটি WebView wrapper; ওয়েবসাইটের নিজস্ব লগইন, সার্ভার ও ইন্টারনেট সংযোগের ওপর নির্ভর করবে।
- প্রথমবার খোলার সময় ওয়েবসাইটের Google/security login বা cookie flow আবার আসতে পারে।
- Debug APK পরীক্ষার জন্য। Play Store-এ প্রকাশ করতে হলে আলাদা signed release build ও privacy/policy প্রস্তুতি দরকার।
