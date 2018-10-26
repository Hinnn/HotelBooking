# HotelBooking
web app development assignment1
Name: Yue Wang
Student ID: 20082242

Description: This web is called hotel Booking. The aim of this web is to booking hotel online. It includes three schemas, bookings, rooms and customers. It can find all rooms in the database, and also a single room by specific roomNum. Rooms can be added and deleted. The room price can be increased by 5 by using the post method.
Customers can sign up and then their information will be stored in the database, and they can log in by using their email and passwords. Customers can be added and deleted. All the customer information can be found.
All booking information or just one booking can be listed. Besides, these bookings can also be deleted or added. There is a property called “amount”, it can be increased by 1. The number of all booking amount can be found.

Rooms
Resource	        URI(structure)	     HTTP Request
List of all Rooms	/rooms	                GET
Get a single room	/rooms/{roomNum}	GET
Increase price	        /rooms/{id}/price	PUT
Add a Room	        /rooms	                POST
Delete a Room	        /rooms/{id}	        DELETE

Customers:
Resource	        URI(structure)	      HTTP Request
Customer sign up 	/customers	         POST
Customer log in	        /customers/{email}	 POST
List of all Customers	/customers	         GET
Get a single Customer	/customers/{customerID}	 GET
Delete a Customer	/customers/{id}	         DELETE

Bookings:
Resource	         URI(structure)	      HTTP Request
List of all Bookings	 /bookings	         GET
Get a single Booking	 /bookings/{id}	         GET
Delete a Booking	 /bookings/{id}	         DELETE
Increase amount	         /bookings/{id}/amount	 PUT
Add a booking	         /bookings/{customerID}	 POST
Total of Booking amount	 /bookings/amount	 GET

Persistence approach: Though the process is finished, data still exist by using mongoDB. Rooms, customers and booking information are all stored in the mongoDB to achieve persistence.

Developer experience approach: I have recorded a video and upload it to YouTube to show what can this hotel booking website do. And besides, all the codes are uploaded to GitHub. This README file also help to describe my website and also lists the URIs to help you know how to test it.
GitHub: https://github.com/Hinnn/HotelBooking

Reference: 
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/
https://developer.mozilla.org/zh-CN/docs/learn/Server-side/Express_Nodejs/mongoose
https://blog.csdn.net/songrenqing/article/details/80629832
https://segmentfault.com/a/1190000008245062
https://www.cnblogs.com/y-yxh/p/5859937.html
https://www.cnblogs.com/ywang1724/p/3917085.html
https://blog.csdn.net/zxhandroid/article/details/75777850

YouTube link: https://youtu.be/Q9Ys5aaOBqU


