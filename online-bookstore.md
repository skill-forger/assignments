# Online Bookstore

## Description
A small online bookstore needs to manage its inventory, customers, and orders efficiently. 
Currently, their data is loosely kept in spreadsheets, leading to redundancy, inconsistency, 
and difficulty in querying information.

The bookstore needs to track the following information:
- **Books**: Each book has a unique ISBN, a title, and belongs to a specific genre.
- **Authors**: Books can be written by one or more authors, and authors can write multiple books. 
The bookstore wants to keep track of author names and a short biography.
- **Editions**: The same book (identified by ISBN) can be available in different editions. 
Each specific edition (e.g., Hardcover, Paperback, Ebook) of a book has its own price and stock quantity.
- **Publishers**: Each specific book edition is published by exactly one publisher. 
The bookstore needs to know the publisher's name and the city where they are based.
- **Suppliers**: The bookstore orders specific book editions from various suppliers. 
A single book edition might be available from multiple suppliers, 
each potentially offering a different wholesale cost. 
The bookstore needs supplier names and their contact email addresses.
- **Customers**: Information about registered customers, including their name, email, 
and shipping address (street, city, postal code) needs to be stored.
- **Orders**: Customers place orders, each identified by a unique order ID. 
An order is placed on a specific date and can contain multiple different book format/editions, 
each with a specific quantity ordered. The price charged per item at the time of the order must be recorded.

In this bookstore, there are 3 main types of users:
1. **Customer** - End-users Browse the site, managing their own account, viewing their orders, and searching the catalog.
2. **Staff** - Employees handling day-to-day operations like looking up customer/order details, checking stock, 
basic catalog lookups, and potentially order fulfillment tasks.
3. **Manager** - Users responsible for overseeing inventory, managing supplier relationships, analyzing sales data, 
reviewing reports (like low-stock or sales trends), and making strategic business decisions 
(e.g., based on customer location data or best-selling items).

## Use cases
### Catalog (book, edition, genre) Management
- Customer/Staff/Manager can list all available books in the bookstore.
- Customer/Staff/Manager can view book details.
- Customer/Staff/Manager can list available editions for a book.
- Customer/Staff/Manager can find books by author/genre/publisher.
- Staff/Manager can add a new book into the catalog.
- Staff/Manager can update existing books in the catalog.
- Staff/Manager can remove existing books from the catalog.
- Staff/Manager can add new genre into the catalog.
- Staff/Manager can add new genres for a book.
- Staff/Manager can update existing genres in the catalog.
- Staff/Manager can add remove genres for a book.
- Staff/Manager can add a new edition for a book.
- Staff/Manager can remove edition from a book.

### Author Management
- Customer/Staff/Manager can list all available authors in the bookstore.
- Customer/Staff/Manager can list all available books from an author.
- Customer/Staff/Manager can view author details.
- Staff/Manager can add a new author in the bookstore.
- Staff/Manager can update existing authors in the bookstore.
- Staff/Manager can remove existing authors from the bookstore.

### Publisher Management
- Customer/Staff/Manager can list all available publishers in the bookstore.
- Customer/Staff/Manager can list all available books from a publisher.
- Customer/Staff/Manager can view publisher details.
- Staff/Manager can add a new publisher in the bookstore.
- Staff/Manager can update existing publishers in the bookstore.
- Staff/Manager can remove existing publishers from the bookstore.

### Supplier Management
- Staff/Manager can list all available suppliers in the bookstore.
- Staff/Manager can list all available editions from a supplier.
- Staff/Manager can add a new supplier in the bookstore.
- Staff/Manager can update existing suppliers in the bookstore.
- Staff/Manager can remove existing suppliers from the bookstore.
- Staff/Manager can place a new edition order to a supplier.
- Staff/Manager can complete edition orders from a supplier.

### Inventory Management
- Customer/Staff/Manager can check stock quantity of a book edition.
- Staff/Manager can update the stock quantity of a book edition.
- Manager can generate stock report by week/month/year.

### Customer Management
- Customer can view their own details.
- Customer can update their own profile information.
- Staff/Manager can list all available customers in the bookstore.
- Staff/Manager can view customer information.
- Staff/Manager can deactivate customer profile.

### Order Management 
- Customer can place a new order in the bookstore.
- Customer can update incomplete orders in the bookstore.
- Customer can cancel incomplete orders in the bookstore.
- Customer can retrieve their order details.
- Staff/Manager can place a new order on behalf of the customer.
- Staff/Manager can update orders on behalf of the customer.
- Staff/Manager can retrieve order details from other customers.
- Customer/Staff/Manager can find order history.
- Staff/Manager can complete order for customers.

### Report
- Manager can generate customer report by week/month/year.
- Manager can generate supplier report by week/month/year.
- Manager can generate order report by day/week/month/year.
- Manager can generate edition inventory report by day/week/month/year.
- Manager can identify best-selling items.
- Manager can track book edition sales.
