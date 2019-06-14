1.  Explain the differences between `client-side routing` and `server-side routing`.

    Server-side routing is where pages are stored on an external server. Each time a new page is requested by the user, a GET request is sent to the server for the data and new page is loaded. This causes a refresh and the old page is discarded completely. Server-side routing is also preferable for SEO. Client-side routing is when javascript handles all the routing within the page. A new page is rendered when a user requests one, but a request is never sent to the server. The page will not refresh. Client-side is not optimal for SEO and there are parts of the website that might be loaded that never get used.

1.  What does HTTP stand for?

    Hypertext Transfer Protocol

1.  What does CRUD stand for?

    Create Read Update Destroy

1.  Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.

    GET: A GET request is sent to a server to point to the where the data will be coming from or what it will be "read"-ing.

    POST: this request is used to tell the server to add or "create" new pieces of a web page.

    PUT: this is used to "put" new data on the server

    DELETE: removes or "deletes" data from the server

1.  Mention three tools we can use to make AJAX requests

    Axios: is promised based and for the client

    Fetch: has a global method for getting resources

    request: is the simplest ways to make calls
