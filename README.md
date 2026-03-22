# QuickBite Food Delivery API 🍕

This is my FastAPI internship project.  
I built a simple backend for a food delivery system where users can view menu items, add items to cart, and place orders.


## Features

- View all menu items
- Get item by ID
- Add, update and delete menu items
- Place orders
- Cart system (add, remove, checkout)
- Filter menu by category, price and availability
- Search items by keyword
- Sort items (price, name, category)
- Pagination
- Combined browse (filter + sort + pagination)

---

## Tech Used

- Python
- FastAPI
- Pydantic
- Uvicorn

---

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Run the server:
uvicorn main:app --reload

3. Open swagger and test
http://127.0.0.1:8000/docs

## Sample APIs

- GET /menu
- GET /menu/{id}
- POST /menu
- PUT /menu/{id}
- DELETE /menu/{id}

- POST /orders
- GET /orders

- POST /cart/add
- GET /cart
- POST /cart/checkout

---

## What I Learned

- Basics to advanced FastAPI concepts
- How to build REST APIs
- Using Pydantic for validation
- Implementing real-world workflows like cart and checkout
- Search, sort and pagination

