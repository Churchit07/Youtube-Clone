 # 🎥 YouTube Clone

A fully responsive YouTube Homepage Clone built using only HTML5 and CSS3.
This project replicates the layout, styling, grid system, header, sidebar, and video sections of YouTube.

⚡ No JavaScript used — Pure HTML & CSS Layout Practice Project.


## 🚀Features

##   Layout Features

- Fixed Header with Search Bar
- Fixed Sidebar Navigation
- Responsive Video Grid
- Video Duration Overlay
- Tooltip Hover Effects
 
## Responsive Design

- CSS Grid-Based Layout
- Media Queries for Multiple Breakpoints
- Adaptive Columns (2 / 3 / 4 based on screen size)
   
## Styling Techniques

- Flexbox Alignment
- CSS Grid System
- Absolute & Relative Positioning
- Layering using Z-Index
- Hover Transitions


 
## 🛠️Technologies Used

- HTML5
- CSS3 (Flexbox + Grid)
- Google Fonts (Roboto)

## Project Structure

```
Youtube-Clone/
│
├── youtube.html                   # Main Homepage File
│
│
├── Styles/                        # All CSS Files
│   ├── general.css
│   ├── header.css
│   ├── sidebar.css
│   └── video.css
│
├── Extras/
│    ├── Thumbnails/               # Video thumbnail images
│    ├── Channel pictures/         # Channel profile images
│    ├── Icons /                   # SVG Icons
│
└── README.md
```

## 💻 How to Use This Project

1️⃣ Clone the Repository
```
git clone https://github.com/your-username/youtube-clone.git
```

2️⃣ Open the Project
- Open youtube.html
- OR open with VS Code and run using Live Server

That's it ✅

## 🎨How Styling is Applied in This Clone

This project uses modular CSS architecture, where each section has a separate CSS file.

### 🔹 1. General Styling (general.css)

Responsible for:

- Page background
- Global font family (Roboto)
- Body margins and padding

Key Styling Concepts Used:

✔ margin: 0 to remove default browser spacing

✔ padding-top to prevent content hiding under fixed header

✔ padding-left to adjust space for fixed sidebar

✔ Global font consistency

 🔹 2. Header Styling (header.css)

The header is designed using:

- Flexbox
- Fixed positioning
- Hover tooltips
- Icon alignment

Important CSS Concepts Used:

✔ display: flex

✔ justify-content: space-between

✔ align-items: center

✔ position: fixed

✔ z-index layering

🔹 3. Sidebar Styling (sidebar.css)

Sidebar uses:

-Fixed positioning
- Vertical flexbox
- Hover background effect

Key Concepts:

✔ position: fixed

✔ flex-direction: column

✔ Hover background change

🔹 4. Video Grid Styling (video.css)

This is the most important layout section.

It uses:

-CSS Grid
- Responsive breakpoints
- Overlay positioning
- Grid inside grid (video-info-grid)
