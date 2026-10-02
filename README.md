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
Screenshot:
![Task 2](screenshots/task2.png)

#### Task 3 — Bootstrap Navigation Bar
Screenshot:
![Task 3](screenshots/task3.png)

### Part 3 — Combined Project
#### Task 4 — Responsive Portfolio Page
Screenshot:
![Task 4](screenshots/task4.png)

## Summary
In this assignment I learned how to build responsive web pages using CSS media queries
and the Bootstrap 12-column grid. I created separate example files for each task and
combined everything into a portfolio page. The main challenges were managing breakpoints
consistently and making the navbar collapse correctly on small screens.

## Resources Used
- Bootstrap 5.3 documentation
- W3Schools — CSS Media Queries
- MDN — Responsive Design
