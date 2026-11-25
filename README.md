# Awesome IPTV Bangla — বাংলাদেশি IPTV রিসোর্স গাইড

বাংলা IPTV-র জন্য যাচাই করা প্লেলিস্ট, প্লেয়ার, EPG আর টুলস — এক জায়গায়। Built on **iptv-org/awesome-iptv**.

- **Original repo:** https://github.com/iptv-org/awesome-iptv (curated list of IPTV resources — playlists, players, EPG, tools)

## কী আছে / What is inside

- `awesome-bangla.md` — বাংলা IPTV রিসোর্স গাইড: প্লেলিস্ট, প্লেয়ার, EPG, টুলস। প্রতিটি লিংক ২০২৬-১১-২৫ তারিখে curl দিয়ে যাচাই করা (HTTP 200, প্লেলিস্টে `#EXTM3U` আছে)।
- `bangla-starter.m3u` — ছোট স্টার্টার প্লেলিস্ট: ৪টি বাংলাদেশি চ্যানেল, যাদের স্ট্রিম URL আজ আবার যাচাই করা হয়েছে (HTTP 200 + আসল `#EXTM3U` কনটেন্ট)।

## যা ঠিক করা হয়েছে / What was fixed

- আপস্ট্রিম awesome-iptv তালিকায় শত শত লিংক, কিন্তু বাংলাদেশের জন্য কোনো আলাদা গাইড নেই। এই ফাইলে শুধু বাংলা/বাংলাদেশি রিসোর্স — প্লেলিস্ট, প্লেয়ার, EPG।
- পুরনো iptv-org EPG লিংক `https://iptv-org.github.io/epg.xml` এখন **মৃত (HTTP 404)** — ২০২৬-১১-২৫ যাচাই করা। তাই গাইডে ওই লিংক দেওয়া হয়নি; EPG-র জন্য iptv-org/epg রিপো (নিজে grab করার টুল) দেওয়া হয়েছে।
- T Sports বাদ দেওয়া হয়েছে — এর URL HTTP 404 দেয় (২০২৬-১১-২৩ থেকে মৃত)।

## ব্যবহার / How to use

```bash
# VLC-তে স্টার্টার প্লেলিস্ট খুলুন
vlc bangla-starter.m3u

# অথবা mpv-তে
mpv bangla-starter.m3u

# পুরো বাংলাদেশি প্লেলিস্ট (iptv-org, যাচাই করা #EXTM3U)
mpv https://iptv-org.github.io/iptv/countries/bd.m3u
```

বিস্তারিত গাইডের জন্য `awesome-bangla.md` দেখুন।
