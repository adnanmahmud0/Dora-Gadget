---

# **Dora Gadget 🛒**  

Welcome to **Dora Gadget**, an e-commerce platform designed to bring you the latest and greatest gadgets. Explore our wide range of products, add them to your cart, and manage your wishlist effortlessly.  

## 🌐 Live Website  
[Dora Gadget Live Link](http://dora-gadget.surge.sh)  

## 📄 Requirement Document  
[Assignment Requirement Document](https://github.com/programming-hero-web-course2/b10a8-gadget-heaven-adnanmahmud0/blob/main/public/Batch-10_Assignment-08-.pdf)  

---

## ✨ Key Features  
1. **🛍️ Product Listing & Categorization** – Browse gadgets in a grid view, categorized into Computers, Phones, Smartwatches, and more.  
2. **🛒 Cart & Wishlist Management** – Add items to your cart or wishlist and manage them easily.  
3. **📄 Detailed Product Pages** – Each product has a dedicated details page with specifications, pricing, and actions.  
4. **🔍 Sorting & Filtering** – Sort items by price and filter products by category.  
5. **📱 Responsive Design & 404 Page** – Optimized for mobile, tablet, and desktop with a custom 404 page.  

---

## ⚛️ React Fundamentals Used  
- **JSX** – For rendering HTML inside JavaScript.  
- **Components** – Reusable UI components like Navbar, Footer, Product Cards, etc.  
- **Props** – Passing data between components for reusability.  
- **State Management** – Managed dynamic data using `useState`.  
- **Hooks** – Implemented `useEffect`, `useContext`, `useLocation`, and `useNavigate`.  

*(For a detailed list of concepts, refer to the requirement document.)*  

---

## 🛠️ Data Handling & Management  
- **Context API** – Global state management for cart and wishlist data.  
- **LocalStorage** – Data persistence to retain cart and wishlist items even after page refresh.  

---

## 🚀 Technologies Used  

### **Frontend**  
- [React.js](https://reactjs.org/) – Component-based UI development.  
- [React Router](https://reactrouter.com/) – Routing and navigation.  
- [React Helmet](https://github.com/nfl/react-helmet) – SEO optimization.  
- [Recharts](https://recharts.org/) – Data visualization.  

### **Styling**  
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework.  
- [DaisyUI](https://daisyui.com/) – Pre-designed UI components.  

### **Other Packages**  
- [React Icons](https://react-icons.github.io/react-icons/) – Icon library.  
- [React Toastify](https://fkhadra.github.io/react-toastify/) – Notifications and alerts.  
- [Sort-By](https://www.npmjs.com/package/sort-by) – Sorting utility.  

---

## 📦 NPM Dependencies  

```json
{
  "name": "dora-gadget",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint .",
    "preview": "vite preview"
  },
  "dependencies": {
    "localforage": "^1.10.0",
    "match-sorter": "^8.0.0",
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "react-helmet": "^6.1.0",
    "react-helmet-async": "^2.0.5",
    "react-icons": "^5.3.0",
    "react-rating-stars-component": "^2.2.0",
    "react-router-dom": "^6.27.0",
    "react-toastify": "^10.0.6",
    "recharts": "^2.13.3",
    "sort-by": "^1.2.0"
  },
  "devDependencies": {
    "@eslint/js": "^9.13.0",
    "@types/react": "^18.3.12",
    "@types/react-dom": "^18.3.1",
    "@vitejs/plugin-react": "^4.3.3",
    "autoprefixer": "^10.4.20",
    "daisyui": "^4.12.14",
    "eslint": "^9.13.0",
    "eslint-plugin-react": "^7.37.2",
    "eslint-plugin-react-hooks": "^5.0.0",
    "eslint-plugin-react-refresh": "^0.4.14",
    "globals": "^15.11.0",
    "postcss": "^8.4.47",
    "tailwindcss": "^3.4.14",
    "vite": "^5.4.10"
  }
}
```

---

## ⚡ Installation & Setup  

### **Prerequisites**  
1. **Node.js** – Install [Node.js](https://nodejs.org/).  
2. **Firebase (if applicable)** – Configure Firebase for authentication or database usage.  

### **Installation Steps**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/dora-gadget.git
   ```
2. Navigate to the project folder:  
   ```bash
   cd dora-gadget
   ```
3. Install dependencies:  
   ```bash
   npm install
   ```
4. Start the development server:  
   ```bash
   npm run dev
   ```

---

## 🖼️ Screenshot  
![Dora Gadget Homepage](https://raw.githubusercontent.com/adnanmahmud0/Dora-Gadget/refs/heads/main/Screenshot%202025-01-05%20162442.png)


---

## 🏗️ Development & Build Commands  

| Command           | Description                            |
|------------------|--------------------------------|
| `npm run dev`    | Starts the development server. |
| `npm run build`  | Builds the project for production. |
| `npm run preview` | Previews the built project. |
| `npm run lint`   | Runs ESLint for code checking. |

---

