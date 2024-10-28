লার্ন উইথ সুমিত এর প্রথম এসাইনমেন্ট এর আপনাকে স্বাগতম। এই মডিউলে যা যা দেখানো হয়েছে, তার উপর ভিত্তি করে আপনাদের জন্যে একটি এসাইনমেন্ট তৈরি করা হয়েছে। এই এসাইনমেন্ট এর জন্য আমরা HTML এবং Tailwind CSS ব্যবহার করে একটি template তৈরি করে দিয়েছি। আপনাদের কাজ হবে এই template ব্যবহার করে এসাইনমেন্ট করা। ***এই এসাইনমেন্ট এ আপনি নিজের ইচ্ছা মত ডিজাইন বা টেমপ্লেট পরিবর্তন করতে পারবেন না এবং আপনাকে এই মডিউলে যা যা শেখানো হয়েছে, শুধু মাত্র সেগুলো ব্যবহার করেই Vite & React দিয়ে প্রোজেক্টটি করতে হবে । অন্যথায় আপনার মার্ক এর উপর প্রভাব পড়তে পারে ।***

## এসাইনমেন্ট এ আপনাকে যা যা করতে হবেঃ

✓ পুরো এসাইনমেন্ট টেমপ্লেটটিকে রিয়্যাক্ট এ কনভার্ট করতে হবে । কনভার্ট করার সময় আপনার লজিকাল সেন্স এপ্লাই করতে হবে। কোন সেকশনকে কতটুকু কম্পোনেন্টে ভাঙবেন, সেটা আপনার কমন সেন্স থেকে আপনাকে সিদ্ধান্ত নিতে হবে। পুরো টেম্পলেটটিকে একটি রিয়্যাক্ট কম্পোনেন্টে রেখে দেয়ার মতো অযৌক্তিক কাজ করলে মার্ক স্বাভাবিকভাবেই পাবেন না। তাই যতটা সুন্দর করে কম্পোনেন্ট কম্পোজ করতে পারবেন ততোই ভাল মার্ক পাবেন।

✓ পুরো কোডে বিভিন্ন SVG রয়েছে, সেগুলোকে আলাদা ভাবে কম্পোনেন্ট এ রূপান্তর করে ব্যবহার করতে হবে। অর্থাৎ সারাসরি SVG ব্যবহার করতে পারবেন না। আপনাকে প্রথমে সেই SVG এর একটি কম্পোনেন্ট বানিয়ে নিতে হবে, এর পরে সেটি ব্যবহার করতে হবে ।

✓ আমাদের দেয়া টেমপ্লেটে "Grab your Dream Property" নামক একটি সেকশন রয়েছে। আপনাকে সেই সেকশন এর গ্রিড ভিউ তে বিভিন্ন Property এর তথ্য কার্ড আকারে রেন্ডার করতে হবে । বর্তমানে সেখানে ৫টি কার্ড আছে, প্রত্যেকটিতে একই ছবি এবং ডেটা দেয়া আছে। আপনাকে প্রত্যকটিতে আলাদা আলাদা ডেটা দিয়ে কার্ড গুলো রেন্ডার করতে হবে। আপনি চাইলে ৫ টির বেশি কার্ড ও রেন্ডার করতে পারেন। তবে প্রত্যেকটিতে অবশ্যই আলাদা আলাদা ডেটা এবং ছবি ব্যবহার করতে হবে ।

✓ কার্ড রেন্ডার করার জন্যে আপনাকে নিজেকে একটি Array of Object বানিয়ে নিতে হবে। আপনাকে সেই Array কে Map করে কার্ড গুলো রেন্ডার করতে হবে । কার্ডের তথ্য গুলো সঠিক হতে হবে এমন কোনো কথা নেই, তবে সেগুলো একেবারেই যেন অপ্রাসঙ্গিক না হয়।

✓ মোবাইল ভিউ তে যেন পুরো ওয়েবসাইট রেস্পন্সিভ হয়।

## কিভাবে সাবমিট করবেন:

সবচেয়ে সহজে বুঝার জন্য [এই ভিডিওটি](https://learnwithsumit.com/rnext/courses/rnext/how-to-submit-assignments-in-reactive-accelerator-course) দেখে ফেলুন।

**এসাইনমেন্টে আপনাকে মাত্র দুইটা জিনিস সাবমিট করতে হবে:**

1. **GitHub private repository link:** অবশ্যই সঠিক গিটহাব রিপোজিটরি লিংক দিতে হবে। ভুলে অন্য কোনো লিংক দিলে আপনি এসাইনমেন্টের মার্ক পাবেন না। তাই সাবমিট করার আগে নিউ ট্যাবে লিংক ওপেন করে চেক করে নিবেন সঠিক লিংক জমা দিচ্ছেন কিনা। আরেকটি বিষয় খুবই গুরুত্বপূর্ণ। আপনার প্রজেক্টে কোন এনভায়রনমেন্ট ফাইল যেমন .env অথবা .env.local থাকলে সেগুলোতে থাকা ইনফর্মেশন যদি আপনার প্রজেক্টটি কাজ করার জন্য প্রয়োজনীয় হয়, তাহলে সেগুলো অবশ্যই আপনার .gitignore ফাইল থেকে সরিয়ে নিবেন যেন আমরা সেটি দেখতে পাই। কারণ এসাইনমেন্ট রিভিউ করার সময় আমরা আপনার প্রজেক্টটি রান করে দেখবো। তাই রান করার জন্য প্রয়োজনীয় সকল ফাইল আমরা যেন দেখতে পাই, সেটা আপনাকে নিশ্চিত হতে হবে।
2. **Live site link:** নেটলিফাইতে বা ভার্সেলে সাইট হোস্ট করে সাইটের লাইভ লিংক দিতে হবে। তবে এর বাইরে অন্য কোন হোস্টিং প্রভাইডারেও আপনি চাইলে হোস্ট করতে পারে। তবে সেক্ষেত্রে আপনার হোস্টিং রিলেটেড সমস্যা নিজেকে সল্ভ করতে হবে এবং সব কিছু ঠিক মতো কাজ করতে হবে। ভুলে অন্য কোনো লিংক দিলে আপনি এসাইনমেন্টের মার্ক পাবেন না। তাই সাবমিট করার আগে নিউ ট্যাবে লিংক ওপেন করে চেক করে নিবেন সঠিক লিংক জমা দিচ্ছেন কিনা। ভার্সেলে কি ভাবে হোস্ট করতে হয় তা আপনি না জানলে [এইখানে ক্লিক](https://learnwithsumit.com/rnext/courses/rnext/how-to-deploy-your-project-to-vercel-free) করে দেখে নিতে পারেন।

**সাবমিট একবারই করতে পারবেন তাই ভালো করে দেখে সাবমিট করবেন।**

## GitHub private repository কিভাবে তৈরি করবেন:

Github Private repositoty তৈরি করতে [এইখানে ক্লিক করুন](https://classroom.github.com/a/1_bcpBMy) অথবা ব্রাউজারে এই লিংকে **https://classroom.github.com/a/1_bcpBMy** ভিজিট করুন। লিংকে যাওয়ার পরে **Accept this assignment** এ ক্লিক করুন। সর্বোচ্চ ১মিনিট পরে পেইজটি রিলোড দিলে আপনি আপনার রিপোজেটরি লিংক পেয়ে যাবেন। মনে রাখবেন, আপনাকে এই লিংকটি আমাদের প্লাটফর্মে সাবমিট করতে হবে। না বুঝলে উপরে বলা ভিডিও টিউটোরিয়ালটি দেখে নিন।

## Assignment এর জন্য প্রয়োজনীয় template HTML:

প্রতিটি assignment এর সাথে প্রয়োজনীয় HTML template আমরা দিয়ে দিয়েছি যেন আপনাকে HTML template নিয়ে সময় নষ্ট না করতে হয়। কোর্সের GitHub repository এর সংশ্লিষ্ট ব্রাঞ্চে গেলেই আপনারা **'dist'** folder এর ভিতর HTML template পাবেন। না বুঝলে [এইখানে ক্লিক](https://learnwithsumit.com/rnext/courses/rnext/how-to-submit-assignments-in-reactive-accelerator-course) করে টিউটোরিয়াল দেখে নিতে পারেন।

## এসাইনমেন্ট মার্কস পলিসি:

আপনি নির্ধারিত সময়ে এসাইনমেন্ট জমা দিলে এবং সব কিছু সঠিকভাবে করলে সম্পূর্ণ মার্ক পাবেন। এর পরে জমা দিলে আপনার মার্ক নিচের নিয়মে কাটা যাবে -

1. ডেডলাইনের পরে এক ঘণ্টার মধ্যে জমা দিলে 10% মার্ক কাটা যাবে।
2. ডেডলাইনের পরে এক ঘণ্টার বেশি কিন্তু 24 ঘণ্টার মধ্যে জমা দিলে 30% মার্ক কাটা যাবে।
3. ডেডলাইনের পরে 24 ঘণ্টার বেশি পরে জমা দিলে 50% মার্ক কাটা যাবে।
4. কোর্স ডিউরেশনের পরে আমরা এসাইনমেন্ট গ্রহণ করবো না।

অবশ্যই কোর্স চলাকালিন সময়ে এসাইনমেন্ট জমা দিতে হবে। কোর্সের ডিউরেশন শেষ হয়ে গেলে তার পরে আপনি এসাইনমেন্টে জমা দিলে এসাইনমেন্টের মার্ক পাবেন না।

## সাবমিট করার পর কোড পরিবর্তন:

আপনি ভেবে নিতে পারেন আপনি ওয়েবসাইটে সঠিক সময়ে এসাইনমেন্ট সাবমিট করে নীরবে পরে গিটহাবে কোড পুশ করতে থাকবেন! আপনার গিটহাবের সর্বশেষ কমিট দেখলেই আমরা বুঝতে পারবো আপনি কখন কোড আপডেট করেছেন। সে অনুযায়ী আমরা আপনার মার্ক কেটে নিবো। তাই এসাইনমেন্ট এর সময় পার হবার পরে আমরা আশা করবো আপনি চালাকি করে আর কোড পুশ করবেন না আপনার রিপোজিটরিতে। এটা করলে আপনার সম্পূর্ণ মার্ক কাটা যেতে পারে।

## এসাইনমেন্ট মার্কস কবে পাবেন:

আমরা সর্বোচ্চ ১৫ কার্যদিবসের ভিতরে এসাইনমেন্টের মার্ক দিয়ে দেওয়ার চেষ্টা করবো। ক্ষেত্র বিশেষে একটু দেরি হতে পারে কারো কারো মার্ক পেতে।
#   S m a l l - R e a l - E s t a t e - W e b s i t e - L a n d i n g - P a g e - H T M L 
 