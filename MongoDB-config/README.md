
---

# **Database (MongoDB Implementation)**

````markdown
# 🗄️ HomelyHub – Database Setup (MongoDB)

This project uses **MongoDB** with **Mongoose** and contains three main collections:

- **users**
- **properties**
- **bookings**

A sample dataset (`properties.json`) is included in the project root.

---

## 📦 Database Setup

### Connection String (in backend `.env`)
```env
MONGO_URI=mongodb://localhost:27017/HomelyHub
````

Start MongoDB locally:

```bash
mongodb
```

---

## 📂 Collections Overview

### 1️⃣ Users Collection

Stores user accounts.

```
fields: username, email, password, phone, role
```

### 2️⃣ Properties Collection

Stores property listings.

```
fields: propertyName, description, address, price, images[], amenities[], ownerId
```

### 3️⃣ Bookings Collection

Stores reservations.

```
fields: userId, propertyId, checkIn, checkOut, guests, totalPrice
```

---

## 📥 Import Sample Properties (properties.json)

Place `properties.json` in your **project root** (already done).

Run:

```bash
mongoimport --db HomelyHub --collection properties --file properties.json --jsonArray
```

This will:

✔ Create the `properties` collection
✔ Insert all sample property documents

---

## 📁 Database Folder Structure

```
backend/
  └── src/
       ├── models/
       │     ├── userModel.js
       │     ├── propertyModel.js
       │     └── bookingModel.js
       ├── config/
       │     └── db.js
       └── ...
properties.json   # sample seed data
```
