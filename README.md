# 7DC — 7TV Discord Bridge (User-Installable App)

This started as a simple idea: bringing the 7TV Twitch emote experience - escpecially wide-Emotes - to Discord.
7DC is a **User-Installable Application**, meaning it is tied to your Discord account and works across DMs, Group Chats, and Servers without requiring a bot in each one.

# <img src="https://cdn.7tv.app/emote/01G96X3198000E1TFQ6V2HEJW7/4x.avif" width="48" height="41" alt="emoji">  Early Access

7DC is currently in **Early Access** 

Access is currently limited to gather usage data, test server stability under load and predict future infrastructure. It also allows features and workflows to be refined based on community feedback, helping make the application as stable, reliable, and user-friendly as possible before a wider release.

To request access, add me on Discord | @0pzi.

While the app is fully functional, you may occasionally encounter bugs, unexpected behavior, or temporary limitations. 
[Feedback](https://github.com/0PZI/7DC-Public/issues) from testers is greatly appreciated and helps shape the future of 7DC.

# <img src="https://cdn.7tv.app/emote/01FPCZ99CR000EJT2EVEY3K7J8/4x.avif" width="48" height="49" alt="emoji">  Features

* **Use Everywhere:** Thanks to Discord's "User Install" feature, your emotes follow you globally.
* **7TV Sync:** Directly pulls from your current active 7TV emote set.
* **Fast Autocomplete:** Search for emotes instantly via the Discord command UI.
* **Smart Caching:** Uses an in-memory cache for emote sets to ensure lightning-fast responses and minimal API load.

# <img src="https://cdn.7tv.app/emote/01HVWN8E1G0003S49WDMY4KNHN/4x.avif" width="48" height="49" alt="emoji">  How to Use

1. Link your Discord Account to your [7TV Profile](https://7tv.app/settings)
2. [Add 7DC to your Discord Profile](https://discord.com/oauth2/authorize?client_id=1513755393682313467)
3. Use the Commands below to get started sending Emotes or configure your experience

# <img src="https://cdn.7tv.app/emote/01FBZESCNR000A6AWCB1X558GZ/4x.avif" width="48" height="49" alt="emoji">  Commands

* `/emote [name]` | `/e [name]` — Search and send an Emote from your active Emote-set
* `/size [small/medium/large]` — Change your default Emote preview size `default=small`

# <img src="https://cdn.7tv.app/emote/01FB4NYBG0000FFZEHGR5A0DYS/4x.avif" width="48" height="49" alt="emoji">  Performance & Caching

The app is optimized for speed:

* **Instant Search:** Your 7TV emote list is cached in-memory for 30 minutes. This ensures that when you type a name, the suggestions appear instantly without waiting for an API response.
* **Efficient API Usage:** Caching prevents unnecessary requests to 7TV's servers, keeping the integration smooth and stable.

# <img src="https://cdn.7tv.app/emote/01JQHGR6R8705W0TX7MC5CGAE7/4x.avif" width="48" height="49" alt="emoji"> Data & Privacy

7DC is designed with a "privacy-first" approach:

* **No Private Data:** The application **does not** collect or store passwords, emails, or private messages.
* **Public IDs Only:** To function, the app only maps your **Discord User ID** to your **7TV User ID**. Both of these are public identifiers that are already available on your public profiles.
* **No Tracking:** Your emote usage is not tracked, stored, or logged. The app simply acts as a bridge to display your own 7TV collection.

# <img src="https://cdn.7tv.app/emote/01G6ZS6QDR0003EG3F712GQ2C8/4x.avif" width="48" height="49" alt="emoji"> Limitations 

* **Emote previews are not possible:** Discord (e.g.) renders emoji previews client-sided, while slash commands only support plain text choices and cannot display emotes, images, or other content.

---

## 🔗 Links

[7TV](https://7tv.app) • [Discord Terms & Guidelines](https://discord.com/guidelines) • [Install 7DC](https://discord.com/oauth2/authorize?client_id=1513755393682313467)


## 🧾 Notes

* 7dc is not affiliated with, nor endorsed by 7tv
* emotes remain property of their respective creators on 7tv
* users are responsible for ensuring proper use according to discord guidelines and 7tv rules
* this project follows discord developer policies
