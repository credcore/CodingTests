# Backend Coding Tests
Common Coding Tests for Developers.

Please attempt any *ONE* of the following tests.
You could create a repo (public or private) on GH, and share access so that we can review it.
Alternatively, you may send us the source code in zipped format.

Note: We expect you to spend close to 2-4 hours on this. 
- So a few things being incomplete, or erroneous is totally OK!
- Not looking for fully working code. Placeholder methods are fine.

### Useful Resources

1. Swagger Editor: https://editor.swagger.io/
2. Public APIs: https://github.com/public-apis/public-apis

### 1. Movie Ticket Booking

1. Design a Swagger/Open REST API for Movie Ticket Booking (do not implement)
2. Design a database schema for the same (Relational DB preferred). It should have Users, Bookings, Shows, Seats etc.
3. Please use the Swagger Editor linked above, or any other.
4. Implement any one API in the list end-to-end (from WebService to DB)

### 2. Crypto Bank

Imagine we're a small Bitcoin Bank, which has loaned money (in BTC, or any other Crypto Currency) to several people.
They are all expected to pay you 1/12th of the amount every month. You have their Bitcoin addresses, as well as your own address.

Implement a system which runs on the last day of the month, which:
1. Sends them a thank you note if the amount has been paid
2. Or Send an alert if money is unpaid.
3. Use any free Bitcoin API
4. Create DB tables you need (Loans table, Account table etc)
5. For sending just assume a sendEmail() API exists - doesn't need to do anything.
6. DO NOT implement any payments API etc. Just assume all of them already exist, and that they have written necessary data to your DB.

### 3. Delivery Optimization

We have a set of warehouses, each having location co-ordinates and inventory details.

1. Implement an "orders" API, which supplies a customer from the nearest warehouse. 
2. The warehouse should have the necessary stock.
3. The order may be for one or more units, but for a single item.
4. Create any tables that you might need.

### 4. Barter

1. Design a Swagger/Open REST API for Barter Website (do not implement)
2. Design a database schema for the same (Relational DB preferred). It should have Users, Listings, Trades etc.
3. Please use the Swagger Editor linked above, or any other.
4. Implement any one API in the list end-to-end (from WebService to DB)

### 5. GraphQL

1. There's a hacker news rest API at https://github.com/HackerNews/API
2. Create a GraphQL version of this API
3. Implement a tiny part of the API (as an example of what implementation would look like). 

