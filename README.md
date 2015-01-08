# docker-HockeyKit

* go to the repository in which you have pulled current version of the project.
* run the command: docker build .

in case of a successful buid run:

* docker run -it --rm -p 11080:80 <BUILD-ID>

Test if HockeyKit server is running properly. Open a browser and go to:

http://localhost:11080/index.php

You should see a page with the topic: "App installation"

