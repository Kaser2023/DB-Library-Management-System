# DB Project: Library Management System

I've asked ChatGPT to give me 50 Questions and i will solve them.

# I've approximately solve 45 questions by myself


# The solutions for  all 50 these questions on the file [[ lmsQuery.sql  ]]
 You may solve them before see the soltuions -> it's your choice :)
 
# Here are the [[ 50 ]] Questions:


-- These questions cover a variety of SQL concepts, including SELECT statements, filtering, joining tables, 
-- and aggregate functions. Feel free to use these questions to practice and enhance your SQL skills:

--------------------------------------------------------------------------------------------------------------------------------
-- 1-10: General SELECT Queries
--------------------------------------------------------------------------------------------------------------------------------

-- 1.Retrieve all columns for all records in the "books" table.
-- 2.Retrieve the names of all members from the "members" table.
-- 3.Display the titles and authors of books with the genre "Science Fiction."
-- 4.Retrieve the contact numbers of members with a "Premium" membership.
-- 5.Get the total number of records in the "loans" table.
-- 6.Retrieve the distinct genres present in the "books" table.
-- 7.Display the names and membership types of members with IDs between 1 and 10.
-- 8.Retrieve the book titles and return dates for loans with a return date after '2024-01-01.'
-- 9.Display the names of members who borrowed books in 2023.
-- 10.Retrieve the IDs and titles of books that are not available.



--------------------------------------------------------------------------------------------------------------------------------
-- 11-20: Sorting and Limiting Results
--------------------------------------------------------------------------------------------------------------------------------

-- 11.Display the names of members in alphabetical order.
-- 12.Retrieve the book titles and authors, ordered by genre.
-- 13.Display the names and contact numbers of members, limiting the results to the first 10 records.
-- 14.Retrieve the book titles and authors in reverse alphabetical order.
-- 15.Display the first 5 records from the "loans" table.
-- 16.Retrieve the names and contact numbers of members, ordered by contact number.
-- 17.Display the book titles and authors, limiting the results to the first 15 records.
-- 18.Retrieve the names and membership types of members, ordered by membership type and then by name.
-- 19.Display the first 3 records from the "books" table, ordered by book ID in descending order.
-- 20.Retrieve the book titles and authors, limiting the results to the first 20 records, ordered by title.

--------------------------------------------------------------------------------------------------------------------------------
-- 21-30: Filtering and Conditional Queries
--------------------------------------------------------------------------------------------------------------------------------

-- 21.Retrieve the names and contact numbers of members with a "Standard" membership.
-- 22.Display the book titles and authors of books with "Fiction" or "Fantasy" genres.
-- 23.Retrieve the book titles and authors of books where the author's name contains "Brown."
-- 24.Display the names of members who borrowed a book with ID 3.
-- 25.Retrieve the book titles and authors for books available for loan.
-- 26.Display the book titles and authors of books borrowed in 2022.
-- 27.Retrieve the names and contact numbers of members who borrowed a book in 2024.
-- 28.Display the book titles and authors for books borrowed by members with a "Premium" membership.
-- 29.Retrieve the names of members who borrowed a book with a title containing "The."
-- 30.Display the book titles and authors for books borrowed by members with contact numbers starting with '555.'



--------------------------------------------------------------------------------------------------------------------------------
-- 31-40: Aggregation and Grouping
--------------------------------------------------------------------------------------------------------------------------------

-- 31.Get the total number of books in the "books" table.
-- 32.Display the average duration (in days) books are borrowed.
-- 33.Retrieve the total count of loans for each member.
-- 34.Display the earliest and latest taken dates for loans.
-- 35.Get the count of loans for each book.
-- 36.Display the book with the most loans.
-- 37.Retrieve the count of loans for each genre.
-- 38.Display the member with the highest number of loans.
-- 39.Get the total number of loans per membership type.
-- 40.Display the book titles and the count of loans for each book.


--------------------------------------------------------------------------------------------------------------------------------
-- 41-50: Joining Tables
--------------------------------------------------------------------------------------------------------------------------------


-- 41.Retrieve the book titles and authors along with the names of members who borrowed them.
-- 42.Display the book titles, authors, and the names of members who borrowed the books in 2023.
-- 43.Retrieve the book titles, authors, and return dates for loans, along with the member names.
-- 44.Display the book titles and authors along with the membership types of members who borrowed them.
-- 45.Retrieve the book titles and authors along with the total count of loans for each book.
-- 46.Display the names of members, contact numbers, and the titles of books they borrowed.
-- 47.Retrieve the book titles, authors, and return dates, along with the names and membership types of members who borrowed them.
-- 48.Display the book titles and authors along with the total count of loans for each genre.
-- 49.Retrieve the book titles and authors along with the earliest and latest taken dates for loans.
-- 50.Display the names of members, contact numbers, and the total count of loans for each member.
