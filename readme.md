
# 📄 Drug Store Website Documentation
**Project Title:** Abyssinia Pharmacies  
**Developer:** [Your Name]  
**Last Updated:** May 2025

## 📌 Overview
The **Abyssinia Pharmacies** web project is a simple, responsive, and user-friendly front-end website designed to showcase various categories of pharmaceutical products. It aims to help users visually browse the store's offerings, including medicines, cosmetics, supplements, and baby products.

## 🌐 Technologies Used
- **HTML5** – for structuring the content  
- **CSS3** – for styling and layout  
- **Responsive Design** – using media queries to ensure mobile compatibility

## 🗂️ Project Structure
```
/project-root
│
├── index.html        # Main webpage (HTML structure)
├── style.css         # Stylesheet for layout and design
├── /images/          # Folder containing all product images
```

## 🧩 Features

### ✅ Navigation Bar
- **ID:** `#navbar`  
- Contains the store name "Abyssinia Pharmacies"  
- Styled with a green background and white bold text

### ✅ Header Section
- **ID:** `#header`  
- Displays the site’s welcome message and tagline  
- Styled with a soft blue-green background

### ✅ Product Categories
Each product category is wrapped in its own `div` with relevant `id`s:
- **Medicines** - `#medicines`
- **Cosmetics** - `#cosmetics`
- **Medical Devices & Supplies** - `#medical`
- **Vitamins & Supplements** - `#vitamins`
- **Daily Essentials** - `#daily`
- **Mother & Baby Products** - `#motherandbaby`

Each item inside the categories:
- **Uses ID:** `#item`  
- Includes an image and a caption with **ID:** `#description`

### ✅ Contact Information
- **ID:** `#contact-info`  
- Provides address, phone number, and email for the pharmacy  
- Visually separated with background color and centered text

## 🎨 Styling Summary (CSS)

- **Fonts:** Segoe UI and Arial for a clean, readable look  
- **Color Palette:**
  - Header/Footer background: `#e0f2f1` (soft cyan)
  - Navbar: `#004d40` (dark teal)
  - Text: `#333` and white for contrast  
- **Cards:** White backgrounds with shadows and rounded corners  
- **Hover Effects:** Subtle box-shadow on product cards  
- **Responsive Design:** 
  - Adjusts padding, image size, and layout on screens under 768px and 600px

## 📱 Responsiveness
The layout adapts seamlessly to various screen sizes:
- Items stack vertically on small devices
- Image sizes shrink appropriately
- Padding and gaps adjust for mobile friendliness

## 🧪 Possible Improvements
- Add product details and pricing
- Include a search bar or filter options
- Implement a shopping cart system
- Optimize image loading (e.g., lazy loading)
- Add animations or interactivity with JavaScript

## 📧 Contact
For feedback or collaboration:  
- **Email:** info@abyssiniapharmacies.com  
- **Phone:** +251912345678  
- **Address:** Bole Subcity, Woreda 10, Addis Ababa, Ethiopia
