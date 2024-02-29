# E Commerce Website -> Shopping Cart


<div align="center">
  <br />
    <a href="#" target="_blank">
      <img src="https://github.com/ShivamGupta-5703/E-Commerce-Website/assets/134150130/f59d106e-031f-4b69-adf8-eb57fe6390b2" alt="Project Banner">
    </a>
  <br />

<div>
  <img src="https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logoColor=white&logo=node.js&color=339933" alt="Node.js" />
  <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="MongoDB" />
  <img src="https://img.shields.io/badge/-Bootstrap-black?style=for-the-badge&logoColor=white&logo=bootstrap&color=563D7C" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/-CSS-black?style=for-the-badge&logoColor=white&logo=css3&color=1572B6" alt="CSS" />
  <img src="https://img.shields.io/badge/-JavaScript-black?style=for-the-badge&logoColor=white&logo=javascript&color=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/-EJS-black?style=for-the-badge&logoColor=white&logo=ejs&color=394385" alt="EJS" />
  <img src="https://img.shields.io/badge/-Passport.js-black?style=for-the-badge&logoColor=white&logo=passport&color=34E27A" alt="Passport.js" />
  <img src="https://img.shields.io/badge/-Joi-black?style=for-the-badge&logoColor=white&logo=joi&color=EF5350" alt="Joi" />
</div>

  <h3 align="center">A full stack Shopping cart E-Commerce Website</h3>
</div>

## <a name="introduction">🤖 Introduction</a>

A full-stack website utilizing HTML, CSS, Node.js, Bootstrap, EJS, and MongoDB. The platform allows users to register as sellers or buyers. Sellers can manage their products by adding, editing, and deleting items. Both sellers and buyers can browse through available products, add items to their carts, and proceed with purchases.
## <a name="tech-stack">⚙️ Tech Stack</a>

- Node.js
- MongoDB
- Bootstrap
- CSS
- Java Script
- EJS
- Passport.js
- Joi

## <a name="features">🔋 Features</a>

👉 1. **Database Management with MongoDB:** Utilizing MongoDB for efficient storage and management of user data, product details, and transaction records.
    2. **User Authentication:** Users can register, login, and authenticate using Passport.js, ensuring secure access to the platform's features.
    3. **Responsive Design with Bootstrap and CSS:** Employing Bootstrap and CSS for responsive and visually appealing layouts, ensuring seamless user experience across devices.
    4. **Dynamic Frontend Rendering with EJS:** Utilizing EJS for dynamic rendering of frontend elements, enabling interactive user interfaces for product browsing and purchasing.
    5. **Form Validation with Joi:** Implementing Joi for form validation, ensuring data integrity and preventing invalid submissions during user interactions.
    6. **Seller Product Management:** Sellers can manage their product listings by adding, editing, and deleting items, providing them control over their inventory.
    7. **Product Catalog and Browsing:** Both sellers and buyers can browse through available products, viewing detailed information and images to make informed decisions.
    8. **Shopping Cart Functionality:** Users can add items to their carts, review their selections, and proceed with purchases, enhancing the shopping experience.
    9. **Transaction Management:** Handling transactions securely, ensuring smooth processing of payments and order fulfillment for both buyers and sellers.
    10. **Role-based Access Control with Passport.js:** Implementing Passport.js for role-based access control, distinguishing between sellers and buyers and providing appropriate permissions.


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
https://github.com/ShivamGupta-5703/E-Commerce-Website.git
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:
MONGODB_URL - url for the database.
SECRET - Secret key for session.
```env
MONGODB_URL=
SECRET=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up for the corresponding websites on [MongoDB](https://www.mongodb.com/), [Clerk](https://clerk.com/), and [Uploadthing](https://uploadthing.com/). 

**Running the Project**

```bash
npm start
```

Open [http://localhost:5000](http://localhost:5000) in your browser to view the project.
