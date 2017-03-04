---
layout: post
title: Equipment Tracking web application
description: Simple CRUD application with basic user authentication system for internal equipment tracking.
keywords: cured application, php application, datatables, equipment tracking web app, crud ajax web application
tags: [PHP, CRUD, AJAX, DataTables, Web Application]
comments: true
---

A couple of weeks ago I was asked to gather and compile a list of equipment that have been borrowed by a group of engineers and the list I received is in MS Excel file. So, I thought instead of waiting them to send me the list file once in a year, I should create a simple web application where they can easily update the equipment info anywhere and anytime - live update. Then, I decided to spend few times to write this simple web application called Equipment Tracking (Etrac).

Technically, Etrac is built from scratch using [DataTables](https://datatables.net/), [jQuery](https://jquery.com/), [PHP](http://php.net/), [MySQL](https://www.mysql.com/) and [Bootstrap](http://getbootstrap.com/) with [Google-style theme](https://todc.github.io/todc-bootstrap/). Etrac uses a very simple user authentication module that I created before in PHP for use in other old projects. Now with this web app, whenever I need the latest list of borrowed equipment, I can just go to the app URL (set to intranet accessible only) and export or print the list as the user can easily update the equipment info to the latest info. Etrac supports exporting to PDF, Excel and CSV file format.

### Equipment Tracking (Etrac) v1.0 Screenshots

![Screenshot1](http://i.imgur.com/dzJf6Wy.png)
*Figure 1 (above): List of equipment displayed using DataTables jQuery plugin without user login.*

![Screenshot2](http://i.imgur.com/U0KobRL.png)
*Figure 2 (above): Login page.*

![Screenshot3](http://i.imgur.com/Lsx4JkX.png)
*Figure 3 (above): List of equipment with logged user. If the user has the right permission given, the user can click CRUD buttons such as "Add new record", "Batch delete..." or "Update" button.*

![Screenshot4](http://i.imgur.com/xyXCltl.png)
*Figure 4 (above): Adding new record via Modal dialog.*

![Screenshot5](http://i.imgur.com/s2Sud2z.png)
*Figure 5 (above): When user clicks on delete button, a confirmation will pop up to double-confirm before the delete action can be performed.*

![Screenshot6](http://i.imgur.com/ulkAEDG.png)
*Figure 6 (above): Search or filter can be performed easily when using this DataTables jQuery plugin.*

![Screenshot7](http://i.imgur.com/TTdjjVV.png)
*Figure 7 (above): Super simple user profile settings page.*

![Screenshot8](http://i.imgur.com/sluB9Lk.png)
*Figure 8 (above): List of registered users.*
