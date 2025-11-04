# Responsive Front-End Framework Project

This project demonstrates the use of **two popular front-end frameworks** — **Bulma** and **Bootstrap** — to design a **responsive web layout**.  
It includes:
1. A **responsive card component** created using **Bulma**.
2. A **responsive grid layout** implemented using **Bootstrap**.

---

## 📂 Project Structure

/project-folder
│
├── index.html # Main HTML file with Bulma and Bootstrap
├── style.css # Custom CSS file for styling
└── README.md # Documentation file

yaml
Copy code

---

## 🚀 Features

### 🔹 Bulma Section (Responsive Card)
- Uses the **Bulma CSS framework**.
- Displays a **responsive card** with:
  - Image
  - Title and subtitle
  - Description content
  - Date/time information
- Automatically adjusts to screen sizes (mobile-first design).

### 🔹 Bootstrap Section (Responsive Grid)
- Uses the **Bootstrap grid system** (`row`, `col-12`, `col-md-6`, `col-lg-4`).
- Creates a **3-column responsive layout**:
  - On large screens: 3 cards per row
  - On medium screens: 2 cards per row
  - On small screens: 1 card per row
- Each card contains:
  - Image
  - Title
  - Description

---

## 🧠 Technologies Used

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure of the webpage |
| **CSS3** | Custom styling |
| **Bulma** | Responsive card design |
| **Bootstrap 5** | Responsive grid layout |
| **Google Fonts (Poppins)** | Clean, modern typography |

---

## 💻 How to Run the Project

1. **Download or clone** the project folder.  
   ```bash
   git clone https://github.com/yourusername/frontend-framework-project.git
Open the folder and locate the file:

diff
Copy code
index.html
Double-click the file or open it in your browser.

You’ll see:

A Bulma-based responsive card at the top.

A Bootstrap-based responsive grid layout below.

## 📄 File Explanation
index.html
Imports Bulma and Bootstrap frameworks via CDN.

Contains two sections:

Bulma Section: A card showing image, text, and description.

Bootstrap Section: A grid with 3 responsive cards.

Includes a custom header and footer.

style.css
Provides additional custom styling:

Page background and font setup.

Header and footer colors.

Card alignment and margins.

## 📱 Responsiveness
Device	Bulma Card	Bootstrap Grid
Mobile (≤576px)	1 full-width card	1 card per row
Tablet (≥768px)	Same card adjusts	2 cards per row
Desktop (≥992px)	Same card adjusts	3 cards per row

Both frameworks ensure smooth scaling and responsive behavior without writing extra media queries.

## 🧾 Credits
Bulma Framework: https://bulma.io

Bootstrap Framework: https://getbootstrap.com

Images: Random sample images from https://picsum.photos

