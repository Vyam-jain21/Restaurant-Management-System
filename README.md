# Restaurant Management System (C Program)

A simple, file-based **Restaurant Management System** written in C.  
This program allows **Admin** and **Customers** to interact with the restaurant system with different features like product registration, customer registration, admin login, product display, and placing orders.

---

## 🚀 Features

### 👨‍💼 Admin
- Register new admin (stored in `restaurant.txt`)
- Secure login system with 3 attempts and 30-second cooldown
- Register new products (`product.txt`)
- Display available products

### 🧑‍🤝‍🧑 Customer
- Register new customer (`rest.txt`)
- Login as returning customer
- View available products
- Place an order

---

## 📁 File Structure Used
| File Name       | Purpose |
|-----------------|----------|
| `restaurant.txt` | Stores admin username & password |
| `rest.txt`       | Stores customer records |
| `product.txt`    | Stores product menu with price, category & quantity |

---

## 🛠️ How to Compile & Run

### **Using GCC**
```bash
gcc restaurant.c -o restaurant
./restaurant
