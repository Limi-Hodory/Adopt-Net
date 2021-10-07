# Adopt-Net
Hello everybody,

I'm excited to present my final "Advanced Web Application Development" project done with Amit Ben Basat and Liem Mazal as part of our B.Sc Computer Science studies.

During the project I had to work with different technologies and programming languages, including:

# Technologies and Logic :bulb:
- Frontend technologies: JavaScript, HTML, CSS.
- Backend: C#.NET, ASP and Microsoft SQL.
- Additional Libraries and Frameworks: Bootstrap, jQuery, Charts.js, etc...

# Additional Description:
-	The backend application is build based on ASP.NET using the MVC design pattern.
-	Using 7 main models including: animals, organizations, adopting days, pictures of animals and organizations, etc...
-	3 different main connections between the models: Many to many - each association can have several adoption days, and each adoption day can have several organizations that take a part in this day. One to one - each organization and animal has it's own one of a kind picture, each animal can have a unique product. One to many - each organization can have several animals.
-	Support in Listing, Creating, Deleting, Modifying and Searching.
-	The DB is based on Entity Framework and accessed using Linq.
-	Using "Group By" query - to sort all animals accroding to the organization that they belong to.
- Using "Join" query - combine two tables, therefore creating a new one, each for the index of the animals and the index of the products.
- JQuery - using Ajax and js to create Bing map that shows each association's location, and to create 2 graphs that show number of dogs vs number of cats and distribution of adoption days.
- JS - we use js to create a weather widget.
- Twitter API - creating controller with GET and POST requests using speacial keys values to connect to our developers account on twitter. When an animal is added - it is also tweeted on our twitter account.
- Authorization - Creating 3 types of authorities - "Client", "Association", and "Administrator".
