# HotelBooking
**web app development assignment1**

<p>**Description:** This web is called hotel Booking. The aim of this web is to booking hotel online. It includes three schemas, bookings, rooms and customers. It can find all rooms in the database, and also a single room by specific roomNum. Rooms can be added and deleted. The room price can be increased by 5 by using the post method.</p>
<p>Customers can sign up and then their information will be stored in the database, and they can log in by using their email and passwords. Customers can be added and deleted. All the customer information can be found.</p>
<p>All booking information or just one booking can be listed. Besides, these bookings can also be deleted or added. There is a property called “amount”, it can be increased by 1. The number of all booking amount can be found.</p>

**Rooms**<br>
Resource               URI(structure)          HTTP Request<br>
List of all Rooms          /rooms                GET<br>
Get a single room          /rooms/{roomNum}      GET<br>
Increase price             /rooms/{id}/price     PUT<br>
Add a Room                 /rooms                POST<br>
Delete a Room              /rooms/{id}           DELETE<br>

**Customers:**<br>
Resource                URI(structure)       HTTP Request<br>
Customer sign up        /customers               POST<br>
Customer log in	       /customers/{email}        POST<br>
List of all Customers   /customers               GET<br>
Get a single Customer   /customers/{customerID}  GET<br>
Delete a Customer       /customers/{id}	         DELETE<br>

**Bookings:**<br>
Resource                URI(structure)       HTTP Request<br>
List of all Bookings     /bookings               GET<br>
Get a single Booking     /bookings/{id}          GET<br>
Delete a Booking         /bookings/{id}          DELETE<br>
Increase amount          /bookings/{id}/amount   PUT<br>
Add a booking            /bookings/{customerID}  POST<br>
Total of Booking amount  /bookings/amount        GET<br>


<p>**Persistence approach:** Though the process is finished, data still exist by using mongoDB. Rooms, customers and booking information are all stored in the mongoDB to achieve persistence.</p>

<p>**Developer experience approach:** I have recorded a video and upload it to YouTube to show what can this hotel booking website do. And besides, all the codes are uploaded to GitHub. This README file also help to describe my website and also lists the URIs to help you know how to test it.</p>
<p>**GitHub:** https://github.com/Hinnn/HotelBooking</p>

**Reference:** <br>
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/<br>
https://developer.mozilla.org/zh-CN/docs/learn/Server-side/Express_Nodejs/mongoose<br>
https://blog.csdn.net/songrenqing/article/details/80629832<br>
https://segmentfault.com/a/1190000008245062<br>
https://www.cnblogs.com/y-yxh/p/5859937.html<br>
https://www.cnblogs.com/ywang1724/p/3917085.html<br>
https://blog.csdn.net/zxhandroid/article/details/75777850<br>
https://www.cnblogs.com/shiy/p/6526868.html<br>
https://blog.csdn.net/jiadabin/article/details/51745928<br>


**YouTube link:** https://youtu.be/Q9Ys5aaOBqU<br>


