# Saimum.org - Coming Soon Landing Page

সাইমুম-এর জন্য একটি আধুনিক ও প্রিমিয়াম "Coming Soon" ল্যান্ডিং পেজ।

## 📁 ফোল্ডার ও ফাইল স্ট্রাকচার:
```text
saimum.org-coming-soon/
├── index.html                 # মূল ল্যান্ডিং পেজ
├── README.md                  # ডিপ্লয়মেন্ট গাইড
└── assets/
    ├── css/
    │   └── style.css          # গ্লাস-মরফিজম ও ডার্ক মোড ডিজাইন
    ├── js/
    │   └── script.js          # লাইভ কাউন্টডাউন ও পার্টিকেল এফেক্ট
    └── images/
        ├── logo.png           # সাইমুম-এর অফিসিয়াল লোগো
        └── favicon.svg        # ভেক্টর সাইট আইকন
```

---

## 🚀 Cloudflare Pages-এ ডিপ্লয় করার সহজ ধাপ (Option 1 - Direct Upload):

1. **Cloudflare Dashboard-এ যান:**
   - ব্রাউজারে [dash.cloudflare.com](https://dash.cloudflare.com) ওপেন করুন।
   
2. **Workers & Pages সেকশনে যান:**
   - বাম পাশের মেনু থেকে **Compute (Workers & Pages)** > **Pages**-এ যান।
   - **Create application** বাটনে ক্লিক করে **Pages** সিলেক্ট করুন।
   - **Upload assets** অপশনটি নির্বাচন করুন।

3. **প্রজেক্ট নাম ও ফাইল আপলোড:**
   - প্রজেক্টের একটি নাম দিন (যেমন: `saimum-coming-soon`)।
   - আপনার কম্পিউটারের এই ফোল্ডারটি (`e:\Saiful\Programming\saimum.org-coming-soon`) সিলেক্ট করুন অথবা এর ভেতরের ফাইলগুলো ড্র্যাগ করে ড্রপবক্সে ছেড়ে দিন।
   - **Deploy site** বাটনে ক্লিক করুন। কয়েক সেকেন্ডেই পেজটি লাইভ হয়ে যাবে এবং একটি `*.pages.dev` লিংক পাবেন।

4. **saimum.org কাস্টম ডোমেইন কানেক্ট করা:**
   - ডিপ্লয় শেষে প্রজেক্টের **Custom domains** ট্যাবে যান।
   - **Set up a custom domain**-এ ক্লিক করে আপনার ডোমেইন `saimum.org` (এবং চাইলে `www.saimum.org`) লিখুন।
   - যেহেতু ডোমেইনটি ইতোমধ্যে আপনার Cloudflare অ্যাকাউন্টে যুক্ত আছে, Cloudflare স্বয়ংক্রিয়ভাবে DNS রেকর্ড সেট করে দেবে!
   - ব্যাস! আপনার ডোমেইনে সুন্দর "Coming Soon" পেজটি সাথে সাথে সক্রিয় হয়ে যাবে।
