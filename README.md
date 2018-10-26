# HotelBooking
**web app development assignment1**

<p>**Description:** This web is called hotel Booking. The aim of this web is to booking hotel online. It includes three schemas, bookings, rooms and customers. It can find all rooms in the database, and also a single room by specific roomNum. Rooms can be added and deleted. The room price can be increased by 5 by using the post method.</p>
<p>Customers can sign up and then their information will be stored in the database, and they can log in by using their email and passwords. Customers can be added and deleted. All the customer information can be found.</p>
<p>All booking information or just one booking can be listed. Besides, these bookings can also be deleted or added. There is a property called “amount”, it can be increased by 1. The number of all booking amount can be found.</p>

**Rooms:**<br>
Resource&nbsp&nbsp&nbsp&nbsp&nbspURI(structure)&nbsp&nbsp&nbspHTTP Request<br>
List of all Rooms&nbsp&nbsp&nbsp/rooms&nbsp&nbsp&nbspGET<br>
Get a single room&nbsp&nbsp&nbsp/rooms/{roomNum}&nbsp&nbsp&nbspGET<br>
Increase price&nbsp&nbsp/rooms/{id}/price&nbsp&nbsp&nbspPUT<br>
Add a Room&nbsp&nbsp&nbsp/rooms&nbsp&nbsp&nbspPOST<br>
Delete a Room&nbsp&nbsp&nbsp/rooms/{id}&nbsp&nbsp&nbspDELETE<br>

**Customers:**<br>
Resource&nbsp&nbsp&nbspURI(structure)&nbsp&nbsp&nbspHTTP Request<br>
Customer sign up&nbsp&nbsp&nbsp/customers&nbsp&nbsp&nbspPOST<br>
Customer log in&nbsp&nbsp&nbsp/customers/{email}&nbsp&nbsp&nbspPOST<br>
List of all Customers&nbsp&nbsp&nbsp/customers&nbsp&nbsp&nbspGET<br>
Get a single Customer&nbsp&nbsp&nbsp/customers/{customerID}&nbsp&nbsp&nbspGET<br>
Delete a Customer&nbsp&nbsp&nbsp/customers/{id}&nbsp&nbsp&nbspDELETE<br>

**Bookings:**<br>  
Resource&nbsp&nbsp&nbspURI(structure)&nbsp&nbsp&nbspHTTP Request<br>
List of all Bookings&nbsp&nbsp&nbsp/bookings&nbsp&nbsp&nbspGET<br>
Get a single Booking&nbsp&nbsp&nbsp/bookings/{id}&nbsp&nbsp&nbspGET<br>
Delete a Booking&nbsp&nbsp&nbsp/bookings/{id}&nbsp&nbsp&nbspDELETE<br>
Increase amount&nbsp&nbsp&nbsp/bookings/{id}/amount&nbsp&nbsp&nbspPUT<br>
Add a booking&nbsp&nbsp&nbsp/bookings/{customerID}&nbsp&nbsp&nbspPOST<br>
Total of Booking amount&nbsp&nbsp&nbsp/bookings/amount&nbsp&nbsp&nbspGET<br>

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


