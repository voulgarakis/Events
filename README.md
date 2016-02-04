ASP.NET MVC - Events Management Application

Events have title, start-date and start-time. Events may optionally have duration, description, location and author. Events can be public (visible by everyone) and private (visible to their owner author only). 

Anonymous users (without account) can view all public events. The home page displays all public events, in two groups: upcoming and passed. Events are shown in short form (title, date, duration, author and location) and have a [View Details] button, which loads dynamically (by AJAX) their description and [Edit]/[Delete] buttons.

Anonymous users can register in the system and login/logout. Users should have mandatory full name, email and password. User’s email should be unique. User’s password should be non-empty and should be at least 6 characters long.

Logged-in users should be able to view all public events, to create new events, edit their own events and delete their own events.

 A special user "admin@admin.com" should have the role "Administrator" and should have full permissions to edit/delete events.