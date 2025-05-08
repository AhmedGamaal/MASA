
# MASA - Online Book Store 

MASA is a modern online book store web application built to improve the book shopping experience in Egypt. It allows customers to browse, filter, and buy books seamlessly, while also offering powerful admin tools to manage inventory, orders, and users.

---

##  Who Are We?

We’re a team of passionate developers who collaborated to build MASA as part of our .NET learning journey. The goal was to apply full-stack web development principles in a real-world scenario using modern technologies.

###  Team Members

- **Ahmed Gamal** – Full-Stack Developer  
- **Salma Akram** – Full-Stack Developer  
- **Mai Shehab** – Full-Stack Developer  
- **Abdelrahman Tawhed** – Full-Stack Developer  

---

##  Tech Stack

| Layer       | Technology                    |
|-------------|-------------------------------|
| Frontend    | HTML, CSS, JavaScript, Bootstrap 5 |
| Backend     | ASP.NET Core MVC (.NET 9)     |
| Database    | MS SQL Server 2022            |
| ORM         | Entity Framework Core         |
| Auth        | ASP.NET Core Identity         |
| Hosting     | Azure / AWS (Optional)        |

---

##  Design & System Diagrams

- **System Diagram** → [View on Google Drive](https://drive.google.com/drive/folders/1_xX3pzX3BVyZF7ChlCi6RxWEcUMzw419?usp=drive_link)  
- **UI/UX Design** → [View on Figma](https://www.figma.com/design/DpDSuVv3kEFhh7WQiLUE2Q/e-commerce?node-id=1-2903&t=ylV4GjcZacKoNAzq-0)  

---

##  Key Features

-  **Smart Search & Filtering** – by title, genre, author, and price  
-  **Shopping Cart & Secure Checkout**  
-  **Order Tracking & History**  
-  **Admin Dashboard** – Manage books, categories, users, and orders  
-  **Customer Reviews & Ratings**  
-  **Authentication & Authorization** – Role-based login (Admin, User)  

---

##  How to Run the Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AhmedGamaal/MASA.git
   ```

2. **Open the Solution**

   Navigate to the project folder and open `BookShoppingCartMvc.sln` in Visual Studio 2022 or later.

3. **Configure the Database Connection**

   Open `appsettings.json` and update the connection string:

   ```json
   "ConnectionStrings": {
      "DefaultConnection": "data source=YOUR_SERVER_NAME;initial catalog=BookStoreDb;integrated security=true;encrypt=false"
   }
   ```

4. **Run the Project**

   Press `Ctrl + F5` or click Run.

   On first run:
   - Database will be created.
   - Default data will be seeded.
   - Admin account will be created.

---

##  Default Admin Credentials

You can log in with the following credentials:

- **Email:** admin@gmail.com  
- **Password:** Admin@123  

 **Notes**
- You may need to enable EF Core Migrations if seeding or DB creation fails.
- Make sure SQL Server is installed and running before launching the app.
- Bootstrap 5 is used for styling, and the site is fully responsive.

---

