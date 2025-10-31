# 🎬 Movie Catalog - Manual API Testing Project

This project contains a **Postman collection** for **manual testing** of Movie Catalog .  
It was created as part of my QA training to practice working with REST APIs and HTTP methods.>
📝 Note: This collection was created for educational purposes as part of a QA exam project at SoftUni.  
> The tested API was provided by the academy and is used here only for demonstration of manual API testing skills.


---

## 🧾 About the Project

The Movie Catalog API allows users to register, log in, and manage a list of movies.  
I tested all main functionalities manually in Postman — including creating, editing, and deleting movies.

---

## 🌐 Base URL

`https://d24hkho2ozf732.cloudfront.net`  

⚠️ *Note: This was a temporary test environment and may not be active anymore.*

---

## 🧪 Requests Included

| # | Name | Method | Endpoint | Description |
|---|------|---------|-----------|--------------|
| 1 | Register User | POST | `/api/User/Register` | Create a new user |
| 2 | Log In | POST | `/api/User/Authentication` | User login and token |
| 3 | Create Movie | POST | `/api/Movie/Create` | Add a new movie |
| 4 | List Movies | GET | `/api/Catalog/All` | View all movies |
| 5 | Edit Movie | PUT | `/api/Movie/Edit` | Update an existing movie |
| 6 | Delete Movie | DELETE | `/api/Movie/Delete` | Remove a movie |

---


## ✅ What Was Tested

- Status codes (200, 201, 400, 401)
- JSON response structure
- Authorization (token required)
- Data changes after Create / Edit / Delete

---

## 👩‍💻 Author

**Yoana Raykova**  
