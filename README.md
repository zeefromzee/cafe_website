# The Gathering Place

> *"Start your day with a book, art, or just a coffee."*

A community-oriented café web experience designed for readers, artists, gamers, and creatives to discover the space, explore the menu, and participate in interest-based clubs.

**Live Site:** [the-gathering-place.vercel.app](https://the-gathering-place.vercel.app)

---

## Table of Contents

- [About](#about)
- [Pages and Features](#pages-and-features)
- [Clubs](#clubs)
- [Menu Highlights](#menu-highlights)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## About

The Gathering Place is a multi-page static website serving as the digital presence of the Cozy Cafe Club, a community hub founded on the principles of creativity, inclusivity, and meaningful human connection. The platform gives visitors a structured way to acquaint themselves with the café's philosophy, navigate its offerings, and become active participants in its growing network of interest-based communities.

The site is deployed on [Vercel](https://vercel.com) and requires no backend infrastructure, making it lightweight, fast, and straightforward to maintain or extend.

---

## Pages and Features

| Page | Description |
|---|---|
| **Home** | Hero landing section with a welcoming introduction and a call-to-action directing visitors to the club catalogue |
| **Menu** | A comprehensive listing of all food and beverage offerings, organized by category |
| **Clubs** | A catalogue of active community clubs, each displaying membership count, meeting schedule, skill level, and a join prompt |
| **About** | An articulation of the café's mission, foundational values, and the benefits of club membership |
| **Contact** | A contact form and relevant details for reaching the team |

Additional interface features include a responsive navigation bar with a mobile hamburger toggle and a consistent visual language maintained across all pages.

---

## Clubs

The site currently presents six active clubs, each meeting on a recurring weekly schedule and welcoming members across a range of experience levels.

| Club | Focus Area | Meeting Schedule | Members |
|---|---|---|---|
| The Book Nook Club | Literary discussion and reading | Tuesdays, 6:00 PM | 124 |
| The Gaming Guild | Casual and competitive gaming | Thursdays, 7:00 PM | 98 |
| The Creative Canvas | Visual art, photography, and creative work | Saturdays, 5:00 PM | 87 |
| Coffee and Conversations | Open discussion and casual networking | Sundays, 4:00 PM | 156 |
| The Baking Circle | Baking, recipe exchange, and community events | Fridays, 6:30 PM | 73 |
| The Heart Journal Circle | Reflective journaling for well-being and creativity | Wednesdays, 6:15 PM | 64 |

Visitors who cannot find a suitable match are invited to submit a proposal through the **Suggest a New Club** feature on the Clubs page.

---

## Menu Highlights

The café menu is organized into five distinct categories, each reflecting the establishment's commitment to quality and comfort.

**Hot Drinks** -- Espresso, Americano, Latte, Cappuccino, Flat White, Macchiato, Hot Chocolate, and Herbal Tea

**Cold Drinks** -- Cold Brew, Iced Latte, Iced Coffee, Smoothies, Milkshakes, and Iced Tea

**Snacks and Light Bites** -- Croissants, Muffins, Scones, Avocado Toast, and assorted spreads

**Sandwiches and Wraps** -- Grilled Cheese, Turkey and Avocado, Caprese, and Hummus and Veggie Wrap

**Desserts and Sweets** -- Brownies, New York-style Cheesecake, Tiramisu, Cinnamon Rolls, and Macarons

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure and markup |
| CSS3 | Visual styling, layout, and responsive behaviour |
| JavaScript | Client-side interactivity, including navigation toggling |
| Vercel | Static hosting and continuous deployment |

---

## Getting Started

To run the project in a local development environment, follow the steps below.

**1. Clone the repository**
```bash
git clone https://github.com/your-username/the-gathering-place.git
cd the-gathering-place
```

**2. Serve the project locally**

As a static site, the project can be opened directly in any browser. For a more reliable development experience, a local server is recommended.

```bash
# Using the Python built-in server
python -m http.server 8000
# Then navigate to http://localhost:8000
```

Alternatively, the VS Code **Live Server** extension can be used by right-clicking `index.html` and selecting "Open with Live Server."

**3. Deploy to Vercel**

```bash
npm install -g vercel
vercel
```

---

## Project Structure

```
the-gathering-place/
├── index.html          # Root entry point
├── home.html           # Home page
├── Menu.html           # Full menu listing
├── CLUBS.html          # Club catalogue
├── About.html          # About the community
├── contact.html        # Contact page
├── styles/             # CSS stylesheets
├── scripts/            # JavaScript files
└── assets/             # Images and media assets
```

---

## Contributing

Contributions that align with the project's inclusive and creative ethos are welcome. To propose changes, please follow the standard fork-and-pull-request workflow outlined below.

1. Fork the repository
2. Create a dedicated feature branch: `git checkout -b feature/your-feature-name`
3. Commit changes with a descriptive message: `git commit -m "Add: description of change"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request against the main branch for review

---

## License

This project is open source and distributed under the [MIT License](LICENSE).

---

<div align="center">
Built with care and community spirit &nbsp;·&nbsp; <a href="https://the-gathering-place.vercel.app">Visit the live site</a>
</div>
