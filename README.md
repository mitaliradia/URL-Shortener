# URL-Shortener
1st Node.js mini project

Designed a URL shortener service that takes in a valid URL and returns a shortened URL, redirecting the user to the perviously provided URL.

Also, keeps the track of total visits/clicks on the URL.

Routes

POST /URL - Generates a new short URL and returns the shortened URL in the format example.com/random-id.

GET /:id - Redirects the user to the original URL

GET /URL/analytics/:id - Returns the clicks for the provided short id


