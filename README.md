# marketing-page
- As a user I can log in, and see a list of text books.
- Each book will have a 1-5 rating I can browse from.
- As a user I can review each book.
- Login Page: After a user logs in, they'll be directed to a home page.
- Navigation: Navigation is present on all pages, Users should know what page is active by clicking on a nav link and activating their tab.
- Home Page: Contains a list of Books laid out in a grid format.
- Single Book Page: Loads information about the book, Author, Name, Publisher and a scrolling list of reviews. - Add review and delete book buttons present.
- Single Book Add Review Page: Clicking add review brings up a form (could be modal, could be its own page) where a user can add their review of the book. Clicking submit adds the review to the books information. **Stretch Goal: Add a way for user to rate each book "visually" with `stars`**
- Delete Book: Modal confirming the action, on confirmation user is routed back to the home page and book is gone from the list of books.
- Data Modeling: Each book has a
	- Title: String
	- Author: String
	- Publisher - String
	- Reviews- Array of Objects field. The reviews object shape should be:
		-  Reviewer: String
		-  Review: String
​
**Stretch Goal: A link to each book will take the user to another site (Amazon, Chegg, Half-Price Books, etc.) where they can purchase a book and compare prices.**
