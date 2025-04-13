# 📚 Bookstore Database (MySQL + ERD)

This project is a comprehensive SQL-based relational database system for a bookstore. It simulates the real-world operations of a bookstore, managing books, authors, customers, orders, shipping methods, and more.

---

## 🧠 Project Overview

The Bookstore Database Project is a structured MySQL-based system designed to manage data for a bookstore. It handles essential operations such as storing book details, managing authors and publishers, tracking customer information and addresses, processing orders, and supporting shipping and order status updates. The database is designed to organize and retrieve data efficiently, ensuring smooth management of bookstore operations. The schema includes well-defined relationships between tables to represent real-world scenarios such as many-to-many relationships between books and authors, historical order tracking, and customer address history.

---

## 🎯 Objectives

- Design an efficient and scalable MySQL database for a bookstore.
- Model relationships between entities like books, authors, customers, and orders.
- Use SQL to create and manage tables, enforce relationships, and ensure data integrity.
- Create visual ER diagrams using Draw.io.
- Practice user access control and querying.

---

## 🛠️ Tools & Technologies

- **MySQL** – Database management and SQL execution.
- **Draw.io** – Visual database schema (ERD) design.
- **SQL** – Data definition and manipulation.

---

## 📁 Tables Included

| Table Name         | Description |
|--------------------|-------------|
| `book`             | A list of all books available in the store. |
| `book_author`      | Manages many-to-many relationship between books and authors. |
| `author`           | A list of all authors. |
| `book_language`    | Available languages for books. |
| `publisher`        | A list of book publishers. |
| `customer`         | Bookstore’s customers. |
| `customer_address` | Links customers with multiple addresses. |
| `address`          | All addresses in the system. |
| `address_status`   | Status of addresses (e.g., current, old). |
| `country`          | Countries where addresses are located. |
| `cust_order`       | Orders placed by customers. |
| `order_line`       | Books included in each order. |
| `shipping_method`  | Shipping methods available. |
| `order_history`    | Historical events of an order. |
| `order_status`     | Order status types (e.g., pending, shipped). |

---

## 🗂️ Entity Relationship Diagram (ERD)

A preview of the bookstore database structure is shown below.  
Click the link to view or download the full diagram in PDF format.

[📄 View Full ER Diagram (PDF)](https://github.com/iamiancliff/bookstore-db-management/raw/main/bookstore_er_diagram.drawio.pdf)