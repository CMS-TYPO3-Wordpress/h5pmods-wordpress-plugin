# H5P Mods wordpress plugin

This WordPress plugin is provided as an example of how you can use the actions
provided by the H5P plugin. The actions are used for altering or adding
H5P content or library resources.

Feel free to fork this project or simply use it as a template for doing your
own custom modifications to H5P.

You should be aware that the hooks you add on your site will not follow
the content if it's exported.

## Issues
* [artefact_rub_de](https://git.noc.ruhr-uni-bochum.de/artefact-kgi/artefact_rub_de/-/issues)

## Moodle
* [Moodle: ArtEfact (040627-WiSe16/17)](https://moodle.ruhr-uni-bochum.de/m/course/view.php?id=7168)

## Deployment

### Live-System
* [https://artefact.ruhr-uni-bochum.de](https://artefact.ruhr-uni-bochum.de/)
### Staging-System
* [https://artefact.ruhr-uni-bochum.de/qa](https://artefact.ruhr-uni-bochum.de/qa/)
### Live-System
* [https://localhost/](https://localhost/)

## Features

### Functional Requirements
* F001: H5p 
* F002: SSO: login with RUB-LDAP Account for the corresponding Moodle Course
* F003: Layout: RUB-Webfonts and Six Colors-Schemes on Page-Level
* F004: Backend: Editor shall choose one of the six color-schemes while editing a Page.
* F005: Color Schemes on Page-Level shall be inherited to h5p content elements
* F006: Some Pages shall only be visible and accessable for logged in Users. 
* F007: Pages only be visible and accessable for logged in Users shall not be seen in menus for not logged in visitors
* F008: A Moodle-User in the dedicated Moodle-Course shall see and use pagecontent via iframe and userfriendldy SSO.  

### Nonfunctional Requirements
* T001: URL artefact.rub.de and artefact.ruhr-uni-bochum.de
* T002: Webspace/Serverspace: V-Server LAMP by IT-Services RUB
* T004: SSL-Certificate for https
* T005: VMWare-V-Server, Ubuntu-Linux-Server, Apache2, PHP, MySQL, Wordpress
* T006: Server and Worpress shall be able to send Email
* T007: Backup and Restore of the V-Server by IT-Services
* T008: Interface to LDAP for SSO

## Milestones
* 0.0.1 Release Dec 1, 2019–Mar 31, 2020
* 0.0.2 Release Apr 1, 2020–Apr 30, 2020
* 0.0.3 Release May 1, 2020–May 15, 2020
* 0.0.4 Release May 16, 2020–May 31, 2020
* 0.0.5 Release Jun 1, 2020–Jun 15, 2020
* 0.0.6 Release Jun 16, 2020–Jun 30, 2020
* 0.0.7 Release Jul 1, 2020–Jul 15, 2020
* 0.0.8 Release Jul 16, 2020–Jul 31, 2020
* 0.0.9 Release Aug 1, 2020–Aug 15, 2020
* 0.0.10 Release Aug 16, 2020–Aug 31, 2020
* 0.0.11 Release Sep 1, 2020–Sep 15, 2020
* 0.0.12 Release Sep 16, 2020–Sep 30, 2020

## Other Gitlab Repos 
* [artefact_rub_de_redaktion](https://git.noc.ruhr-uni-bochum.de/artefact-kgi/artefact_rub_de_redaktion/-/issues)
* [artefact_rub_de_localdev](https://git.noc.ruhr-uni-bochum.de/artefact-kgi/artefact_rub_de_localdev/-/issues)
* [twentytwenty-child](https://git.noc.ruhr-uni-bochum.de/artefact-kgi/twentytwenty-child/-/issues)
* [h5pmods-wordpress-plugin](https://git.noc.ruhr-uni-bochum.de/artefact-kgi/h5pmods-wordpress-plugin/-/issues)


## License

(The MIT License)

Copyright (c) 2015 Joubel AS

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

