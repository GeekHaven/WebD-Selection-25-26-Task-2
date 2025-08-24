# Web Development Wing Member Selection - Backend Round 2  
**Unleashing Backend Mastery**  

Congratulations on embarking on this quest to join the Web Development Wing of GeekHaven!  
In this thrilling mission, you’ll channel your backend skills to forge the foundation of a dynamic **Reselling Platform**.  
Prepare for a captivating journey into the realms of **Express.js**, where you’ll create a marketplace for buying and selling pre-loved treasures.  

---

## Phase 2 Deadline  
**30 August 2025, 11:59 PM**  

---

## The Epic Journey  

### 1. Forging the Backend Marketplace  
- Construct an **Express.js backend stronghold**, where the server-side magic will thrive.  
- Secure the marketplace with **authentication & authorization** so only rightful users can act.  
- Carve the API paths of a bustling reselling marketplace:  
  - **User Onboarding** → Registration & login for buyers and sellers.  
  - **User Profile Mastery** → View & update profile with contact info, location, transaction history.  
  - **Marketplace Listings** → Post new products, fetch listings with pagination, update/remove own listings.  
  - **Favorites & Likes** → Like/favorite items to track potential purchases.  
  - **Shopping Cart Sorcery** → Add items, update quantities, remove items before checkout.  
  - **Checkout & Transactions** → Handle checkout, generate invoices, and process payments (mock or real integration optional).  

---

### 2. Harnessing the Data Magic  
- Power your reselling world with **MongoDB** or **MySQL**.  
- Bonus points if you show strong **SQL mastery**.  

---

### 3. The Sweet Optional Scrolls (Bonus Features)  
- Seller reviews & ratings  
- Real-time chat between buyers & sellers  
- Featured listings (promoted products)  
- Notifications for liked items or categories  
- Search & filters (by name, category, location, price)  

---

## 🔐 Anti-Copy Constraints (Read Carefully)  

To ensure every submission is **unique and original**, the following constraints are **mandatory**:  

1. **Assignment Seed (`ASSIGNMENT_SEED`)**  
   - You will receive a **personal seed** (`GHW25-<unique>`).  
   - Your backend must:  
     - Sign/verify admin JWTs with this seed.  
     - Generate product SKUs using a **checksum derived from this seed**.  
     - Compute a **platform fee** = `floor(1.7% of subtotal + (n from seed))` during checkout.  
   - Submissions failing seed validation will be rejected.  

2. **Rate Limiting & Idempotency**  
   - `/checkout` must be rate-limited to **7 requests per minute per IP**.  
   - Support **Idempotency-Key headers** → retries within 5 minutes must not double-charge.  

3. **HMAC-Signed Responses**  
   - On successful `/checkout`, include an HTTP header:  
     ```
     X-Signature: HMAC-SHA256(response_body, ASSIGNMENT_SEED)
     ```  
   - Our validator will check this.  

4. **Deployment Requirement**  
   - Deploy your API on **Render/Fly/Railway/any free cloud**.  
   - Expose two special routes:  
     - `/<rollno>/healthz` → health check.  
     - `/logs/recent` → last 50 requests (redacted).  

5. **Deliverables**  
   - Private GitHub repo (invite mentors).  
   - Minimum **10 commits over ≥3 days** (no one-shot dumps).  
   - **OpenAPI YAML** for your API.  
   - **Postman Collection** for testing.  
   - **1–2 page ADR (Architecture Decision Record)** explaining design choices.  
   - **3–5 min demo video** (unlisted link) showing seeded behaviors (e.g., SKU checksum, HMAC header).  

6. **Viva & Change Request**  
   - In viva, you will be asked to make a **live 10-min change** (e.g., add a new field, update validation).  
   - Be prepared to walk through your code & explain your design.  

---

## Magical Tools and Codex  

- **Database Mastery** → MongoDB or MySQL.  
- **Documentation of Spells** → README + API docs must explain how to set up & test.  
- **Async/Await Mastery** → Handle database ops smoothly.  
- **Optional Sorcery** → WebSockets/events for real-time magic.  

---

## The Gaze of Evaluation  

- ✅ Seeded behaviors pass hidden tests  
- ✅ Proper authentication & RBAC  
- ✅ Pagination works & stable  
- ✅ Rate limiting + idempotency enforced  
- ✅ HMAC signature correct  
- ✅ Clean schema & migrations  
- ✅ Good ADR & design explanation  
- ✅ Git history shows real progress  
- ✅ Demo video + viva performance  

---

## Submission  

- 📂 Private GitHub repository (invite mentors).  
- 🌐 Deployed URL.  
- 📜 OpenAPI YAML + Postman collection.  
- 📝 ADR document.  
- 🎥 Demo video link.  

---

## Final Words  

This challenge is **not about finishing fastest**—it’s about showcasing **your backend expertise**, your ability to build scalable & secure systems, and your **ownership of the code**.  

May your code reflect clarity and power, and your backend stand as a testament to your mastery.  
The Web Development Wing awaits your creation 🚀.  

