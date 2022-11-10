# MongoDB (NetNinja)

## What is MongoDB?

First of all, it is a "NoSQL" (non-'relational') database (unlike PostgreSQL & MySQL):

1. You can't use SQL commands to interact with it
2. It doesn't store data in a "relational" way:
   - Where in a SQL database, your "User" & "Blog Post" or "Author" & "Books/Written Works" tables would be connected through an ID - maybe blog posts each have one user/one user ID

Second, it is a database system that JavaScript developers will find more familiar:

1. _Instead_ of storing data in a relational way, it stores it in 1. '_collections_' of 2. '_documents_' (records). These documents are structured very-much like JSON Objecects (with K:V pairs)

   {
   "title": "2001: a Space Odysee",
   "director": "Stanley Kuberic",
   "date_of_release": "1968, April 6 ",
   "mainActors": [
   {
   "first_name": "Keir",
   "last_name": "Dullea",
   "characters": "David Bowman"
   },
   {
   "first_name": "Gary",
   "last_name": "Lockwood",
   "characters": "Frank Poole"
   },
   {
   "first_name": "Douglas",
   "last_name": "Rain",
   "characters": "Hal 9000"
   },
   ]
   }

2. Querying this kind of a database is much easier for a JS developer, because of the pre-exisitng methods & structures held in common.
