# Web Development Wing Member Selection - Frontend Round 2  
**Building the Ultimate Reselling Marketplace**  

Embark on an adventurous quest to create a **Reselling Platform Frontend**.  
Choose your spell — either the **powerful React.js** or the **versatile Next.js** — and shape the digital marketplace of dreams.  

---

## Submission Deadline  
**30 August 2025, 11:59 PM**  

---

## 🌟 The Core Challenge  

Your mission is to design and implement the **frontend** of a reselling platform with the following features:  

### 1. Forge the Product Display  
- Create a **responsive, user-friendly page** where sellers can list products and buyers can browse.  

### 2. The Shopping Cart Expedition  
- Let users add/remove items from the cart.  
- Maintain a clean UI for cart review.  

### 3. The Dynamic Marketplace Feed  
- Homepage should display a **live feed of latest listings** with product images, descriptions, and prices.  

### 4. Product Exploration Adventure  
- Implement **search** by category, keyword, or price filter.  

### 5. Product Detail Portal  
- Clicking on a product opens a **detailed product page** with:  
  - Specs  
  - Seller info  
  - Pricing history  

### 6. Sprinkle of Interest: Likes & Bookmarks  
- Users can **like/bookmark** products for later.  

### 7. Seller Profiles Unveiled  
- Create a **seller profile page** showing reviews, ratings, and other listings.  

### 8. Seamless Checkout  
- Implement a smooth **checkout process** using cart items.  

---

## ✨ Optional Enhancements (Sweet Extras)  

- **Smart Pagination** → Show 10 items at a time via scroll or "Load More".  
- **Chat Portal** → Buyer ↔ Seller communication.  
- **Review System** → Buyers can leave reviews for sellers.  
- **Advanced Filters** → Price range, location, condition, category.  
- **Promotional Listings** → Sellers can “boost” listings to the top.  
- **Social Sharing** → Share product links on social platforms.  
- **Dark Mode** → Toggle between light & dark themes.  
- **Location-Based Listings** → Show items near the user.  

---

## 🎨 Achievable Enhancements  

- **Visual Magic** → Use TailwindCSS / Material UI / Ant Design for styling.  
- **Responsive Masterpiece** → Ensure mobile + desktop compatibility.  
- **Smooth Animations** → Subtle UI animations (hover, transitions, loaders).  

---

## 🛡️ Anti-Copy & Uniqueness Requirements  

To make sure every submission is **authentic and original**, the following are mandatory:  

1. **Assignment Seed (`ASSIGNMENT_SEED`)**  
   - You will receive a **unique seed** (`FRONT25-<unique>`).  
   - Your frontend must:  
     - Display this seed on `/about` page in a styled component.  
     - Generate a **color theme or accent color** dynamically from the seed (e.g., hash → color palette).  
     - Fail gracefully if seed is missing.  

2. **Dynamic Behaviors**  
   - **Cart total** must include a **platform fee = (seed_number % 10)% of subtotal**.  
   - Product IDs shown on the frontend should be rendered with a **checksum digit** derived from the seed.  

3. **Deployment Requirement**  
   - Deploy your project on **Vercel/Netlify/Render**.  
   - Must expose:  
     - `/<rollno>/healthz` route/page → Simple “Frontend Alive!” check.  
     - `/logs/recent` page → Show last 20 actions (clicks/searches), stored in local state.  

4. **Deliverables**  
   - Private GitHub repo (invite mentors).  
   - Minimum **10 commits spread over ≥3 days** (no one-shot dumps).  
   - Clear folder structure (`components/`, `pages/`, `styles/`).  
   - **README.md** with setup instructions.  
   - Short **2–3 min demo video** showing:  
     - Seed-based theme color  
     - Product browsing  
     - Cart functionality  
     - Checkout page  

5. **Viva & Live Change**  
   - In viva, you may be asked to make a **10-min live change** (e.g., add a new filter, tweak theme).  
   - Be ready to walk through your code.  

---

## 🔎 The Measure of Excellence  

- ✅ Unique seed-based theme applied  
- ✅ Product listing, detail, search, and cart fully functional  
- ✅ Responsive UI with good design choices  
- ✅ Pagination / filters where applicable  
- ✅ Smooth navigation between pages  
- ✅ Deployment live & accessible  
- ✅ Commit history shows consistent progress  
- ✅ Demo video + viva performance  

---

## 📜 Submission  

- 📂 Private GitHub repository (invite mentors).  
- 🌐 Deployed URL (Vercel/Netlify/Render).  
- 🎥 Demo video link.  

---

## Final Words  

This challenge is about more than building pages — it’s about **designing a usable, scalable, and creative frontend experience**.  

✨ Showcase your originality.  
✨ Keep your users at the center.  
✨ Let your UI shine with clarity and elegance.  

The Web Development Wing awaits your masterpiece 🚀.  

