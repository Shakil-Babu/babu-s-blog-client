---
title: "বাইনারি সার্চ (Binary search)"
date: 'september 04 2021'
author: 'Shakil Babu'
cover_image: "/images/scopeandlexical.png"
desc: "অবশ্যই অ্যালগরিদম বা প্রোগ্রামে স্পেস কমপ্লিক্সিটি(complexity)ও গুরুত্বপূর্ণ বিষয় । কোনো অ্যালগরিদম বা প্রোগ্রাম ঠিক কতটুকু জায়গা বা মেমরি নিলো তাকেই স্পেস কমপ্লিক্সিটি(complexity) বলে।"
category: 'dsa'
---
কম্পিউটার সাইন্সে (Computer Science) কিছু কমন অ্যালগরিদম গুলোর মধ্যে বাইনারি সার্চ (Binary search) অন্যতম। এটি খুবই সহজ একটি অ্যালগরিদম যা লিনিয়ার সার্চের থেকে অনেক দ্রুত কাজ করে । তবে বাইনারি সার্চ (Binary search) ইমপ্লিমেন্ট করার আগে মাথায় রাখতে হবে অবশ্যই অ্যারেটা যেন সর্টেড(Sorted) থাকে অর্থাৎ ছোট থেকে বড় ক্রমে সাজানো থাকতে হবে। যদি অ্যারে সর্টেড(Sorted) না থাকে তাহলে আগে সর্টেড(Sorted) করে নিতে হবে তারপর বাইনারি সার্চ চালাতে হবে ।


## বাইনারি সার্চ (Binary search) কিভাবে কাজ করে ?
কোনো একটা অ্যারে থেকে স্পেসিফিক আইটেম সার্চ করার সময় অ্যারেটা দুই ভাগে ভাগ করে মাঝের আইটেম বাঁ উপাদানকে টার্গেট করা হয় যদি মাঝের আইটেমটি কাঙ্ক্ষিত সার্চ আইটেম নাহ হয় তাহলে 