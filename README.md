# How The Web Works Lab: DNS, HTTP and Website Requests

## 1. Project Overview
This projects dives into what happens when a user enters a website address into a browser. The goal is to show how DNS, HTTP, browsers, web servers, and website files work together to load and display a webpage.

## 2. Simple Web Request Diagram
Example flow:
[User enters website URL] -> [Browser checks DNS] -> [DNS returns IP address] -> [Browser sends HTTP/HTTPS request] -> [Web server receives request] -> [Server sends back HTML, CSS, and JavaScript] -> [Browser renders webpage]

## 3. What DNS Does
DNS stands for Domain Name System. DNS converts-human readable domain names into IP addresses.

Example:
amazon.com -> 98.87.170.74

Without DNS, users would need to remember IP addresses instead of website names.

## 4. What HTTP Does
HTTP stands for Hypertext Transfer Protocol. HTTP is used by browsers and servers to request and send web content. A browser sends an HTTP request to a web server. The server responds with content such as HTML, CSS, JavaScript, images, or other files.

## 5. HTTP vs HTTPS
| Protocol | Meaning | Security |
|---|---|---|
| HTTP | Hypertext Transfer Protocol | Not encrypted |
| HTTPS | Hypertext Transfer Protocol Secure | Encrypted |

HTTPS is more secure because it protects data while it travels between browser and server.

## 6. Basic HTTP Request Example
```http
GET / HTTP/1.1
Host: example.com
User-Agent: Browser
```
This request asks the server for the homepage `example.com`.

## 7. Basic HTTP Response Example
```http
HTTP/1.1 200 OK
Content-Type: text/html

<html>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```
This response tells the browser the request was successful and sends back HTML content.

## 8. Common HTTP Status Codes
| Status Code | Meaning |
|---|---|
| 200 | OK/Request Success |
| 301 | Moved Permanently |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## 9. Website Building Blocks

## 10. Cybersecurity Takeaways

## 11. What I Learned

## References
- TryHackMe. "Introduction to Cyber Security." TryHackMe, [https://tryhackme.com/](https://tryhackme.com/module/how-the-web-works)

## Disclaimer
This project is for educational purposes only. It summarizes concepts learned through TryHackMe and does not include walkthrough answers, flags, or private room solutions.
