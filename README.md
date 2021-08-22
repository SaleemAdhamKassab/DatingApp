# DatingApp
- Introduction:

Building a dating web application using ASP.NET Core Web API, Entity Framework Core & Angular from scratch.

This will include the ability for users to register, log in, and authenticating the site using JSON web token.

To take a look at how the website works, please follow the below links:

Demo video:

https://drive.google.com/file/d/1W_0olIfKFGfMPs676uczUbwcCfzjSvn7/view?usp=sharing

My Git Hub to check the source code: 

https://github.com/SaleemAdhamKassab/DatingApp



- We have three levels for users:
1.	Member :

Register on the application and will automatically forward them to the home page.

Make a lot of filters options by (age, gender, last active, and newest member) 

View other users' profiles including a photo gallery, send them private messages with an unread status until the other user read it

Like other users, one time and check his likes history 

Check unread, inbox, outbox, and reply or delete their messages

update their own profiles and show a warning message about the loss of their updates in case they moving to another link or closing the browser without pressing the “Save changes” button

along with, users will be able to update their own profiles and show a warning message about the loss of their updates in case they moving to another link or closing the browser without pressing the “Save changes” button

Upload multiple photos after approving the admin -except the first one- he can set it as the main profile picture or delete it (using "Cloudinary: Cloud Service Provider") as a photo storage solution.


2.	Admin :

The admins had permission on a Control Panel menu: 

Edit user's permissions on the application to (Admin, Moderator, or member)

Approving or delete user's photo upload requests

3.	Moderator :

Approve or delete user photo upload requests to reduce the load on the admin and share some administrative tasks

-  	Used Technology :

1.	The main protagonists:

      a.	Angular CLI version: 12.1.0
   
      b.	ASP.NET Core Web API version: 5.0.301
   
      c.	Microsoft Entity Framework Core version: 5.0.3
   

2.	Supporting Cast:

    a.	HTML

    b.	CSS

    c.	Bootstrap

    d.	Node.js

    e.	Databases:

     SQLite: Development

     MySQL: Production

    f.	Git

    g.	Cloudinary: using cloud provider as a photo storage solution, is great because this is typically a very scalable solution and it's not going to affect it's not going to impact the storage on our web server or our database.


If it was helpful please press a star :)



