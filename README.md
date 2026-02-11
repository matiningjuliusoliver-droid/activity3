# Markdown
# RESTful API-Activity- Julius Oliver M. Matining
**1.Why did we put BASE_URI in .env instead of hardcoding it?**
Answer: We put the BASE_URI in the .env file to keep sensitive configuration secure and to allow easy changes across different environments without modifying the source code.

**2.Why did we use plural nouns (e.g., /dishes) for our routes?**
Answer: We used plural nouns because RESTful APIs represent collections of resources, which makes endpoint naming consistent, standard, and easier to understand.

**3.When do we use 201 Created vs 200 OK?**
Answer: We use 201 Created when a new resource is successfully added to the server, while 200 OK is used when a request is successful but does not create anything, such as retrieving or updating data.

**Why is it important to return 404 Not Found instead of just an empty array or a generic error?**
Answer:Returning 404 Not Found clearly informs the client that the requested resource does not exist, preventing confusion and making error handling more accurate.


**why did i choose embed the [Review/Tag/Log]?**

Answer: I chose to embed the Review/Tag/Log because they are closely related to the main resource and are usually accessed together, which improves performance by reducing extra API calls

**why did i choose to reference the [Chef/User/Guest]**
Answer:I chose to reference the Chef/User/Guest because they are independent entities that can be used across multiple records, so referencing avoids duplicating their data and keeps the database normalized.





