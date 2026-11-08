# প্রাইভেট শুক্রাণু ডোনার বাংলাদেশ

প্রাথমিক তথ্য ও যোগাযোগের ওয়েবসাইট। আবেদনকারীদের তথ্য Supabase-এর `contact_requests` টেবিলে জমা হয়।

## প্রকাশ (GitHub Pages)
1. GitHub repository খুলুন: https://github.com/rakibulislam05050-debug/private-donor-bangladesh
2. Settings → Pages
3. Build and deployment → Deploy from a branch
4. Branch: main এবং folder: /(root) নির্বাচন করে Save চাপুন
5. কিছুক্ষণ পর Pages-এ দেখানো ওয়েব ঠিকানাটি খুলে পরীক্ষা করুন।

## নিরাপত্তা ও সীমাবদ্ধতা
- ফ্রন্টএন্ডে কেবল Supabase anon/public key ব্যবহার করা হয়েছে; service_role key নয়।
- ডাটাবেসে Row Level Security চালু। জনসাধারণ শুধু সম্মতিসহ আবেদন জমা দিতে পারে; তালিকা পড়তে পারে না।
- এই সংস্করণে অ্যাডমিন প্যানেল, ইমেইল নোটিফিকেশন, ছবি আপলোড বা PDF রসিদ তৈরি নেই।
- এই সাইট চিকিৎসা/ক্লিনিক নয় এবং দাতা-গ্রহীতার সরাসরি মিল বা চিকিৎসা প্রক্রিয়া পরিচালনা করে না।
- Google-এ দেখা যেতে সময় লাগতে পারে; indexing নিশ্চিত নয়।
