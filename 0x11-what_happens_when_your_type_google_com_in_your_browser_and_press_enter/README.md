0x11. What happens when you type google.com in your browser and press Enter
---
This repository is an attempt to answer the age-old interview question "What happens when you type google.com into your browser's address box and press enter?"

Except instead of the usual story, we're going to try to answer this question in as much detail as possible. No skipping out on anything.
Behind the Scenes: What Happens When You Enter a URL
Have you ever wondered what magic happens when you type a URL into your browser and press Enter? What seems like a simple action actually triggers a fascinating and intricate journey behind the scenes? Let's take a delightful dive into this process:
DNS Lookup: Translating Names to Addresses
Imagine the internet as a vast city, and every website is a house with a unique address. When you type "https://www.google.com," your computer consults a DNS server, which acts like a city directory. This server translates the easy-to-remember domain name into an IP address, guiding your request to the correct house on the web.
TCP/IP: The Internet’s Delivery System
Now that your computer knows the address, it uses TCP/IP protocols to establish a connection. Think of TCP as a meticulous courier that breaks your data into small packets, delivers them safely, and reassembles them at their destination. Meanwhile, IP is the smart navigator, ensuring each packet takes the best route through the internet's bustling network.
Firewall: The Security Guard
As your data packets journey through the internet, they might encounter firewalls, the vigilant security guards of the digital world. Firewalls examine incoming and outgoing traffic, ensuring that only safe and authorized packets reach their destination, keeping malicious intruders at bay.
HTTPS/SSL: The Bodyguard of Your Data
When you see "https" in a URL, it’s like having a bodyguard for your data. HTTPS, secured by SSL, creates an encrypted tunnel between your browser and the server. This encryption ensures that your sensitive information, like passwords and credit card details, remains safe from prying eyes.
Load Balancer: The Traffic Director
Large websites like Google handle massive amounts of traffic. Enter the load balancer, the clever traffic director that distributes incoming requests across multiple servers. This prevents any single server from getting overwhelmed, ensuring smooth and efficient operation.
Web Server: The Content Provider
Once your request reaches the right server, the web server springs into action. It retrieves the necessary web pages and resources (text, images, videos) from its storage and prepares them for delivery back to you.
Application Server: The Dynamic Content Creator
For websites that offer dynamic content, the application server is the star. When you search for something on Google, the application server fetches the search results from a database, dynamically creating a personalized webpage just for you.
Database: The Treasure Chest of Information
Websites often rely on robust databases to store and manage vast amounts of information. When you perform a search, the application server queries the database to retrieve the most relevant results, ensuring you get the best information possible.
Rendering the Page: Bringing It All to Life
Finally, the web server sends the gathered data back to your browser. Your browser then gets to work, interpreting the HTML, CSS, and JavaScript to render the webpage, displaying the content beautifully on your screen.
The Journey Ends, But the Web Keeps Flowing
This complex dance between your computer, servers, and network protocols brings the internet to life, allowing you to access information seamlessly. Next time you browse the web, remember the intricate journey that makes it all possible, and appreciate the marvel of technology at your fingertips. Happy surfing!

