jsBookmark
==========

A JavaScript library for hash-based bookmarks.

Description
-----------

This library allows to store and read URL bookmarks based on the hash part. It is ideal to share the current status of AJAX-based applications, and to have browser history support in such applications. It offers two different behaviours:
  * Complex status: If the developer wants to bookmark complex application status 
    (JSON objects) the library must save this status encoding it in Base64 format. 
    Therefore, the generated bookmark will be an unreadable string. The 
    __encoded.html__ example shows how it works.
  * Simple status: If the developer only wants to bookmark the different sections of
    an application (*#main*, *#about*, etc.) the status is saved literally, without
    encoding it. The __literal.html__ example shows it.


Usage
-----
  See the different examples. The full documentation of the API is coming.
