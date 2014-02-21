Secure-Services
===============
This module adds HTTP basic authentication to the Services module.It allow access to only those users that have permission set for this module.

Installation
------------
Unpack the module and place the secure_services folder in your site's
module directory (e.g. sites/all/modules).
Set permission for the role that you want to access services.

To Test:

http://user:password@example.com/endpoint/

Replace
user/password with your user credentials ...
example.com with your site url
endpoint with your services endpoint you have made.
