# 7DC — 7TV Discord Bridge (User-Installable App)

7DC started as a simple idea: bringing the 7TV Twitch emote experience into Discord.

7TV emotes are heavily shaped by Twitch culture, but Discord doesn't really support them in a native or consistent way—especially wide emotes (1:2 or 1:3). 7DC bridges that gap by letting you use your own 7TV emote set directly inside Discord with proper formatting and scaling.

7DC is a **User-Installable Application**, meaning it is tied to your Discord account and works across DMs, Group Chats, and Servers without requiring a bot in each one.

## 🚧 Early Access

7DC is currently in **Early Access**.

Access is currently limited to a selected group of users. Additional access may be granted over time depending on available capacity and server resources. In some cases, early access is distributed through direct requests.

To request access, follow me on [Twitter (@sl0pzi)](https://twitter.com/sl0pzi) and send a DM

This phase helps gather real-world usage data, test stability under load, and better predict future infrastructure and server costs as the user base grows. It also allows features and workflows to be refined based on community feedback, helping make the application as stable, reliable, and user-friendly as possible before a wider release.

While the app is fully functional, you may occasionally encounter bugs, unexpected behavior, or temporary limitations. [Feedback](https://github.com/0PZI/7DC-Public/issues) from testers is greatly appreciated and helps shape the future of 7DC.

## 🚀 Features

* **Use Everywhere:** Thanks to Discord's "User Install" feature, your emotes follow you globally.
* **7TV Sync:** Directly pulls from your current active 7TV emote set.
* **Fast Autocomplete:** Search for emotes instantly via the Discord command UI.
* **Smart Caching:** Uses an in-memory cache for emote sets to ensure lightning-fast responses and minimal API load.

## 🛠 Commands

* `/connect [7tv_id]` — Link your Discord account to your 7TV profile (Use your 7TV Object ID from your profile URL). **Your Discord account must already be connected to 7TV!!!**
* `/emote [name]` — Search and send an emote from your active set (delivered in 2x scale with autocomplete).

## 🧭 Setup — Finding Your 7TV ID
* ![7TV ID Location](./assets/7TV_ID.png)

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

Simply install the app to your Discord profile via the [application link](https://discord.com/oauth2/authorize?client_id=1513755393682313467). Once authorized, you can use the commands above in any text channel you have access to.

---

## 🔗 Links

[7TV](https://7tv.app) • [Discord Terms & Guidelines](https://discord.com/guidelines) • [Install App](https://discord.com/oauth2/authorize?client_id=1513755393682313467)

---

## 🧾 Notes

* emotes remain property of their respective creators on 7tv
* users are responsible for ensuring proper use according to discord guidelines and 7tv rules
* this project follows discord developer policies
