# Assignment #3 — Responsive Web Design

**Name:** Abitay Ainaz
**Group:** IT-2502

## Parts Completed

### Part 1 — Media Queries
#### Task 0 — Responsive Typography
**Description:**
A simple webpage containing a heading (`<h1>`), subheading (`<h2>`), and a paragraph (`<p>`).
CSS media queries are used to change the font sizes depending on the screen size:

- **Mobile (default, < 768px):** `h1 = 20px`, `h2 = 16px`, `p = 12px`
- **Tablet (≥ 768px):** `h1 = 32px`, `h2 = 24px`, `p = 16px`
- **Desktop (≥ 1024px):** `h1 = 48px`, `h2 = 36px`, `p = 24px`

The page also uses `meta viewport` for proper scaling on mobile devices and a light gray 
background for readability.

Screenshot:
<img width="656" height="724" alt="image" src="https://github.com/user-attachments/assets/a8997bcf-aeb0-4fc9-8993-9d726c532426" />

#### Task 1 — Responsive Layout with Media Queries
**Description:**
A webpage with **three colored boxes** arranged in a row. The layout changes
depending on the screen size using **only CSS media queries** (no Bootstrap):

- **Mobile (< 768px):** boxes are **stacked vertically** (1 per row, full width).
- **Tablet (≥ 768px):** **two boxes per row**, third wraps to a new row.
- **Desktop (≥ 1024px):** all **three boxes side by side** (3 equal columns).

Font sizes also adjust at each breakpoint to keep the design readable.
Screenshot:
<img width="472" height="541" alt="image" src="https://github.com/user-attachments/assets/e181148f-0147-408a-b988-3dac834a303b" />
<img width="606" height="110" alt="image" src="https://github.com/user-attachments/assets/33fcb985-5169-4608-8780-0c05dc757773" />

### Part 2 — Bootstrap Grid System
#### Task 2 — Bootstrap Responsive Columns
**Description:**
Build a responsive layout using **Bootstrap's 12-column grid**:

- **Mobile:** `col-12` wins → each column is full width.
- **Tablet (≥ 768px):** `col-md-6` overrides → 2 columns per row.
- **Desktop (≥ 992px):** `col-lg-4` overrides → 3 equal columns (12 ÷ 4 = 3).

Bootstrap automatically handles the wrapping, spacing (`gutter`), and
stacking — no custom media queries needed.
Screenshot:
<img width="705" height="509" alt="image" src="https://github.com/user-attachments/assets/f93267a2-104b-4785-9927-032a94fa2686" />


#### Task 3 — Bootstrap Navigation Bar
**Description:** 
Created a **responsive navbar** with Bootstrap:
- Logo on the left (`.navbar-brand`)
- Links on the right (`.ms-auto` → Home / About / Services / Contact)
- Collapses into a **hamburger menu** on screens < 992px
- Uses Bootstrap JS bundle for the collapse toggle behavior

Screenshot:
<img width="695" height="517" alt="image" src="https://github.com/user-attachments/assets/8bb752be-b505-4741-bbc4-c6e54fb0f625" />

### Part 3 — Combined Project

#### Task 4 — Responsive Portfolio Page
**Description:** 
Portfolio page combining **Media Queries** and **Bootstrap Grid**.

**Structure:**
1. **Header** — Bootstrap navbar (logo + links + hamburger)
2. **Main section** divided into two parts:
   - **Left (`col-lg-8`)** — Projects arranged in a nested grid of cards
     (`col-12 col-md-6` → 2 cards per row on desktop/tablet).
   - **Right (`col-lg-4`)** — Sidebar with avatar, name, contact info, and skills badges.
3. **Footer** — full-width dark footer across the bottom.

- **Bootstrap grid:** `col-lg-8` (projects) + `col-lg-4` (sidebar), cards use `col-md-6`
- **Media queries:** custom breakpoints at 768px / 1024px for font sizes, sidebar, footer, and card hover
**How the layout works:**

```
Container
└── Row (12 columns)
    ├── col-lg-8   → Projects (nested row with cards)
    └── col-lg-4   → Sidebar
```

- **Desktop (≥ 992px):** `8 + 4 = 12` → projects left, sidebar right 
- **Tablet (≥ 768px):** cards in 2 columns, sidebar moves below (full width)
- **Mobile:** everything stacked in one column

Screenshot:
<img width="740" height="782" alt="image" src="https://github.com/user-attachments/assets/c3c37ce3-006e-4ae4-a472-e82478c7d2ac" />
<img width="740" height="759" alt="image" src="https://github.com/user-attachments/assets/7c97a764-8a38-427b-8903-1c4ae7194865" />
<img width="807" height="144" alt="image" src="https://github.com/user-attachments/assets/fcfaa050-403e-434c-ac23-95fe5ac94953" />
<img width="552" height="594" alt="image" src="https://github.com/user-attachments/assets/10992aa3-94e8-43fa-90d8-91be56d370ef" />

## Summary
In this assignment I learned how to build responsive web pages using CSS media queries
and the Bootstrap 12-column grid. I created separate example files for each task and
combined everything into a portfolio page. The main challenges were managing breakpoints
consistently and making the navbar collapse correctly on small screens.

# https://jkooked.github.io/webka-assik3/ 
