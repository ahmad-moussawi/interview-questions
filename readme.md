## Backend
- What is the CSRF attack, and how to prevent it? [5min]. 
- What is the difference between compiled language and interpreted language with examples [5min].

- How to implement a full text search within your webapp [5min] 
  > I expect the candidate to tell me about available technologies, and search engine availables like ElasticSearch, fulltext search, and when to use the relational db for this
  
- You've asked to implement a caching mechanism for a webapp, how would you do it.
  > I expect to hear about caching layers, strategies, and mediums like Redis, memcached, distributed cache, etc ...
  
- What is the difference between Yaml and JSON 
- How to scale up your application in terms of availability

- What is text encoding
- How to store DateTime in database for a Reminder (Summary Report every Monday at 3PM)
- When to use UTC to store Date in database
- What is the difference between List and Enumerable?

## CSharp
- What are the main differences between .net framework and .net core
- What is the difference between `Scoped` and `Transient` (scoped to the request)
- How do you compare two string in C# in a case insensitive way? [2min]
- What are expression trees [3min]
- When do you prefer to use an ORM/vs Non ORM?
- When do you use Stored Procedures?
- What is reflection

## EntityFramework
- What does `AsNoTracking()` method in EntityFramework
- When do you use Lazy Loading, and is it recommended?
- What is the discriminant
- When not to use Entity Framework?

## Database
- Is there any performance benefit from using Views
- Optimistic vs Pessimistic transactions
- write an SQL query to get the amount of the last transaction for each account

```sql
Id, Account, Date, Amount
1, A1, 2021-01-01, 500
2, A1, 2021-02-01, 800
3, A1, 2021-03-01, 700

4, A2, 2021-01-01, 400
5, A2, 2021-03-01, 750
6, A2, 2021-02-01, 850

-- expected output

A1, 700
A2, 750

```

## Front End / Web
- Can you explain to me what is `Promise` in JavaScript
- What is the difference between `LocalStorage` and `SessionStorage`
- What is the difference between `querySelector` and `querySelectorAll` 
- How to center a div in a page
- What is the difference between absolute/relative position
- How to detect if an element is visible within the view port in the screen
- What is the different between LocalStorage and SessionStorage?
- How to make an ajax call using JavaScript (without using external libraries)
  > I expect the candidate to tell me about XMLHttpRequest and fetch methods
- What is the difference between TypeScript/JavaScript? 

## Angular
- How to implement site tracking across the whole app
  
  > I expect a solution without changing the actual code, i.e. applying a global directive
