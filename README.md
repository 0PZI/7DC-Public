# 7DC — 7TV Discord Bridge (User-Installable App)

7DC is a modern Discord integration that brings your favorite 7TV emotes to every corner of Discord. Unlike traditional bots, this is a **User-Installable Application**, meaning it stays with your profile and works in DMs, Group Chats, and any server—even if the bot isn't invited there.

## 🚧 Early Access

7DC is currently in **Early Access**.

This phase helps gather real-world usage data, test stability under load, and better predict future infrastructure and server costs as the user base grows. It also allows features and workflows to be refined based on community feedback, helping make the application as stable, reliable, and user-friendly as possible before a wider release.

While the app is fully functional, you may occasionally encounter bugs, unexpected behavior, or temporary limitations. Feedback from testers is greatly appreciated and helps shape the future of 7DC.

## 🚀 Features

* **Use Everywhere:** Thanks to Discord's "User Install" feature, your emotes follow you globally.
* **7TV Sync:** Directly pulls from your current active 7TV emote set.
* **Fast Autocomplete:** Search for emotes instantly via the Discord command UI.
* **Smart Caching:** Uses an in-memory cache for emote sets to ensure lightning-fast responses and minimal API load.

## 🛠 Commands

* `/connect [7tv_id]` — Link your Discord account to your 7TV profile (Use your 7TV Object ID from your profile URL).
* `/emote [name]` — Search and send an emote from your active set (delivered in 2x scale).

## ⚡ Performance & Caching

The app is optimized for speed:

* **Instant Search:** Your 7TV emote list is cached in-memory for 10 minutes. This ensures that when you type a name, the suggestions appear instantly without waiting for an API response.
* **Efficient API Usage:** Caching prevents unnecessary requests to 7TV's servers, keeping the integration smooth and stable.

## 🛡 Data & Privacy

7DC is designed with a "privacy-first" approach:

* **No Private Data:** The application **does not** collect or store passwords, emails, or private messages.
* **Public IDs Only:** To function, the app only maps your **Discord User ID** to your **7TV User ID**. Both of these are public identifiers that are already available on your public profiles.
* **No Tracking:** Your emote usage is not tracked, stored, or logged. The app simply acts as a bridge to display your own 7TV collection.

## ⚙️ How to Use

Simply install the app to your Discord profile via the application link. Once authorized, you can use the commands above in any text channel you have access to.

---

*All rights for emotes belong to their respective creators on 7TV.app.*
