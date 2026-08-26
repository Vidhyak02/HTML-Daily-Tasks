# 🌍 Day 11 – HTML Task 11

## 📌 Project Overview

This project is a **5-section responsive webpage** created using **HTML5 and Internal CSS**.

The main focus of this task is to create **text overlays on images** using CSS positioning. Each section contains a full-screen Unsplash background image with a stylish text content overlay.

The webpage is designed with a clean and modern travel-inspired theme to demonstrate how images and text can be combined effectively in a webpage.

---

## 🎯 Objective

The objective of this task is to understand and implement:

* Image and text overlay using CSS
* `position: relative`
* `position: absolute`
* CSS gradients
* Full-screen sections
* Navigation between sections
* Responsive web design
* Hover effects
* Smooth scrolling
* Unsplash images

---

## ✨ Features

* 🌅 5 Full-screen Sections
* 🖼️ Unsplash Images
* 📝 Text displayed over images
* 🎨 Gradient image overlays
* 🧭 Fixed navigation bar
* 🔗 Smooth section navigation
* 🔘 Styled buttons with hover effects
* 📱 Responsive layout
* 💻 Internal CSS
* 🌐 Clean and modern UI

---

## 📂 Sections

### 1. 🏠 Home – Discover The World

The first section introduces the webpage with a beautiful travel image and an introductory message.

**Content:**

* Welcome text
* Main heading
* Description
* Start Exploring button

---

### 2. 🏔️ Mountains – Into The Mountains

This section focuses on adventure and mountain landscapes.

**Content:**

* Adventure heading
* Mountain description
* Navigation button

---

### 3. 🌊 Ocean – Feel The Ocean

A peaceful ocean-themed section featuring a beach image with centered overlay content.

**Content:**

* Escape heading
* Ocean description
* Explore More button

---

### 4. 🌃 City – City Lights

This section presents the energy and beauty of modern city life.

**Content:**

* Lifestyle heading
* City description
* Continue button

---

### 5. 🌲 Forest – Lost In Nature

The final section focuses on nature and peaceful forest landscapes.

**Content:**

* Peace heading
* Nature description
* Back To Top button

---

## 🛠️ Technologies Used

| Technology      | Purpose            |
| --------------- | ------------------ |
| HTML5           | Page structure     |
| CSS3            | Styling and layout |
| Unsplash        | Images             |
| CSS Positioning | Text overlay       |
| CSS Gradient    | Image readability  |
| Media Queries   | Responsive design  |

---

## 💡 Main CSS Concept

The main concept of this project is placing text over an image.

The image container uses:

```css
.section {
    position: relative;
}
```

The text content is positioned over the image using:

```css
.content {
    position: absolute;
}
```

This allows the text to appear directly on top of the image.

A gradient overlay is also added to improve text visibility:

```css
.overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(
        to top,
        rgba(0, 0, 0, 0.85),
        rgba(0, 0, 0, 0.15)
    );
}
```

---

## 📁 Project Structure

```text
Day_11_HTML_Task_11/
│
├── Day11.html
│
├── Day11
│
└── Output/
    └── Output
```

---

## 📱 Responsive Design

The webpage is designed to work across different screen sizes.

Media queries are used to adjust:

* Navigation
* Font sizes
* Content positioning
* Section layout
* Mobile screen spacing

---

## 🖥️ Output

The final webpage contains five visually appealing image sections with text positioned over each image.

The fixed navigation bar allows users to quickly move between the different section

<img width="1352" height="615" alt="Output_1" src="https://github.com/user-attachments/assets/4448a011-67be-47e7-8aab-755e833921fd" />
<img width="1349" height="535" alt="Output_2" src="https://github.com/user-attachments/assets/6fcaa017-6818-4333-8682-0d5d26e1f3f9" />
<img width="1329" height="548" alt="Output_3" src="https://github.com/user-attachments/assets/1b0da6c6-d369-4e62-850a-6a0f27cb1ff3" />
<img width="1345" height="547" alt="Output_4" src="https://github.com/user-attachments/assets/4995fe60-8053-412d-bd9f-fc199bcd8b54" />
<img width="1337" height="560" alt="Output_5" src="https://github.com/user-attachments/assets/16ac907e-0440-43f2-8c85-68010ab4492c" />


## 📚 What I Learned

Through this task, I learned how to:

* Place text over images using CSS
* Work with absolute and relative positioning
* Create full-screen sections
* Add gradient overlays
* Create fixed navigation bars
* Implement smooth scrolling
* Add hover effects
* Make webpages responsive
* Use external images from Unsplash
* Design a modern image-based webpage

---

## 👩‍💻 Author

**Vidhya K**

GitHub: [Vidhyak02](https://github.com/Vidhyak02)

---

⭐ **If you find this project useful, feel free to explore the other HTML Daily Tasks in the repository!**
<img width="1337" height="560" alt="Output_5" src="https://github.com/user-attachments/assets/6b20f643-27e7-47b6-bb1e-0bf719680b77" />
