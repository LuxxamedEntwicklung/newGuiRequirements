We need to setup a singlePage Server which is not servicing url services to the browser but setting a one page application which is behavong on Windows, macOS, Linux and Android like an Application.

Otherwise we would risk that the server could be touched via url breaking. To service the entire security there shall not be any url service inside served.

We provide therefore  certificatr server which generates new certificates when needed to provide certs for ssl security in Browser.

The Webserver needs a load balancer which sets Load to one User per jvm.

The JVM has to look if there is another active jvm blocking the login while existing.

The Jvm has to be secured so there shall be no file system access from outside via the web server. Downloads and Uploads shall be allowed only over the system.

The ssh functionality shall be switched on and off via the software when a user is logged in which has admin privileges on the system.

The server shall be an nginx serverr with no file repository

Webserver is based on NBfxml example with JPro maven repos and JPro base features

last edited 21.09.2025, Thorsten Stüker
