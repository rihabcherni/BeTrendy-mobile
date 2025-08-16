
# Be-Trendy
E-commerce Mobile App (Ionic + Django + MongoDB)

## Features
- **User Authentication** – Registration, login, and profile management
- **Multi-Role System** – Client, Seller, and Admin interfaces
- **Product Catalog** – Browse trendy items with images, prices, and details
- **Advanced Search & Filters** – Find products by category, price, and ratings
- **Shopping Cart** – Add, remove, and update cart items
- **Wishlist** – Save favorite products for later
- **Seller Dashboard** – Manage products and orders
- **Responsive Design** – Optimized for mobile devices
- **RESTful API** for frontend communication
- **Secure Authentication & Authorization** (JWT)
- **Product Management** (CRUD operations)
- **Order Management** – Complete order lifecycle

## App Screenshots

### Authentication Interface

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="screenshots/login/splash.PNG" alt="Splash Screen" width="200"/><br/>
        <b>Splash Screen</b><br/>
      </td>
      <td align="center">
        <img src="screenshots/login/welcome.PNG" alt="Welcome Screen" width="200"/><br/>
        <b>Welcome Screen</b><br/>
      </td>
      <td align="center">
        <img src="screenshots/login/newslteer.PNG" alt="Newsletter Subscription" width="200"/><br/>
        <b>Newsletter Subscription</b><br/>
      </td>
     <td align="center">
        <img src="screenshots/login/role.PNG" alt="Role Selection" width="200"/><br/>
        <b>Role Selection</b><br/>
      </td>
      <td align="center">
        <img src="screenshots/login/register1.PNG" alt="Register Step 1" width="200"/><br/>
        <b>Registration</b><br/>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="screenshots/login/otp.PNG" alt="OTP Verification" width="200"/><br/>
        <b>OTP Verification</b><br/>
      </td>
    <td align="center">
          <img src="screenshots/login/forgot.PNG" alt="Forgot Password" width="220"/><br/>
          <b>Forgot Password</b><br/>
        </td>
     <td align="center">
        <img src="screenshots/login/login.PNG" alt="Login Screen" width="200"/><br/>
        <b>Login Screen</b><br/>
      </td>
      <td align="center">
        <img src="./screenshots/login/profil.PNG" alt="User Profile" width="200"/><br/>
        <b>User Profile</b><br/>
      </td>
       <td align="center">
        <img src="./screenshots/login/nav.PNG" alt="Nav" width="200"/><br/>
        <b>Menu</b><br/>
      </td>
    </tr>
  </table>
</div>

### Client Interface

<div align="center">
  <table>
    <tr>
     <td align="center" colspan="2">
        <img src="./screenshots/client/product.png" alt="Product Catalog"/>
        <b>Shopping Experience</b><br/>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="./screenshots/client/category-all.png" alt="Category Filter"/>
        <b>Category Filter</b><br/>
      </td>
      <td align="center">
        <img src="./screenshots/client/9-favorite.PNG" alt="Wishlist" width="400"/><br/>
        <b>Wishlist</b><br/>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <img src="./screenshots/client/carte.png" alt="Shopping Cart"/><br/>
        <b>Shopping Cart & order summary</b>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <img src="./screenshots/client/pay.png" alt="Shopping Cart"/><br/>
        <b>Payment Methods</b><br/>
      </td>
    </tr>
  </table>
</div>

### Seller Interface
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="./screenshots/seller/seller-dash.PNG" alt="Seller Dashboard" width="210"/><br/>
        <b>Seller Dashboard</b><br/>
      </td>
      <td align="center">
        <img src="./screenshots/seller/seller.PNG" alt="Seller Profile" width="240"/><br/>
        <b>Seller Profile</b><br/>
      </td>
        <td align="center">
        <img src="./screenshots/seller/add-pro.PNG" alt="Seller add" width="180"/><br/>
        <b>Add Product</b><br/>
      </td>
    </tr>
  </table>
</div>

### Admin Interface
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="./screenshots/admin/admin-dash.PNG" alt="Admin Dashboard" width="200"/><br/>
        <b>Admin Dashboard</b><br/>
      </td>
      <td align="center">
        <img src="./screenshots/admin/client.PNG" alt="Sellers" width="200"/><br/>
        <b>Sellers List</b><br/>
      </td>
            <td align="center">
        <img src="./screenshots/admin/seller-add.PNG" alt="Add seller" width="200"/><br/>
        <b>User Management</b><br/>
      </td>
    </tr>
  </table>
</div>

---

### Technology Stack  

<table>
  <tr>
    <th>Layer</th>
    <th>Technologies</th>
  </tr>
  <tr>
    <td><b>Frontend (Mobile App)</b></td>
    <td>
      - Ionic (Cross-platform mobile framework)<br/>
      - Angular (Frontend framework)<br/>
      - TypeScript (Programming language)
    </td>
  </tr>
  <tr>
    <td><b>Backend (API Server)</b></td>
    <td>
      - Django (Python web framework)<br/>
      - Django REST Framework (API development)<br/>
      - JWT (Authentication tokens)
    </td>
  </tr>
  <tr>
    <td><b>Database</b></td>
    <td>
      - MongoDB (NoSQL document database)
    </td>
  </tr>
</table>

## Installation & Setup

### Prerequisites
- **Node.js** (v16 or higher)
- **Python** (v3.9 or higher)
- **MongoDB** (v5.0 or higher)
- **Ionic CLI**
- **Git**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/rihabcherni/BeTrendy-mobile.git
cd BeTrendy-mobile
```

### 2️⃣ Setup Frontend (Ionic)

```bash
cd frontend
npm install
npm install -g @ionic/cli
ionic serve
```

Access the app via: **[http://localhost:8100](http://localhost:8100)**

### 3️⃣ Setup Backend (Django + MongoDB)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
Access the API via: **[http://localhost:8000](http://localhost:8000)**  

---

## Contributors

- **Rihab Cherni** 
- **Molka Elloumi**
- **Wiem Hammemi** 
<div align="center">
  <p><strong>Made with ❤️ by the Be-Trendy team</strong></p>
</div>