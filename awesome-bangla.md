# Awesome IPTV Bangla — যাচাই করা রিসোর্স গাইড

সব লিংক ২০২৬-১১-২৫ তারিখে curl দিয়ে যাচাই করা। যেটা যাচাই করা যায়নি, সেটা এখানে নেই।

## প্লেলিস্ট (iptv-org — সবগুলোতে `#EXTM3U` আছে)

| প্লেলিস্ট | লিংক | যাচাই |
|---|---|---|
| বাংলাদেশ (সব চ্যানেল) | https://iptv-org.github.io/iptv/countries/bd.m3u | HTTP 200, `#EXTM3U` আছে |
| বাংলা ভাষা (সব দেশ) | https://iptv-org.github.io/iptv/languages/ben.m3u | HTTP 200, `#EXTM3U` আছে |
| বিশ্ব সংবাদ | https://iptv-org.github.io/iptv/categories/news.m3u | HTTP 200, `#EXTM3U` আছে |
| বিশ্ব খেলা | https://iptv-org.github.io/iptv/categories/sports.m3u | HTTP 200, `#EXTM3U` আছে |
| পুরো iptv-org সূচি | https://iptv-org.github.io/iptv/index.m3u | HTTP 200, `#EXTM3U` আছে (২৩,৯২১ লাইন) |

## iptv-org রিপো (GitHub)

- প্লেলিস্ট সংগ্রহ: https://github.com/iptv-org/iptv — HTTP 200
- EPG টুল (নিজে গাইড grab করার জন্য): https://github.com/iptv-org/epg — HTTP 200
- চ্যানেল ডেটাবেস: https://github.com/iptv-org/database — HTTP 200
- রিসোর্স তালিকা (original): https://github.com/iptv-org/awesome-iptv — HTTP 200

## EPG — সতর্কতা

পুরনো লিংক `https://iptv-org.github.io/epg.xml` এখন **মৃত — HTTP 404** (২০২৬-১১-২৫ যাচাই)। iptv-org এখন আর একটিমাত্র প্রকাশিত `epg.xml` দেয় না; EPG পেতে হলে iptv-org/epg রিপোর টুল দিয়ে নিজে grab করতে হয়। তাই এখানে ওই মৃত লিংক দেওয়া হয়নি।

## প্লেয়ার (যাচাই করা)

- VLC — https://www.videolan.org/vlc/ — HTTP 200। m3u/m3u8 সরাসরি খোলে, Windows/Mac/Linux/Android সবখানে চলে।
- mpv — https://mpv.io/ — HTTP 200। হালকা কমান্ড-লাইন প্লেয়ার, `mpv <playlist-url>` দিলেই চলে।

## স্টার্টার প্লেলিস্ট

`bangla-starter.m3u` ফাইলে ৪টি চ্যানেল আছে — Bangla Vision, Boishakhi TV, Ekushey TV, NTV — যাদের স্ট্রিম URL ২০২৬-১১-২৫ তারিখে আবার যাচাই করা হয়েছে (HTTP 200 + আসল `#EXTM3U` কনটেন্ট)।

## কী বাদ দেওয়া হয়েছে

- **T Sports** — URL HTTP 404 দেয়, তাই বাদ। (২০২৬-১১-২৩ থেকে মৃত)
- Kodi (https://kodi.tv/) — এই মেশিন থেকে curl-এ সাড়া দেয়নি (HTTP 000), তাই লিংক দেওয়া হয়নি। Kodi নিজে বৈধ প্লেয়ার, কিন্তু এই রাউন্ডে যাচাই করা যায়নি।
