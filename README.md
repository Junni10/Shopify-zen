# Zen Curry Express — Shopify Theme

## Setup Instructions

### 1. Upload This Theme
In your Shopify admin: Online Store → Themes → Add theme → Upload zip file.

### 2. Upload All Images to Assets
Go to: Online Store → Themes → (your theme) → Edit code → Assets → Add a new asset

Upload each image from your original site with these **exact filenames** (spaces replaced with hyphens):

#### From /Images/ folder:
| Original Filename               | Upload As                        |
|---------------------------------|----------------------------------|
| Zen curry awning.png            | Zen-curry-awning.png             |
| Zen Curry.png                   | Zen-Curry.png                    |
| Zen curry banner 1.png          | Zen-curry-banner-1.png           |
| Zen curry banner 2.png          | Zen-curry-banner-2.png           |
| Zen curry banner 3.png          | Zen-curry-banner-3.png           |
| Curry House front.webp          | Curry-House-front.webp           |
| What we serve-01.png            | What-we-serve-01.png             |
| What we serve-02.png            | What-we-serve-02.png             |
| What we serve-03.png            | What-we-serve-03.png             |
| Socials-01.png                  | Socials-01.png                   |
| Socials-02.png                  | Socials-02.png                   |
| socials.png                     | socials.png                      |
| socials-08.png                  | socials-08.png                   |
| socials-09.png                  | socials-09.png                   |
| footer socials-03.png           | footer-socials-03.png            |
| footer socials-04.png           | footer-socials-04.png            |
| footer-socials.png              | footer-socials.png               |
| footer socials-06.png           | footer-socials-06.png            |
| footer-01.png                   | footer-01.png                    |
| Front door.png                  | Front-door.png                   |
| contact-10.png                  | contact-10.png                   |
| contact-11.png                  | contact-11.png                   |
| contact-12.png                  | contact-12.png                   |
| contact-13.png                  | contact-13.png                   |

#### Menu item images (from root of original project):
| Original Filename               | Upload As                        |
|---------------------------------|----------------------------------|
| hamburger-15.png                | hamburger-15.png                 |
| hamburger-14.png                | hamburger-14.png                 |
| Original.png                    | Original.png                     |
| Chicken Katsu.png               | Chicken-Katsu.png                |
| Pork Katsu.png                  | Pork-Katsu.png                   |
| Croquette.png                   | Croquette.png                    |
| Fried Shrimp.png                | Fried-Shrimp.png                 |
| Kurobuta Sausage.png            | Kurobuta-Sausage.png             |
| Beef.png                        | Beef.png                         |
| Spam Katsu.png                  | Spam-Katsu.png                   |
| Meatloaf.png                    | Meatloaf.png                     |
| Spinach.png                     | Spinach.png                      |
| Vegatable.png                   | Vegatable.png                    |
| Tofu Katsu.png                  | Tofu-Katsu.png                   |
| Grilled Chicken.png             | Grilled-Chicken.png              |
| Calamari.png                    | Calamari.png                     |
| Sauteed Chicken.png             | Sauteed-Chicken.png              |
| Chicken Karaage.png             | Chicken-Karaage.png              |
| Chicken Tender.png              | Chicken-Tender.png               |
| Curry Udon.png                  | Curry-Udon.png                   |
| Karaage Bowl.png                | Karaage-Bowl.png                 |
| Katsudon.png                    | Katsudon.png                     |
| Yakiudon.png                    | Yakiudon.png                     |
| Yakisoba.png                    | Yakisoba.png                     |
| Gyoza.png                       | Gyoza.png                        |
| Karaage.png                     | Karaage.png                      |
| Shumai.png                      | Shumai.png                       |
| Chiken Katsu Salad.png          | Chiken-Katsu-Salad.png           |
| Takoyaki.png                    | Takoyaki.png                     |
| Oyster.png                      | Oyster.png                       |
| Edamame.png                     | Edamame.png                      |
| Tofu Salad.png                  | Tofu-Salad.png                   |
| Reg Salad.png                   | Reg-Salad.png                    |
| Curry Fries.png                 | Curry-Fries.png                  |
| Fries.png                       | Fries.png                        |

### 3. Create Pages in Shopify
Go to: Online Store → Pages → Add page

Create two pages:
- Title: **Menu** → Template: `page.menu`
- Title: **Contact** → Template: `page.contact`

### 4. Configure Theme Settings
Go to: Online Store → Themes → Customize

- Set Order Online URL, Instagram URL, Facebook URL in Header & Announcement Bar sections
- Update phone, address, hours in the Footer section

### 5. Theme Structure Overview
```
zen-curry-theme/
├── assets/          ← base.css + all uploaded images go here
├── config/          ← theme settings
├── layout/
│   └── theme.liquid ← master shell (nav + footer wrap every page)
├── sections/        ← all page content blocks
├── templates/       ← index.json, page.menu.json, page.contact.json
└── locales/         ← translations
```
