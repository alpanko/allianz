AEM
===



AEM Setup
---------
- [AEM 6.2 documentation root](https://docs.adobe.com/docs/en/aem/6-2.html)
- AEM Page Template
- [AEM 6.2 setup guide](https://docs.adobe.com/docs/en/aem/6-2/deploy.html#Getting%20Started)
- Replication should be configured ootb, for further information see [this](https://docs.adobe.com/docs/en/aem/6-2/deploy/configuring/replication.html).
- Configuring the dispatcher [here](https://docs.adobe.com/docs/en/dispatcher.html)
- A minimal dispatcher configuration file can be found in the dispatcher archive

IDE Setup
---------
- [Eclipse IDE](https://eclipse.org/downloads/)
- [AEM Developer Tools for Eclipse](https://docs.adobe.com/docs/en/dev-tools/aem-eclipse.html)
- [Apache Maven](https://maven.apache.org)

Project Setup
-------------
- [AEM project archetype](https://github.com/Adobe-Marketing-Cloud/aem-project-archetype)
- [Importing a project into Eclipse](https://docs.adobe.com/docs/en/dev-tools/aem-eclipse.html#How%20To%20Import%20Existing%20Projects)


Development Basics
------------------
- [AEM Development Basics](https://docs.adobe.com/docs/en/aem/6-2/develop/the-basics.html)
- [AEM Development Best Practices](https://docs.adobe.com/docs/en/aem/6-2/develop/best-practices.html)

Paragraph System
----------------
- [Adding a parsys](https://blogs.adobe.com/sunil/2015/04/12/adding-the-parsys-component-to-template/)

Sightly/HTL & Sling Models
--------------------------
- [Sling Models](https://sling.apache.org/documentation/bundles/models.html)
- [Using Sling Models](https://helpx.adobe.com/experience-manager/using/slingmodel_62.html)
- [HTL](https://docs.adobe.com/docs/en/htl/overview.html)
- [HTL EL](https://docs.adobe.com/docs/en/htl/docs/expression-language.html)

Component Development
---------------------
- [Developing Components](https://docs.adobe.com/docs/en/aem/6-2/develop/components.html)
- [Component examples](/libs/wcm/foundation/components)

Tutorial
--------
- Apache Sling JCR Overview 1h: https://www.youtube.com/watch?v=Xuw2ZRjbZt8 (pretty old from 2008 but concepts stay)
- More isights to OSGi and Sling Rest Style: https://www.youtube.com/watch?v=vll9wezY1bs

Local CQ Resources and Tools
----------------------------
- [CRXDElite](http://localhost:4502/crx/de)
- [Content Repository access in the Mac Finder via WebDAV](http://localhost:4502/)
- [Content Repository Extreme](http://localhost:4502/crx/explorer/index.jsp)
- [Siteadmin](http://localhost:4502/siteadmin#/content)
- [CMS Startpage](http://localhost:4502/libs/cq/core/content/welcome.html)
- [Content Explorer](http://localhost:4502/crx/explorer/browser/index.jsp)
- [Configuration Manager](http://localhost:4502/system/console/configMgr)
- [Task Manager](http://localhost:4502/libs/cq/taskmanagement/content/taskmanager.html)
- [Package Manager](http://localhost:4502/crx/packmgr/index.jsp)

APIs
----
- [ContextHUB](https://docs.adobe.com/docs/en/aem/6-2/develop/personalization/contexthub/ch-samplestores.html)

FAQ
---
- How to start AEM without Geometrixx?
Stop AEM, Remove crx-quickstart folder and call the jar via the following command:
`java -jar ~/AEM_6.2_Quickstart.jar -r nosamplecontent`
Afterwards you have a 'naked' AEM instance without demo content cluttered around everywhere

Documentation
-------------

AEM: http://docs.adobe.com

Recent updates: https://docs.adobe.com/docs/en/aem/recent-documentation-updates.html
AEM Docs daily changes: http://adobedocsdiff.headwire.com/sitediff/


API References
--------------

https://docs.adobe.com/docs/en/aem/6-2/develop/ref.html
https://github.com/Adobe-Marketing-Cloud/htl-spec/blob/1.2/SPECIFICATION.md - HTL v. 1.2 spec
https://docs.adobe.com/docs/en/aem/6-2/develop/ref/jsdoc/ui-touch/editor-core/index.html - Touch UI
https://docs.adobe.com/docs/en/aem/6-2/develop/ref/test-api/index.html - Hobbes.js


Open Source Projects
--------------------

http://felix.apache.org -  OSGI Framework Implementation
http://jackrabbit.apache.org/ - JCR Repository
http://sling.apache.org/ - Sling Web Framework
http://tika.apache.org/ - Content extraction from various file formats
http://lucene.apache.org/ - Lucene Search Index Engine and Solr Server


How-to
------

https://helpx.adobe.com/marketing-cloud/experience-manager.html
https://adobe-consulting-services.github.io/acs-aem-tools/
http://adobe-consulting-services.github.io/acs-aem-commons/
http://stackoverflow.com/questions/tagged/aem

Educational resources
---------------------

http://aemcasts.com/ - Short video tutorials for beginners
http://dev.day.com/gems - 45 min in-depth tech webcast

Packages
--------

https://github.com/Adobe-Marketing-Cloud/aem-demo-machine/wiki
https://www.adobeaemcloud.com/
---------

https://helpx.adobe.com/experience-manager/kb/aem62-available-hotfixes.html
https://helpx.adobe.com/experience-manager/kb/aem61-available-hotfixes.html
https://helpx.adobe.com/experience-manager/kb/aem6-available-hotfixes.html

Dev tools
---------

Eclipse AEM plugin: https://docs.adobe.com/docs/en/dev-tools/aem-eclipse.html
Intellij AEM Plugin: https://github.com/headwirecom/aem-ide-tooling-4-intellij/wiki
Chrome Log Tracer: http://adobe-consulting-services.github.io/acs-aem-tools/aem-chrome-plugin/log-tracer/
AEM sync: https://github.com/Adobe-Marketing-Cloud/tools/tree/master/repo


Code examples
-------------
http://adobe-consulting-services.github.io/acs-aem-samples/

Adobe pubilc repositories
------------------------

https://repo.adobe.com/nexus/content/repositories/public
http://bit.ly/AMCPKGSHARE - Package Share
https://github.com/Adobe-Marketing-Cloud/
http://adobe-consulting-services.github.io
https://github.com/AdobeAtAdobe
https://github.com/cqsupport
https://helpx.adobe.com/experience-manager/kb/download-companion-app.html - Asset Companion app

3rd party code repositories and libraries
-----------------------------------------
https://github.com/TWCable
http://wcm.io/
https://github.com/Netcentric
https://github.com/Citytechinc
https://github.com/Cognifide
https://github.com/badvision/curly
https://github.com/sinnerschrader/aem-react
https://github.com/sinnerschrader/aem-react-js

AEM on GitHub
-------------

https://github.com/search?utf8=%E2%9C%93&q=aem-&type=Repositories&ref=searchresults

Migration Tools
---------------
oak-upgrade: https://jackrabbit.apache.org/oak/docs/migration.html
Crx2Oak: https://repo.adobe.com/nexus/content/groups/public/com/adobe/granite/crx2oak/
Oak Run: http://mvnrepository.com/artifact/org.apache.jackrabbit/oak-run
Huge data migration: https://github.com/TWCable/grabbit

Marketplace
-----------
http://bit.ly/MCXChange


Mobile
------

https://github.com/blefebvre/aem-phonegap-kitchen-sink
https://github.com/blefebvre/aem-phonegap-starter-kit

Communites
----------

AEM Technologist  Community: http://communities.adobe.com
AEM Helpx: https://helpx.adobe.com/marketing-cloud/experience-manager.html
AEM Help Forum: http://help-forums.adobe.com/experience-manager
AEM Assets Forum: http://help-forums.adobe.com/experience-manager/assets

Blogs
-----

http://blogs.adobe.com/experiencedelivers/
http://blogs.adobe.com/contentmanagement/
https://www.terrabeata.com/
http://experience-aem.blogspot.de
http://www.wemblog.com/
http://cq-ops.tumblr.com/
http://www.aemstuff.com
http://www.nateyolles.com

Release Notes
-------------

Marketing Cloud: https://marketing.adobe.com/resources/help/en_US/whatsnew/
Dispatcher: http://www.aemstuff.com/tools/dispatcheronlinetracker.html

Video
-----

http://tv.adobe.com/videos/adobe-experience-manager/
Adobe Gems: http://www.adobe.com/go/gems
Support Team: https://github.com/cqsupport


Training
--------

http://bit.ly/AEMTraining

Events and Conferences
----------------------

Agenda: https://communities.adobe.com/en/communities/aem_technologistsdevelopersarchitects/events.html
http://adaptto.org
http://www.connectcon.ch
http://www.circuitdevcon.com
http://summit.adobe.com

Information about login (authentication and authorization) and Single Sign On/Single Logout
===========================================================================================

AEM
---
- [User Administration](https://docs.adobe.com/docs/en/aem/6-2/administer/security.html)
- [Identity Management](https://docs.adobe.com/docs/en/aem/6-2/administer/security/identity-management.html)
- [AEM "Closed User Group"](https://docs.adobe.com/docs/en/aem/6-2/administer/security/cug.html)


Dispatcher
----------
Closed User Group pages (i.e. pages with an ACL) are not cached.

Important:
> When a Dispatcher farm has session-management enabled, all pages that the farm handles are not cached. To cache pages that are outside of CUG, create a second farm in dispatcher.any
that handles the non-CUG pages.

- [Session Management/Authentication](https://docs.adobe.com/docs/en/dispatcher/disp-config.html#par_124_22_0007)

SSO
---

Several docs, covering the same topic, with different content...

- [Configuring SSO](https://docs.adobe.com/docs/en/aem/6-2/deploy/configuring/single-sign-on.html)
- [Configuring SSO using SAML](https://helpx.adobe.com/enterprise/help/configure-sso.html)
- [Demonstration of AEM and SAML integration](https://helpx.adobe.com/experience-manager/kb/simple-saml-demo.html)
- [Enabling SSO with SAML](https://helpx.adobe.com/sign/how-to/SAML_Configuration.html)
- [FAQ](https://helpx.adobe.com/enterprise/help/sso-faq.html)
- [Changes in AEM 6.1](http://www.aemstuff.com/blogs/july/saml.html)

other
-----
- [custom authhandler (AEM6.1)](http://www.wemblog.com/2013/03/how-to-create-custom-authentication.html)
