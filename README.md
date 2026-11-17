# link_in_bio

A free, good-looking link-in-bio page that you own. Link-in-bio services want an account, show their branding and charge for the nice features. This is one HTML file instead: no build step, no framework, no account and no fees. Edit one JSON object at the bottom of the file, put it on any static host, and you are done.

**Live demo:** https://p32929.github.io/link_in_bio/

## Screenshots

### Desktop
![Desktop](https://github.com/user-attachments/assets/bf9bad5a-3149-479c-b6d5-364d80d543ad)

### Mobile
![Mobile](https://github.com/user-attachments/assets/985a2f02-5eaf-4ad3-885c-5cf0a1d16fb6)

## Features

1. **One file** — `index.html` is the whole site. Drop it on GitHub Pages, Netlify, or any static host.
2. **No build step** — Tailwind loads from a CDN, everything else is plain JS.
3. **All content in one JSON object** — title, tagline, profile image, link categories, social icons.
4. **Grouped links** — organise them under category headings instead of one long list.
5. **Three ready-made examples** in the repo: `index.html`, `islamic.html` and `cacheline.html`.

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

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit. Thanks for helping make link_in_bio better.

<p><a href="https://p32929.github.io/share/?repo=link_in_bio"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
