Objective: Create a personal book library application where you manage your collection of books. This project will allow you to practice various MongoDB operations, understand data modeling, and use advanced features like indexing and aggregation.

Features to Implement:

Book Insertion:
Create a collection for books with fields like title, author, genre, publicationYear, isRead, rating (1-5), and notes.
Use insertOne or insertMany to add books to your library.
Querying Books:
Implement queries to search for books by title, author, genre, or publication year.
Use complex queries like finding all unread books sorted by publication year.
Updating Records:
Allow updates to book information, like marking a book as read, updating ratings, or adding notes.
Deleting Books:
Implement functionality to remove books from the library.
Indexing:
Create indexes on title, author, and genre to speed up searches.
Aggregation Pipelines:
Use aggregation to find:
The average rating per genre.
The number of books read per year.
Top 5 authors by the number of books in your library.
Complex Queries:
Find books where the rating is above a certain threshold and the genre matches user input.
Query books where the notes field contains specific keywords.
Text Search:
Implement text search for books by title or notes.
Data Export:
Export a JSON file of all books or filtered sets based on criteria.
