# Databases and SQL Assessment

**Duration:** 1 hour 50 minutes

## Learning Outcomes

By completing this assessment, pupils will demonstrate their ability to:


1. Create a database with an appropriate table structure

2. Use SQL to retrieve and manipulate data in response to given scenarios

3. Apply problem-solving skills to analyze and process data effectively

## Assessment Instructions

You are required to:

1. **Part A:** Design and create a single table to store and manage information.

2. **Part B:** Write SQL queries to interact with the database.

## Scenario

You are working for a local library that needs a database to keep track of its books.

## Part A: Database Design and Creation (40 marks)

1. Identify Table Fields (5 marks)

   - Create a single table called `Books` with the following fields:
     - Book ID (Primary Key)
     - Title
     - Author
     - Genre
     - Published Year
     - Price
     - Stock Quantity

2. **Define the Table Structure** (10 marks)

   - Choose appropriate data types for each field:

     - For example, `Book ID` should be an integer, and `Title` should be text.

3. **Create the Table** (10 marks)

   - Use a database management tool to create the table with the specified structure.

4. **Populate the Table with Data** (15 marks)

   - Add at least **10 records** of books, ensuring data is realistic and varied.

## Part B: SQL Query Questions (60 marks)

### Task 1: Retrieve Data (20 marks)

Write SQL queries to answer the following:

1. List all books in the "Science Fiction" genre. (5 marks)

2. Display the titles and authors of all books published before the year 2000. (5 marks)

3. Show the title, genre, and price of all books that cost more than £10. (5 marks)

4. Find all books written by "George Orwell". (5 marks)

### Task 2: Sorting Data (20 marks)

Write SQL queries to answer the following:

1. Display all books in alphabetical order by their title. (5 marks)

2. Retrieve the details of all books in the "Fiction" genre, sorted by their publication year (oldest to newest). (5 marks)

3. List the titles and authors of all books priced between £5 and £10 from low to high. (5 marks)


### Task 3: Analyse Data (20 marks)

Write SQL queries to answer the following:

1. Retrieve the titles and genres of books published before 1950. (5 marks)

2. Display the titles of all books that cost exactly £8.49. (5 marks)

3. List the titles and prices of books with a stock quantity greater than or equal to 10. (5 marks)

4. Find all books with a stock quantity of less than 10. (5 marks)


## Mark Scheme

### Part A: Database Design and Creation (40 marks)

| Task                    | Marks | Criteria                                                                 |
|-------------------------|-------|-------------------------------------------------------------------------|
| Identify Table Fields   | 5     | Fields align with the requirements of the scenario.                     |
| Define the Table Structure | 10 | Correctly assigns appropriate data types for each field.                |
| Create the Table        | 10    | Successfully creates the table with no errors.                          |
| Populate the Table      | 15    | Inserts realistic and varied data for all 10 records.                   |

### Part B: SQL Query Questions (60 marks)

| Task                | Marks | Criteria                                                                 |
|---------------------|-------|--------------------------------------------------------------------------|
| Retrieve Data       | 20    | Queries return the correct results and use appropriate syntax.           |
| Sorting Data        | 20    | Queries successfully order data as required.                             | 
| Analyse Data        | 20    | Queries accurately calculate or identify data based on requirements.     |

## Appendix

Book Data for the `Books` Table

| **Book ID** | **Title**                     | **Author**          | **Genre**           | **Published Year** | **Price (£)** | **Stock Quantity** |
|-------------|--------------------------------|---------------------|---------------------|--------------------|---------------|--------------------|
| 1           | Dune                          | Frank Herbert       | Science Fiction     | 1965               | 9.99          | 12                 |
| 2           | 1984                          | George Orwell       | Dystopian           | 1949               | 7.99          | 8                  |
| 3           | To Kill a Mockingbird         | Harper Lee          | Fiction             | 1960               | 6.99          | 5                  |
| 4           | Harry Potter and the Philosopher's Stone | J.K. Rowling    | Fantasy            | 1997               | 8.49          | 15                 |
| 5           | The Hobbit                    | J.R.R. Tolkien      | Fantasy             | 1937               | 10.99         | 7                  |
| 6           | Brave New World               | Aldous Huxley       | Science Fiction     | 1932               | 8.49          | 10                 |
| 7           | The Great Gatsby              | F. Scott Fitzgerald | Fiction             | 1925               | 5.99          | 9                  |
| 8           | The Catcher in the Rye        | J.D. Salinger       | Fiction             | 1951               | 6.49          | 4                  |
| 9           | Fahrenheit 451                | Ray Bradbury        | Dystopian           | 1953               | 7.49          | 3                  |
| 10          | The Name of the Wind          | Patrick Rothfuss    | Fantasy             | 2007               | 12.99         | 6                  |
