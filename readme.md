PROJECT:Library management system
Designed to manage a library service system. At the book level, customer, and loans.
The app is built from advanced data base. To which give the user the option to enter data of
Book: View all books, search for an existing book, remove a book from the repository, and enter a new book with the specific information for loan book (which us:type 1 is for 10 days,type 2 for 5 days and type 3 for 2 days)
customers: View all directory customerss, add a new customers, search a customers, and remove a customers.
 loans: View all borrowed books, book loan to customer, book return, view book level data if it is late.

Name Data base: Library.db
class: 1) books 2)customers 3)loans

3 tables:
1)books           2)customers     3)Loans
  id(PK)         customerid(PK)     CustID
  bookName          Name            bookID
  Author            City            Loanbook
  yearPublished     Age             Returbook
  type(1/2/3)
  loanstatus
  

            all the urls

     /:check box "hello world"
  HOME:/display  "the BOOKS HOME"
 BOOKS:/books  
          addnewbook:
          displayallbooks:
          findbook  by  name (findbook:)
          removebook:

 customers:/customers
          addnewcustomer:
          displaycustomers:
          findcustomer:
          removecustomer:

      loans:/loans         
           loanbook:
           returnbook:
           display_all_loans:
           display_late_loans:  





