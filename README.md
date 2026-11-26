<div align="center">

# 👗 FITSY 👔

### ✨ Digital Fashion & 3D Runway Clothing Portal ✨

**Discover your style. Explore every detail. Shop with FITSY.**

A digital fashion app for exploring **Men’s and Women’s collections**, viewing garments in 360°, and styling outfits on a virtual runway.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## 📖 About FITSY

**FITSY** is a digital fashion shopping app designed to make clothing discovery more interactive. Customers can explore **Men’s and Women’s collections**, view garments from different angles using 360° visualization, and preview outfits on virtual runway models.

FITSY also provides store owners with a dashboard to manage products, runway demonstrations, and customer orders.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🛍️ **Fashion Catalog** | Browse Men’s and Women’s collections with search and category filters. |
| 🔄 **360° Studio View** | Rotate garments and inspect their designs from different angles. |
| 👗 **Virtual Runway** | Preview styled outfits on virtual models. |
| 🔐 **Account Access** | New customers can sign up; existing customers and owners can log in. |
| 📍 **Checkout** | Enter delivery details and review order information. |
| 📦 **Order Management** | Owners can review and manage customer orders. |
| 🎨 **Owner Dashboard** | Owners can manage products and runway demonstrations. |
| 📱 **Responsive Design** | Browse FITSY on desktop and mobile screens. |

---

## 🔐 Customer and Owner Access

FITSY uses **one shared login page**. After the account details are checked, the user is directed to the appropriate area.

- **New customer:** Sign up first, then log in.
- **Existing customer:** Log in with a phone number and password.
- **Owner:** Log in with a phone number, email address, and password.

```mermaid
flowchart TD
    A["👋 Open FITSY"] --> B["🔐 Shared Login Page"]
    B --> C{"Does the customer already have an account?"}

    C -->|"No"| D["📝 Customer Sign Up"]
    D --> E["✅ Account Created"]
    E --> F["🔑 Customer Login"]

    C -->|"Yes"| F
    F --> G["📱 Enter Phone Number and Password"]
    G --> H{"Customer details valid?"}
    H -->|"Yes"| I["🛍️ Customer Storefront"]
    H -->|"No"| J["⚠️ Show Login Error"]

    B --> K["👑 Owner Login"]
    K --> L["📱 Enter Phone Number, Email, and Password"]
    L --> M{"Owner details valid?"}
    M -->|"Yes"| N["🎨 Owner Dashboard"]
    M -->|"No"| J
```

---

## 🛍️ Customer Shopping Journey

Customers can browse Men’s and Women’s clothing, explore garments, and place orders.

```mermaid
flowchart LR
    A["🛍️ Customer Storefront"] --> B["Browse Men's and Women's Collections"]
    B --> C["Choose a Garment"]
    C --> D["🔄 View Garment in 360° Studio"]
    C --> E["👗 Preview Outfit on Virtual Runway"]
    D --> F["🛒 Add to Shopping Bag"]
    E --> F
    F --> G["📍 Enter Delivery Details"]
    G --> H["💳 Review Payment Options"]
    H --> I["✅ Place Order"]
    I --> J["📦 Order Added to Store Orders"]
```

---

## 👑 Owner Dashboard

The owner dashboard provides product, runway, and order management tools. Depending on the application’s implementation, these actions can create, view, update, or delete records in the database.

```mermaid
flowchart TD
    A["👑 Owner Login"] --> B["📊 Owner Dashboard"]
    B --> C["👕 Manage Products"]
    B --> D["✨ Manage Runway Demonstrations"]
    B --> E["📦 Manage Customer Orders"]

    C --> C1["➕ Create Product"]
    C --> C2["🔍 View Products"]
    C --> C3["✏️ Update Product"]
    C --> C4["🗑️ Delete Product"]

    D --> D1["➕ Add Demonstration"]
    D --> D2["✏️ Update Styling"]
    D --> D3["🗑️ Remove Demonstration"]

    E --> E1["🔍 View Orders"]
    E --> E2["✏️ Update Order Details"]
    E --> E3["🗑️ Remove Order"]

    C1 --> F[("💾 Application Database")]
    C2 --> F
    C3 --> F
    C4 --> F
    D1 --> F
    D2 --> F
    D3 --> F
    E1 --> F
    E2 --> F
    E3 --> F
```

---

## 🏗️ FITSY System Architecture

```mermaid
flowchart LR
    Customer["🛍️ Customer"] --> WebApp["👗 FITSY Web App"]
    Owner["👑 Store Owner"] --> WebApp

    subgraph Frontend["🖥️ Frontend"]
        WebApp --> Catalog["Men's and Women's Catalog"]
        WebApp --> Studio["360° Studio"]
        WebApp --> Runway["Virtual Runway"]
        WebApp --> Login["Sign Up and Login"]
        WebApp --> Dashboard["Owner Dashboard"]
    end

    Catalog --> Server["⚙️ Node.js Server"]
    Studio --> Server
    Runway --> Server
    Login --> Server
    Dashboard --> Server

    Server --> Database[("💾 SQLite Database")]
```

---

## 🧰 Technology Stack

| Area | Technologies |
|---|---|
| **Frontend** | HTML5, CSS3, JavaScript, TypeScript |
| **3D Visualization** | Three.js, WebGL |
| **Build Tool** | Vite |
| **Backend** | Node.js |
| **Database** | SQLite |
| **Maps and Location** | Leaflet.js, OpenStreetMap Nominatim |
| **Version Control** | Git, GitHub |

---

## 🌟 Why FITSY?

- 👔 Explore clothing from **Men’s and Women’s collections**.
- 🔄 Inspect garments with interactive 360° views.
- ✨ Preview outfits on a virtual runway.
- 🔐 Use a shared sign-in page with separate customer and owner access.
- 📦 Give owners tools to manage products, runway demonstrations, and orders.
- 📱 Browse using a responsive interface.

---

## 👥 FITSY Team

<div align="center">

### ✨ Meet the Team ✨

| 🪪 Student ID | 👤 Team Member |
|:---:|:---|
| `2620030089` | **Manideep** |
| `2620030105` | **Gowtham Sai** |
| `2620030104` | **Vishwak** |

**Together, building a more interactive fashion experience.** 👗👔

</div>

---

<div align="center">

# 👗 FITSY 👔

### **Fashion for Men. Fashion for Women. Style for Everyone.**

*Discover your look. Make it FITSY.* ✨

</div>
