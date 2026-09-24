# link_in_bio

An elegant single-page link-in-bio you can host anywhere — one HTML file, no build step, no framework, no account. Edit one JSON object at the bottom of the file and you're done.

**Live demo:** https://p32929.github.io/link_in_bio/

## Screenshots

### Desktop
![Desktop](https://github.com/user-attachments/assets/bf9bad5a-3149-479c-b6d5-364d80d543ad)

### Mobile
![Mobile](https://github.com/user-attachments/assets/985a2f02-5eaf-4ad3-885c-5cf0a1d16fb6)

## Features

- **One file** — `index.html` is the whole site. Drop it on GitHub Pages, Netlify, or any static host.
- **No build, no dependencies** — Tailwind comes from a CDN, everything else is plain JS.
- **All content in one JSON object** — title, tagline, profile image, link categories, social icons.
- **Grouped links** — organise them under category headings instead of one long list.
- **Three ready-made examples** in the repo: `index.html`, `islamic.html` and `cacheline.html`.

## How to use it

1. Download `index.html` (or one of the other two, if you prefer their look)
2. Open it in any editor and find the `jsonData` object near the bottom
3. Change `pageTitle`, `headerTitle`, `headerTagline`, `profileImage`, then fill in `categories` with your own links
4. Upload the file to any static host — that's the whole deploy

```js
const jsonData = {
  pageTitle: "Your Name",
  headerTitle: "Your Name",
  headerTagline: "What you do",
  profileImage: "https://example.com/you.png",
  categories: [
    {
      title: "Socials",
      links: [
        { title: "Instagram", url: "https://instagram.com/you", icon: "https://.../icon.png" },
      ],
    },
  ],
};
```

## License

MIT License — Copyright (c) Fayaz Bin Salam. See [LICENSE](LICENSE) for the full text.

## Contributing

Contributions are warmly welcomed and greatly appreciated! Whether it's a bug fix, new feature, or improvement, your input helps make this project better for everyone.

Before submitting a pull request, please:

1. Create an issue describing the feature or bug fix you'd like to work on
2. Wait for discussion and approval to ensure alignment with project goals
3. Fork the repository and create your feature branch
4. Submit your pull request with a clear description of changes

This approach helps avoid duplicate efforts and ensures smooth collaboration. Thank you for considering contributing!

## Share

Sharing this repository with your friends is just one click away from here

[![facebook](https://user-images.githubusercontent.com/6418354/179013321-ac1d1452-0689-493f-9066-940cf2302b6e.png)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/p32929/link_in_bio/)
[![twitter](https://user-images.githubusercontent.com/6418354/179013351-7d8d6d1c-4ce2-46ab-bef8-4c4765a1b888.png)](https://twitter.com/intent/tweet?url=https://github.com/p32929/link_in_bio/)
[![tumblr](https://user-images.githubusercontent.com/6418354/179013343-3111f55a-3b90-40c7-8487-9777348672b0.png)](https://www.tumblr.com/share?v=3&u=https://github.com/p32929/link_in_bio/)
[![pocket](https://user-images.githubusercontent.com/6418354/179013334-b095c45f-becf-49f4-9ee1-5a731a9b1f85.png)](https://getpocket.com/save?url=https://github.com/p32929/link_in_bio/)
[![pinterest](https://user-images.githubusercontent.com/6418354/179013331-44cd9206-11b1-4b65-becb-5863b61c828f.png)](https://pinterest.com/pin/create/button/?url=https://github.com/p32929/link_in_bio/)
[![reddit](https://user-images.githubusercontent.com/6418354/179013338-7416ae3f-73ba-4522-86e1-1374d7082d22.png)](https://www.reddit.com/submit?url=https://github.com/p32929/link_in_bio/)
[![linkedin](https://user-images.githubusercontent.com/6418354/179013327-ca7b7102-1da8-4b1c-858f-1a6e5f21bd70.png)](https://www.linkedin.com/shareArticle?mini=true&url=https://github.com/p32929/link_in_bio/)
[![whatsapp](https://user-images.githubusercontent.com/6418354/179013353-f477fa0b-3e6f-4138-a357-c9991b23ff88.png)](https://api.whatsapp.com/send?text=https://github.com/p32929/link_in_bio/)

## Support

[![buymeacoffee](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg)](https://www.buymeacoffee.com/p32929)

<!-- hire-block -->

---

## 💼 Using this at a company?

I do fixed-price delivery work on my own projects. One invoice, one date, no hourly billing:

| | |
|---|---|
| **White-label build** — this project rebranded, extended and deployed as yours | **$6,500** · 3 weeks |
| **Custom app from scratch** on my own stack, signed and auto-updating | **$12,500** · 6 weeks |
| **Production-hardening sprint** — 72 hours on this project, for your load and your security review | **$999** |
| **Ongoing capacity** — one project-week of my time reserved every month | **$9,000 / month** |

Full details → **[p32929.github.io/hire](https://p32929.github.io/hire/)** · Email **[fayazbinsalam@uberip.com](mailto:fayazbinsalam@uberip.com)** — scoping and quotes are free and I answer within one business day.
