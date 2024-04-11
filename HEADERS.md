**Request Headers:**

- Accept - Media type acceotable for the response
- Authorization - Contains Credentials
- User agent - Information about the client making the request (eg Browser)
- Content Type - Specifies the media type of the request body when sending data (eg "application/json")**
- Accept  Specifies the media types that the client is willing to receive from the server.
- Accept-Encoding  Specifies the encoding algorithms that the client can understand.
- Accept-Language  Specifies the natural languages that the client can understand.
- Cache-Control - Directives for caching mechanisms in both requests and responses.
- Connection - Controls whether the network connection stays open after the current transaction finishes.
- Content-Length - The size of the request body in octets (8-bit bytes).
- Content-Type - The MIME type of the body of the request.
- Cookie  Contains stored HTTP cookies previously sent by the server with the Set-Cookie header.
- Host - The domain name of the server (for virtual hosting) and the TCP port number on which the server is listening.
- Origin - Indicates where a fetch originates from.
- Referer - The address of the previous web page from which a link to the currently requested page was followed.
- User-Agent - A characteristic string that lets servers and network peers identify the application, operating system, vendor, and/or version of the requesting user agent.**

 **Response Headers:**

- Date - Indicates the date and time when the response was generated.
- Server - Specifies information about the server software.
- Content-Type - Describes the type of content in the response body (e.g., text/html, application/json).
- Content-Length - Specifies the length of the response body in bytes.
- Cache-Control - Defines caching directives for both the browser and intermediary caches.
- Expires - Indicates the date/time after which the response is considered stale.
- Last-Modified - Specifies the date/time when the requested resource was last modified.
- Location - Used in redirections to specify the new location.
- Set-Cookie - Sets a cookie on the client's browser.
- Content-Encoding - Specifies the encoding applied to the response body (e.g., gzip, deflate).
- ETag - Provides a unique identifier for the current version of the requested resource.
- Access-Control-Allow-Origin - Specifies which origins are allowed to access the resource.
- WWW-Authenticate - Defines the authentication method that should be used to access the resource.
- Strict-Transport-Security - Instructs the browser to always use HTTPS for all future requests to the domain.
- X-Content-Type-Options - Helps to prevent MIME-sniffing attacks.
- X-Frame-Options - Protects against Clickjacking attacks by controlling if and how a page can be loaded within a frame.
- Content-Security-Policy - Defines security policies to prevent various attacks such as XSS.
- Referrer-Policy - Specifies how much referrer information should be included with requests.
- X-XSS-Protection - Enables the Cross-site Scripting (XSS) filter in the browser.
- Retry-After - Specifies how long to wait before making a new request after receiving a 503 (Service Unavailable) status code.

**General Headers**

**Entity Headers**

**Application types**

- application/json - This is used for JSON (JavaScript Object Notation) data. It's widely used for exchanging structured data between a server and a client.
- application/xml - This is used for XML (Extensible Markup Language) data. XML is another format for representing structured data, though it's less common in modern web development compared to JSON.
- application/octet-stream - This is a generic binary data type. It's often used when the data doesn't fit into any other specific category or when the specific type of the data is unknown or irrelevant.
- application/x-www-form-urlencoded - This is used for sending form data encoded as key-value pairs. This is commonly used in HTML forms.
multipart/form-data - This is used for submitting forms that contain files, transmitting files along with the form data.
- application/pdf - This is used for PDF (Portable Document Format) documents.
- application/msword - This is used for Microsoft Word documents.
- application/vnd.ms-excel - This is used for Microsoft Excel documents.
- application/javascript - This is used for JavaScript code files.
