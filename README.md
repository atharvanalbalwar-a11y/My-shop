# 🛍️ Local Shop Connect

> Connecting customers with nearby local shops — shop smarter, support local.

Local Shop Connect is a web-based platform that lets customers discover shops within a chosen radius, browse products, build a shopping list, and send it straight to a shopkeeper. For shopkeepers, it offers an easy way to get online without building a standalone e-commerce site.

The interface is inspired by popular e-commerce platforms such as Amazon, combining the convenience of online shopping with the accessibility of neighborhood stores.

---

## 📑 Table of Contents

- [Project Objectives](#-project-objectives)
- [User Roles & Responsibilities](#-user-roles--responsibilities)
  - [Shopkeeper](#-shopkeeper)
  - [Customer](#-customer)
- [Team Roles & Responsibilities](#-team-roles--responsibilities)
- [How It Works](#-how-it-works)
- [User Interface](#-user-interface)
- [Current Development Scope (v1)](#-current-development-scope-v1)
- [Future Scope](#-future-scope)
- [Expected Impact](#-expected-impact)

---

## 🎯 Project Objectives

- Digitize local retail businesses and improve their online visibility.
- Connect customers with shops in their immediate vicinity.
- Simplify preparing and sharing shopping lists.
- Help shopkeepers manage products and promotional offers efficiently.
- Support local commerce through a convenient digital platform.

---

## 👥 User Roles & Responsibilities

The platform has two primary roles. Each role has its own set of capabilities and responsibilities.

### 🏪 Shopkeeper

The shopkeeper owns and manages a shop's presence on the platform and fulfills customer requests.

| Area | Responsibilities |
|------|------------------|
| **Shop Information Management** | Add and maintain shop details: name, address, contact information, and delivery availability. |
| **Product Management (CRUD)** | **Create** new products, **Read** the product catalog, **Update** names, prices, descriptions, and availability, and **Delete** products no longer sold. |
| **Time-Limited Offers** | Create promotional offers with expiry dates/deadlines so customers know about discounts and special deals. |
| **Delivery Services** | Specify whether delivery is available and define service areas so customers understand their options. |
| **Shopping List Management** | Receive shopping lists sent by customers and review them within the one-hour request window. |

**Key duties at a glance**
- Keep shop details, prices, and availability accurate and up to date.
- Respond to incoming shopping lists before they expire.
- Manage offers and remove or update them once they end.

### 🛒 Customer

The customer discovers nearby shops, browses products, and sends shopping lists to a shopkeeper.

| Area | Responsibilities / Capabilities |
|------|---------------------------------|
| **Location-Based Shop Discovery** | Find local shops within a specified radius of the current location. |
| **Product Browsing** | Explore products offered by nearby shops. |
| **Shopping Cart** | Add products to a cart and create a consolidated shopping list. |
| **Direct List Sharing** | Send the shopping list to a selected shopkeeper. The request stays active for **one hour**, then expires. |
| **Offers & Discounts** | Discover active promotional offers and see their expiration deadlines. |
| **Convenient Shopping** | Avoid visiting multiple shops just to check availability or communicate a list. |

**Key duties at a glance**
- Provide location access (or a location) to discover nearby shops.
- Choose a shop and send a clear, complete shopping list.
- Be aware that requests expire after one hour.

---

## 🧑‍💻 Team Roles & Responsibilities

Development is divided across five roles so each part of the project has a clear owner.

| Role | Responsibilities |
|------|------------------|
| **Frontend Developer** | Build the responsive, e-commerce-style UI: homepage, shop listing, product pages, cart, offers display, and the shopkeeper dashboard. Connect screens to backend APIs and handle loading, error, and empty states. |
| **Backend Developer** | Design and implement REST APIs for shops, products (CRUD), offers, carts, and shopping-list requests. Handle authentication and role-based access (shopkeeper vs. customer), validation, and the one-hour request expiry logic. |
| **Database & Location Services Engineer** | Design the database schema (shops, products, offers, carts, requests). Implement location-based shop discovery (radius search using coordinates), indexing for fast queries, and scheduled cleanup of expired offers and requests. |
| **AI Integration Engineer** | Integrate AI features into the platform, such as smart product search, turning free-text shopping lists into structured items, and personalized product recommendations. Design prompts, connect AI services to the backend through clean APIs, add fallbacks for when the AI service fails or is slow, and keep user data and API keys secure. |
| **UI/UX, QA & Documentation Lead** | Create wireframes and the visual design system. Write test cases and test end-to-end flows across both user roles, including AI-powered features. Maintain the README, API docs, and setup instructions. |

### 🤝 Shared Responsibilities

- Follow the agreed Git workflow: feature branches, pull requests, and code reviews.
- Agree on API contracts (endpoints and data formats) before frontend and backend work in parallel.
- Hold short regular syncs to track progress against the v1 scope.
- Test your own work before opening a pull request.

---

## 🔄 How It Works

1. **Shopkeeper** registers the shop, adds products, delivery details, and any offers.
2. **Customer** opens the site and sets a search radius around their location.
3. Nearby shops are listed; the customer browses products and active offers.
4. The customer adds items to the cart and sends the shopping list to a chosen shop.
5. The **shopkeeper** reviews the request within **1 hour** before it expires.

---

## 🖥️ User Interface

A clean, responsive, and intuitive interface modeled after modern e-commerce websites. The homepage helps users discover nearby shops, browse products, view current offers, and access their cart with minimal effort.

---

## 🚀 Current Development Scope (v1)

The initial version focuses on core functionality:

- [ ] Shop information management
- [ ] Product CRUD operations
- [ ] Time-limited offers
- [ ] Location-based shop discovery
- [ ] Shopping-cart functionality
- [ ] One-hour shopping-list requests

Advanced features will be added incrementally as the platform develops.

---

## 🔮 Future Scope

- Online payments
- Order-status tracking
- Delivery-partner integration
- Customer reviews and ratings
- Real-time inventory updates
- Notifications for expiring offers
- Personalized product recommendations

---

## 🌱 Expected Impact

Local Shop Connect bridges the gap between traditional neighborhood shops and digital commerce. Customers get easier product discovery and faster shopping-list preparation, while shopkeepers gain a simple way to showcase products, communicate with customers, and manage offers — without needing their own e-commerce website.
# My-shop
