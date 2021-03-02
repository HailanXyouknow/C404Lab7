## Questions
Question 1: How are Flask and Django different? What does Django provide for you that Flask does not?

    Flask supports API by default. Django needs packages (e.g. Django Rest Framework)
    in order to support API.

Question 2: What does REST stand for? When I say something is RESTful, what does that mean?

    REST = Representational State Transfer
    RESTful means it is stateless and each HTTP request is separate.

Question 3: What does CRUD stand for? For each letter in CRUD, give the associated HTTP method.
    C = Create
    R = Read
    U = Update
    D = Delete

Question 4: What do HTTP 1XX Status Codes mean? HTTP 2xx? HTTP 3xx? HTTP 4xx? HTTP 5xx?

    HTTP 1XX - Informational
    HTTP 2XX - Success
    HTTP 3XX - Redirection
    HTTP 4XX - Client Error
    HTTP 5XX - Server Error

Question 5: What is an XSS attack? Provide one way a site can be vulneratble to an XSS attack.

    XSS (cross-site scripting) attack is when people inject scripts to your website (often to do malicious things).

    If a site interprets things like <script> as html tags instead of text, then it is vulnerable to XSS attacks.


Question 6: What does CORS stand for? What situation in web application development will you need to implement CORS?

Hint: What does the CO part of CORS mean?

    CORS = Cross-Origin Resource Sharing
    It allows another domain access to some of the resources in our domain
