# Http Response Categories
There are 5 categories used to group the HTTP Response
## Categories
- Information responses [100 - 199]
- Successful responses [200 - 299]
    - 200 ok
    
        The HTTP response status code 200 is the standard response for successful HTTP request
        The sever responded with "OK" to indicate that the request was successful
    - 201 created
    
        The HTTP response code 201 means that the request is successful and that a new resource has been created
        It is often the case when a new file or directory is uploaded to a web server
    - 202 Accepted
    
        It means that the sever has accepted the request. but the processing has not been completed
        It is used when the client does not need to wait for the processing to finish before continuing
    - 204 No Content
    
        HTTP response status code 204 indicates that the server has successfully processed the request and that there is no content to return
        This is no often used when a request is made to update an existing resource, such as when updating a record in a database.
- Redirection message [300 - 399]
    - 301 Moved Permanently
    
        It means that the resource you are trying to access has been moved permanently. it is usually the result of a website redesign or change in URL.
    
    - 302 Found
        
        The HTTP response status code 302 is similar to status 301, showing that the resource has been moved
        However, unlike status 301, the status code 302 indicates that the redirect is only temporary.
    
    - 304 Not modified
        It indicated that previously cached response can be reused, as the requested resouce has not been modified
        This can improve preformance, as the client does not need to re-download the resouce
- Client error responses [ 400 - 499]
    - 400 Bad request
        
        This HTTP response code means that the server could no understand the request due to invalid syntax
        It is often caused by a client error, such as a malformed URL.
    
    - 401 Unauthorized
        
        It indicates that the client is not authorized to access the requested resource.
        It is usually due to an invalid or missing authorization header.
    
    - 403 Forbidden
        
        It indicates that the client is not authorized to access the requested resource.
        It is usually due to a lack of permissions
    
    - 404 Not Found
        
        It is an error message that means the page you are looking for could not be found.
        This can be due to several reasons, such as a typo is the URL or the page being moved or deleted.
    
    - 405 Method Not Allowed
    
        The HTTP response code 405 indicates that the request method is not allowed for the requested resouce.
        It is usually due to a problem with the server configuration
- Server error responses [ 500 - 599]
