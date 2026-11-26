<div align="center">

# 👗 FITSY 👔

### 👧🏻 Girls’ Fashion · 👦🏻 Boys’ Fashion · ✨ Your Style

**Discover outfits. Explore every angle. Find your FITSY style.**

A digital fashion shopping app featuring clothing collections, 360° garment views, virtual runway styling, and store management.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

</div>

---

## 📖 About FITSY

**FITSY** is a digital fashion shopping app for discovering clothing and creating new looks. Browse collections for girls and boys, explore garments with interactive 360° views, and preview outfits on virtual runway models.

FITSY also includes an owner studio for managing clothing products, runway demonstrations, and customer orders.

---

## ✨ What You Can Do

- 👗 **Explore girls’ fashion** and discover outfit ideas.
- 👔 **Browse boys’ clothing** and find styles for every look.
- 🛍️ **Shop clothing collections** with search and category filters.
- 🔄 **View garments in 360°** to inspect their design from different angles.
- 🧍 **Preview runway outfits** on virtual models.
- 🛒 **Continue to checkout** with delivery and payment options.
- 🎨 **Manage the store** through the owner studio.
- 📦 **Review customer orders** in the owner dashboard.
- 📱 **Browse on mobile or desktop** with a responsive interface.

---

## 🛒 Shopping Flow

```mermaid
flowchart TD
    A["👋 Open FITSY"] --> B["🛍️ Browse Girls' and Boys' Fashion"]
    B --> C["👗 Choose an Outfit"]
    C --> D["🔄 Explore the 360° View"]
    C --> E["✨ Preview the Virtual Runway"]
    D --> F["🛒 Add to Shopping Bag"]
    E --> F
    F --> G["📍 Enter Delivery Details"]
    G --> H["💳 Choose a Payment Option"]
    H --> I["✅ Place Order"]
```

---

## 🏗️ How FITSY Works

```mermaid
flowchart LR
    Customer["👤 Customer"] --> App["👗 FITSY App"]

    subgraph Shopping["🛍️ Shopping Experience"]
        App --> Catalog["Girls' and Boys' Catalog"]
        App --> Studio["360° Garment Studio"]
        App --> Runway["Virtual Runway"]
        App --> Checkout["Checkout"]
    end

    Catalog --> Server["⚙️ Node.js Server"]
    Studio --> Server
    Runway --> Server
    Checkout --> Server

    Server --> Database[("💾 SQLite Database")]
    Owner["🎨 Store Owner"] --> Dashboard["Owner Studio"]
    Dashboard --> Server
```

---

## 👥 Customer and Owner

```mermaid
flowchart TD
    Login["🔐 Sign in to FITSY"] --> Role{"Choose account role"}

    Role -->|"Customer"| Customer["🛍️ Shop on FITSY"]
    Customer --> Browse["Browse clothing"]
    Customer --> Style["View 360° garments and runway outfits"]
    Customer --> Buy["Checkout and place an order"]

    Role -->|"Store Owner"| Owner["🎨 Open Owner Studio"]
    Owner --> Products["Manage clothing products"]
    Owner --> Runway["Manage runway demonstrations"]
    Owner --> Orders["Review customer orders"]
```

---

## 🧰 Technology

| Part of the App | Technologies |
|---|---|
| **Web Interface** | HTML5, CSS3, JavaScript |
| **3D Fashion Views** | Three.js, WebGL |
| **Build Tool** | Vite |
| **Server** | Node.js |
| **Database** | SQLite |
| **Maps and Location** | Leaflet.js, OpenStreetMap Nominatim |
| **Version Control** | Git, GitHub |

---

## ⚙️ Run FITSY Locally

You’ll need **Node.js** and **npm** installed.

```bash
# Install the main project dependencies
npm install

# Build the studio
cd studio
npm install
npm run build
cd ..

# Synchronize the built files
node scripts/extracted_rebuild_script.js

# Start the server
node server.js
```

Then open **http://localhost:5000/** in your browser.

---

## 👥 FITSY Team

<div align="center">

| Student ID | Team Member |
|:---:|:---|
| 2620030089 | Manideep |
| 2620030105 | Gowtham Sai |
| 2620030104 | Vishwak |

</div>

---

<div align="center">

# 👗 FITSY 👔

### 👧🏻 Fashion for her · 👦🏻 Fashion for him · ✨ Style for everyone

**Find your look. Make it FITSY.**

</div>
