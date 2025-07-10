# 🧪 Restful Booker API Testing with Postman

This project contains API automation test cases for the [Restful Booker](https://restful-booker.herokuapp.com/apidoc/index.html) service using **Postman** and **Newman**. It includes authentication, CRUD operations, schema validation, and response content checks.

---

📤 Postman Public Collection Link
🔗 https://www.postman.com/ffvhv0/projects/collection/g4k25de
---

## 📌 Features Covered

- ✅ Token generation via `/auth`
- ✅ Create, Read, Update, Delete booking records
- ✅ Partial updates with `PATCH`
- ✅ Server health check `/ping`
- ✅ Request and response validations
- ✅ Cookie and header validations
- ✅ Dynamic token usage
- ✅ Data-driven test setup using environment variables

---

## 🧾 Technologies Used

- [Postman](https://www.postman.com/)
- [Newman CLI](https://www.npmjs.com/package/newman)
- JSON Schema
- Optional: HTML/JSON reporters

---

## 📂 Project Structure

RestfulBooker_API_Testing/
├── RestfulBooker.postman_collection.json
├── README.md
└── newman/
├── report.html


🧪 Test Cases Summary
| Endpoint        | Method | Validations                             |
| --------------- | ------ | --------------------------------------- |
| `/auth`         | POST   | Token created and stored                |
| `/booking`      | POST   | New booking with ID, validate fields    |
| `/booking/{id}` | GET    | Verify booking data, check content-type |
| `/booking/{id}` | PUT    | Full update, verify all fields          |
| `/booking/{id}` | PATCH  | Partial update of specific fields       |
| `/booking/{id}` | DELETE | Successful deletion, verify with GET    |
| `/ping`         | GET    | Status 201, server running check        |


👤 Author
Tejas Bansal
📧 tejasbansal6065@gmail.com