# 🚀 ReactUI Components

A modern, reusable, and accessible **UI Component Library** built with **React** and **Vanilla CSS**.  
This project showcases beautifully designed components like Buttons, Cards, and Modals with light/dark theme support.

---

## ✨ Features

- 🎨 Clean and modern UI design  
- 🌗 Light / Dark mode toggle  
- ⚡ Reusable components  
- 📱 Fully responsive  
- 🔐 Accessible components  
- 🧩 Modular structure  

---

## 🧩 Components

### 🔘 Buttons
- Primary, Secondary, Danger
- Outline & Ghost styles
- Sizes: Small, Medium, Large
- Icon support
- Disabled state
- Full-width option

### 🃏 Cards
- Header, Body, Footer structure
- Icon integration
- Hover effects

### 📦 Modal
- Smooth animations
- Custom title and footer
- Reusable dialog component
- Keyboard accessibility

---

## 🛠️ Tech Stack

- React JS  
- Vanilla CSS  
- Lucide React Icons  

---

## 📂 Project Structure


src/
│── components/
│ ├── Button.jsx
│ ├── Card.jsx
│ ├── Modal.jsx
│
│── App.jsx
│── App.css
│── index.js


---

## ⚙️ Getting Started

### 1. Clone the repository


git clone https://github.com/your-username/react-ui-components.git


### 2. Navigate to the project


cd react-ui-components


### 3. Install dependencies


npm install


### 4. Run the app


npm start


---

## 🌗 Theme Toggle

This project includes light and dark mode using:

```js
document.documentElement.setAttribute('data-theme', theme);
💡 Usage

Import components:

import { Button, Card, Modal } from './components';

Example:

<Button size="lg" variant="primary">
  Click Me
</Button>
📌 Future Improvements
Add form components (Input, Select, Checkbox)
Add Toast Notifications
Publish as npm package
Add animations
🤝 Contributing

Contributions are welcome!

Fork the project
Create your feature branch
Commit your changes
Push to the branch
Open a Pull Request
