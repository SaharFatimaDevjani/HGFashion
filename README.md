# HG Fashions

A static, multi-page HTML website for **HG Fashions**, a fashion store catalog covering Women, Men, and Kids collections. Built with plain HTML — no CSS framework, build tools, or backend involved.

> "Success is not final; failure is not fatal: It is the courage to continue that counts."

**Live site:** https://saharfatimadevjani.github.io/HGFashion/

## Overview

The site is a browsable product catalog / brochure site. The home page (`index.html`) links out to category pages for each department, showcases an "Azaadi Sale" pricing table, embeds background audio, and includes social media links plus contact information.

## Structure

```
HGFashion/
├── index.html              # Home page: navigation, sale table, contact & social links
├── images/                  # Home page assets (logo, banners, sale images, map)
├── audio/                   # Background audio (azaadpakistan.mp3)
└── fashion/
    ├── women/
    │   ├── bags.html
    │   ├── clothing.html
    │   ├── shoes.html
    │   ├── jewellery.html
    │   ├── cosmetics.html
    │   ├── images2/          # Product images for women's pages
    │   └── videoswomen/      # Product videos
    ├── men/
    │   ├── easternwear.html
    │   ├── westernwear.html
    │   ├── shoes.html
    │   ├── accessories.html
    │   ├── images3/          # Product images for men's pages
    │   └── videosmen/        # Product videos
    └── kids/
        ├── boysclothing.html
        ├── boysshoes.html
        ├── girlsclothing.html
        ├── girlsshoes.html
        ├── toys.html
        ├── images4/           # Product images for kids' pages
        └── videoskids/        # Product videos
```

## Pages

| Department | Categories |
|---|---|
| **Women** | Bags, Clothing, Shoes, Jewellery, Cosmetics |
| **Men** | Eastern Wear, Western Wear, Shoes, Accessories |
| **Kids** | Boys Clothing, Boys Shoes, Girls Clothing, Girls Shoes, Toys |

## Running Locally

No build step is required — it's plain HTML/CSS/media files. Just open `index.html` in a browser, or serve the folder with any static file server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Contact

Contact details, phone numbers, and social media links are available in the footer of `index.html`.
