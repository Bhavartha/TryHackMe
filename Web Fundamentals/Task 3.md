## More HTTP - Verbs and request formats 

<br/>

### Q1) What verb would be used for a login?
**Answer: `POST`**

**Explaination:** \
We use POST request to send data to the server. In POST request, the data doesnt appear in the url. So using POST method over GET is more suitable in this case


<br/>

### Q2) What verb would be used to see your bank balance once you're logged in?
**Answer: `GET`**

**Explaination:** \
We can use GET method to request data from a webserver


<br/>

### Q3) Does the body of a GET request matter? Yea/Nay
**Answer: `Nay`**

**Explaination:** \
Body of GET request is mostly ignored by the server

<br/>

### Q4) What's the status code for "I'm a teapot"?

**Answer: `418`**

**Explaination:** \
The HTTP 418 I'm a teapot client error response code indicates that the server refuses to brew coffee because it is, permanently, a teapot.\
A combined coffee/tea pot that is temporarily out of coffee should instead return 503.\
This error is a reference to Hyper Text Coffee Pot Control Protocol defined in April Fools' jokes in 1998 and 2014.\
Some websites use this response for requests they do not wish to handle, such as automated queries.

<br/>

### Q5) What status code will you get if you need to authenticate to access some content, and you're unauthenticated?
**Answer: `401`**

**Explaination:** \
The HTTP 401 Unauthorized client error status response code indicates that the request has not been applied because it lacks valid authentication credentials for the target resource. \
This status is sent with a WWW-Authenticate header that contains information on how to authorize correctly.

