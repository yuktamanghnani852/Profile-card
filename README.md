👤 Profile Card UI/UX Design

A modern Profile Card UI/UX Design created using HTML and CSS. The project presents a developer profile card with a profile image, social media icons, action buttons, and engagement statistics.

The design demonstrates how CSS can be used to create a clean profile-card interface with layouts, shadows, rounded corners, colors, and Font Awesome icons.

📸 Project Overview

The profile card contains:

- 👤 Profile image
- 💻 Website Developer title
- 🎓 College information
- 📚 BCA 1st Year information
- 🌐 Social media icons
- 🔔 Subscribe button
- 💬 Message button
- ❤️ Like count
- 💭 Comment count
- 🔗 Share count

Layout

┌──────────────────────────────────────────────────────────────┐
│                                                              │
│  │  Profile Card UI/UX Design       ┌─────────────────────┐  │
│  │                                  │       Profile       │  │
│  │                                  │       Image         │  │
│  │                                  │                     │  │
│  │                                  │ Website Developer   │  │
│  │                                  │ Dezyne Ecole College│  │
│  │                                  │ BCA 1st Year        │  │
│  │                                  │                     │  │
│  │                                  │ Social Icons        │  │
│  │                                  │                     │  │
│  │                                  │ Subscribe Message   │  │
│  │                                  │                     │  │
│  │                                  │ ♥ 60.4k  💬 20k     │  │
│  │                                  │ ↗ 12.6k             │  │
│  │                                  └─────────────────────┘  │
│                                                              │
└──────────────────────────────────────────────────────────────┘

🛠️ Technologies Used

- HTML5
- CSS3
- Font Awesome 7.3.1

Font Awesome is used to display the social media and engagement icons.

📂 Project Structure

profile-card/
│
├── index.html
├── Capture.PNG
└── README.md

«Make sure "Capture.PNG" is located in the same folder as the HTML file because it is used as the profile image.»

📦 External Library

The project imports Font Awesome using the following CDN:

<link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.3.1/css/all.min.css">

This provides icons such as:

- Facebook
- Instagram
- LinkedIn
- GitHub
- Behance
- Heart
- Comment
- Share

🎨 Main CSS Features

Main Container

.con {
    height: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
}

The container centers the profile card horizontally and vertically.

Profile Card

.box {
    height: 80%;
    width: 80%;
    align-items: center;
    display: flex;
    box-shadow: 10px 10px 10px;
    border-radius: 20px;
}

The card uses:

- Flexbox
- Box shadow
- Rounded corners
- Relative width and height

Card Sections

The card is divided into three sections:

.left,
.center,
.right {
    height: 100%;
}

Section| Width| Purpose
Left| 3%| Decorative navy strip
Center| 62%| Project title
Right| 35%| Profile information

👤 Profile Image

The profile image is placed inside a circular container:

.circle {
    height: 120px;
    width: 120px;
    border: 5px solid navy;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}

The image itself is also made circular:

img {
    height: 100%;
    width: 100%;
    border-radius: 50%;
    border: 5px solid white;
}

🌐 Social Media Icons

The project uses Font Awesome icons for social platforms:

<i class="fa fa-brands fa-facebook fa-2x"></i>
<i class="fa fa-brands fa-instagram fa-2x"></i>
<div class="fa fa-brands fa-linkedin fa-2x"></div>
<i class="fa fa-brands fa-github fa-2x"></i>
<i class="fa fa-brands fa-behance fa-2x"></i>

Each icon is given its own styling.

For example:

.fa-facebook {
    color: blue;
}

.fa-linkedin {
    color: blue;
}

.fa-github {
    color: pink;
}

The Instagram icon uses a gradient:

.fa-instagram {
    background: linear-gradient(purple, red, yellow, orange);
    color: transparent;
    background-clip: text;
}

🔘 Buttons

The card contains two buttons:

- Subscribe
- Message

The buttons use:

.button1 {
    height: 50%;
    width: 40%;
    background-color: navy;
    color: white;
    border-radius: 20px;
    text-align: center;
    line-height: 30px;
}

📊 Engagement Statistics

The bottom section displays social engagement statistics:

❤️ 60.4k    💬 20k    ↗ 12.6k

These represent:

- 60.4k Likes
- 20k Comments
- 12.6k Shares

Font Awesome icons are used to represent each statistic.

▶️ How to Run

1. Create a project folder.
2. Save the HTML code as "index.html".
3. Place "Capture.PNG" in the same folder.
4. Make sure you have an internet connection so Font Awesome can load from the CDN.
5. Open "index.html" in any modern web browser.

🎯 Learning Objectives

This project helps beginners understand:

- HTML page structure
- CSS Flexbox
- Profile card design
- CSS positioning
- Box shadows
- Border radius
- Circular images
- CSS gradients
- Font Awesome icons
- Responsive sizing using percentages
- Basic UI/UX design concepts

💡 Possible Improvements

The project could be improved by:

- Making the card fully responsive for mobile devices
- Adding hover animations to the buttons
- Making social media icons clickable
- Adding actual Subscribe and Message functionality
- Replacing absolute positioning with a more responsive layout
- Adding transitions to the card
- Using CSS variables for reusable colors
- Adding accessibility attributes to icons
- Adding real profile information dynamically

Example Button Hover Effect

.button1 {
    transition: 0.3s;
}

.button1:hover {
    transform: scale(1.05);
    cursor: pointer;
}

⚠️ Notes

The profile image is referenced as:

<img src="Capture.PNG" alt="">

Therefore, the image must be available at the specified path.

Also, the Font Awesome CDN requires an internet connection when the page is opened.

👨‍💻 Author

Created as a beginner-friendly HTML & CSS Profile Card UI/UX project for practicing modern layouts, styling, icons, and profile-card design.# Profile-card
