# petbusiness
# PetBusiness API

## 🐾 About PetBusiness
**PetBusiness** is a RESTful API designed to manage a pet-related business. It allows users to manage pets, services, appointments, and customer information efficiently. The API is built using **Node.js**, **Express.js**, and follows best practices in API development.

---

## 🚀 Features
- 🐶 **Pet Management** - Add, update, delete, and retrieve pet details.
- 👨‍⚕️ **Service Management** - View and manage pet-related services.
- 📅 **Appointments** - Schedule and manage customer bookings.
- 👥 **Customer Management** - Store and retrieve customer information.
- 📜 **API Documentation** - Integrated with Swagger UI for easy testing and reference.

---

## 📦 Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (or any other supported database)
- **Authentication:** JWT (for secure access)
- **API Documentation:** Swagger UI

---

## 🛠 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Alexanderlecky/petbusiness.git
cd petbusiness
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the root directory and add:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Server
```bash
npm run dev
```
_(Runs the app using nodemon)_

To run normally:
```bash
node App.js
```

---

## 🔥 API Endpoints

### ✅ Pets
- `GET /api/pets` - Get all pets
- `POST /api/pets` - Add a new pet
- `GET /api/pets/:id` - Get pet by ID
- `PUT /api/pets/:id` - Update pet details
- `DELETE /api/pets/:id` - Remove a pet

### ✅ Customers
- `GET /api/customers` - Get all customers
- `POST /api/customers` - Add a new customer
- `GET /api/customers/:id` - Get customer by ID
- `PUT /api/customers/:id` - Update customer details
- `DELETE /api/customers/:id` - Remove a customer

### ✅ Appointments
- `GET /api/appointments` - Get all appointments
- `POST /api/appointments` - Schedule an appointment
- `GET /api/appointments/:id` - Get appointment details
- `PUT /api/appointments/:id` - Update appointment
- `DELETE /api/appointments/:id` - Cancel appointment

---

## 📝 API Documentation
This project includes **Swagger UI** for API testing and documentation.

After running the server, open in your browser:
```
http://localhost:3000/api-docs
```

---

## 🛡 Authentication & Security
- Uses **JWT (JSON Web Tokens)** for secure authentication.
- API routes are protected for registered users.

---

## ✅ Running Tests
To run tests using **Jest**:
```bash
npm test
```

---

## 🤝 Contributing
Contributions are welcome! To contribute:
1. **Fork** the repository.
2. Create a new **branch** (`feature/your-feature`)
3. Commit your changes.
4. Submit a **Pull Request**.

---

## 📄 License
This project is licensed under the **MIT License**.

---

## 📩 Contact
For questions or support, reach out via:
- **GitHub:** [Alexanderlecky](https://github.com/Alexanderlecky)
- **Email:** alexanderkaranja78@gmail.com

🚀 Happy Coding!

