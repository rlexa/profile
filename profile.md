# Software Developer/Architect (Master of Computer Science)

## Focus Experience

**Current focus: Angular/Typescript Frontend/Fullstack.**

- Currently Architect / Senior level:
  - Angular Frontend (Fullstack)
- Expert
  - Rapid Prototyping (rapid learning and prototype development)
    - Incl. documentation, drivers, unittests and customer communication if needed
  - Reverse Engineering
    - Analysis and reconfiguration/refactoring/maintenance of legacy code
    - Performance monitoring and optimization
  - Frontend: concept and implementation of user interfaces
    - Tech. stack: HTML5/CSS3, Javascript, SPA Frameworks like Angular
    - Complex examples: WYSIWYG UI editor, charts, graphics programming
  - Backend: Java, C# (JPA, Hibernate, xSQL, Mongo, Amazon AWS SNS/SQS/S3), NPM (Javascript, Typescript, Express)
    - experience with data synchronization between heterogenous systems
  - Services: Java, C# (RESTlet, ServiceStack, Services, data transfer)
- Tech. Lead
  - Experience as lead for small teams (incl. customer relations and req. engineering)
- Trainer
  - Basics of computer science (and object-oriented C++, Java, also Javascript)
  - Basics of Android application development
  - Basics of UI and layout mechanism development

## Skills, Graduations, Work Experience

- Languages (fluent): German, English, Russian
- Science Degree: Master of Computer Science
- Trainer experience: lectureship at HDA Darmstadt
- Misc. work experience (chronologically descending):
  - (see projects further below)

## Acquired Skills

### Development Environments

| Target OS              | Environment, Engine, Tech                                                                                                                                   |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| PC (Microsoft Windows) | VS Code, Microsoft Visual Studio, Eclipse, InelliJ, C# (.NET), Java (Maven, Spring, Hibernate JPA, UnitTests, Restlets u.v.m.), C++ Ogre3D, DirectShow, MFC |
| Cross-Plattform        | Phonegap and Phonegap Plugins (for Android), Java, Javascript, Typescript, NPM (libraries, servers e.g. with Express)                                       |
| Webfrontend (Browser)  | Angular 2~, AngularJS, qooxdoo GUI development and layout imlementation, Typescript, Javascript, HTML5/CSS3 incl. animations and WebGL                      |
| Android                | Eclipse (ADT Plugin), Java, OpenGL ES 2.0                                                                                                                   |
| Nintendo DS            | NITRO SDK, C++/C                                                                                                                                            |
| PC (Unix)              | Eclipse, GDB, Makefiles, C++                                                                                                                                |
| Docker                 | Kubernetes, HELM                                                                                                                                            |

### Programming Skills

| Language, Tech                                              | Development Experience                                                                                |
| ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| C#                                                          | Driver, Interfaces, .NET, Backend, Reflection, Services                                               |
| Java, XML, BATch, PostgreSQL, MySQL, MongoDB                | Server modules, network interfaces, Android apps, Amazon AWS framework (SNS/SQS/S3...), RESTlets etc. |
| Javascript, Typescript, JSON, HTML/CSS, Angular, Rxjs, D3js | WebApps, GUIs, NodeJS microservices and servers                                                       |
| C++                                                         | GUIs, business logic, graphics etc.                                                                   |
| HLSL Shader, Lua, Python, VBA                               | Scripts, visual effects                                                                               |
| C                                                           | Proprietary environments                                                                              |
| Smalltalk, PHP, Unix AWK, Unix Shellscript                  | Misc.                                                                                                 |

### Tools (Microsoft Office goes without saying)

| Area           | Tool, Framework, Engine                                |
| -------------- | ------------------------------------------------------ |
| Cryptography   | SecuRom                                                |
| DevOps         | Jenkins, Teamcity, Docker                              |
| Documentation  | Confluence                                             |
| Planning       | EnterpriseArchitect, plantUML                          |
| Support        | Jira, Mantis, PHProject, BugTracker                    |
| User Interface | MenuMaster, MFC, Gameface, libRocket, qooxdoo, Angular |
| Versioning     | Perforce, CVS, Subversion, Git                         |

## Projects

Chronologically descending.

### 07/2021 - today **[RWE](https://www.group.rwe/)** (SPA Client with HTML5/CSS3, Angular Library, Angular, Typescript)
- Tasks:
  - SPA WebClients (Angular 12~ Typescript Rxjs, Angular Material)
  - Libraries (Typescript/Javascript, Angular components)
  - Theming (CSS3)
- Info
  - UI clients and portals for intranet use (management of energy park assets)
  - Ever growing library of widgets and code for intranet use in other teams
- Orga
  - Architect and Developer, team ca. 5 ppl.
- Tech
  - HTML5/CSS3 (SCSS)
  - Angular 12~ (Javascript, Typescript)
  - Rxjs
  - Web LocalStorage, Web SessionStorage
  - Angular Material
  - Unit Testing via Karma/Jasmine, Jest, mocking
- Phase:
  - PoC


### 01/2021 - 06/2021 **[KION GROUP AG](https://www.kiongroup.com)** (ALE project, SPA Client with HTML5/CSS3, Angular, Typescript)

- Tasks:
  - WebClients (Angular 11~ Typescript Rxjs, PrimeNG)
    - Microfrontends
      - Angular/PrimeNG development and maintenance
      - incl. Transclusion (frontend-in-frontend)
      - PDF contract generation in client
    - Libraries
      - shared code NPM library
      - theme css NPM library
      - localization NPM library
      - Angular widget NPM library
    - Internationalization
      - i18n with WebTranslateit (per frontend project)
      - custom implementation of turning XLF into CSV for dynamic language resolution at runtime
    - Authentication/Authorization
      - handling oauth2 for multiple frontends
    - Feature Toggles
      - separating technical releases from business releases using flags and toggles
    - Real time user monitoring
      - in NodeJS server
      - in Angular clients
  - Auth Server (NPM Typescript)
    - single auth point for multiple microfrontends
  - Media Servier (NPM Typescript)
    - asset and image delivery solution
  - Backend (Java Spring, OpenApi)
    - Web services for frontend
  - DevOps (Jenkins, YAML, Docker, Kubernetes, Azure)
    - Infrastructure by code
- Info
  - UI clients and portals for internal use (management of forklift resources and contracts)
    - tables, lists and details of contracts and assets
    - complex forms for commercial contract creation
    - complex forms for renting assets in external marketplaces
- Orga
  - Architect and Developer, team ca. 10 ppl.
- Tech
  - HTML5/CSS3 (Sass)
  - Angular 11~ (Javascript, Typescript)
  - Rxjs
  - Redux, Ngrx
  - Web LocalStorage, Web SessionStorage
  - PrimeNG
  - CI and Deployment via Jenkins
  - Unit Testing via Jest, mocking
  - NPM servers (Javascript, Typescript, Express, Webpack)
  - i18n localization
- Phase:
  - Production

### 09/2020 - 12/2020 **devdroy** (PWA with Angular)

- Tasks:
  - Create app as PWA which should work as app on Android and as SPA in the browser
- Info
  - Progressive Web Application (installable as app on Android) for viewing song chords
  - prototype only: proof of concept incl.:
    - PWA features (offline available)
    - UI: list of artists, list of artist songs, song view (with and without chords)
    - own simple format for storing songs with chords
    - sync of remote songs to local IndexedDB for offline availability
    - sharing of selected song from within the app
- Orga
  - Architect/Developer/Designer, 1 ppl.
- Tech
  - HTML5/CSS3 (Sass)
  - Angular 11 (Javascript, Typescript)
  - Rxjs
  - Web LocalStorage
  - Web IndexedDB (incl. synchronization, version upgrade)
  - Firebase hosting
  - Travis CI/CD
  - Unit Testing via Jest, mocking
- Phase:
  - Production [dd-chords](https://dd-chords.web.app/)

### 04/2019 - 08/2020 **[KION GROUP AG](https://www.kiongroup.com)** (PURE project, SPA Client with HTML5/CSS3, Angular, Typescript)

- Tasks:
  - WebClients (Angular 2~11 Typescript Rxjs, PrimeNG)
    - Server-Side-Rendering
    - Microfrontends
      - incl. Transclusion (frontend-in-frontend)
    - Libraries (Typescript/Javascript, Angular components)
    - Internationalization
      - i18n with WebTranslateit (per frontend project)
      - custom implementation of turning XLF into CSV for dynamic language resolution at runtime
    - Authentication/Authorization
      - handling oauth2 for multiple frontends
    - Feature Toggles
      - separating technical releases from business releases using flags and toggles
  - Auth Server (NPM Typescript)
    - single auth point for multiple microfrontends
  - Media Servier (NPM Typescript)
    - asset and image delivery solution
  - Backend (Java Spring, OpenApi)
    - Web services for frontend
  - DevOps (Jenkins, YAML, Docker)
    - Infrastructure by code
- Info
  - UI clients and portals for internal use (management of forklift resources and contracts)
- Orga
  - Architect and Developer, team ca. 10 ppl.
- Tech
  - HTML5/CSS3 (Sass, Less)
  - Angular 2~9 (Javascript, Typescript)
  - Rxjs
  - Redux, Ngrx
  - Web LocalStorage, Web SessionStorage
  - PrimeNG
  - CI and Deployment via Jenkins
  - Unit Testing via Karma/Jasmine, Jest, mocking
  - NPM servers with Typescript and Express
- Phase:
  - Production

### 05/2017 - 03/2019 **[DB Energie](https://www.dbenergie.de)** (SPA Client with HTML5/CSS3, Angular, Typescript)

- Tasks:
  - From-Zero: WebUI Client
  - Concept
  - Software Architecture
  - Implementation
  - Cont. Integration
  - Unit Testing
  - Deployment
  - SOAP and REST service interfaces
  - TIBCO OpenSpace interfaces
  - UI framework: Angular 2~7, Typescript
    - Reactive approach
    - Design framework: Material
  - Environment: VS Code
- Info
  - UI Client for internal use
- Orga
  - Architect and Developer for over 20 months, 1 ppl.
- Tech
  - HTML5/CSS3 (Sass, Less)
  - Angular 2~7 (Javascript, Typescript)
  - Rxjs
  - Redux
  - Web LocalStorage, Cookies
  - Material Design
  - D3.js charts
  - CI, Unit Testing and Deployment via Jenkins
- Phase:
  - Production

### 10/2016 - 04/2017 **[Mediatis](https://www.mediatis.de/)** (SPA Client with HTML5/CSS3, AngularJS, Typescript, Backend with C#, SQL)

- Tasks:
  - offline available WebApp
  - C# Services, Performance, Refactoring
  - AngularJS WebUI features
- Info
  - (Versioned) Document Repository
- Orga
  - Developer for ca. 5 months, 7 ppl.
- Tech
  - HTML5/CSS3 (Less)
  - AngularJS (TypeScript)
  - Web LocalStorage, IndexedDB
  - SQL DB (Entity Framework)
  - C# Services (IIS)
- Phase
  - Production

### 02/2016 - 09/2016 **[livedooh](https://www.livedooh.com/)** (ChromeApp MediaPlayer with AngularJS, SPA Client with AngularJS, Backend with C#, MongoDB)

- Tasks
  - offline available hybrid Web/Chrome App
  - C# nunit tests
  - AngularJS WebUI features
- Info
  - Digital Advertising Media Playback
- Orga
  - Developer for ca. 8 months, 5 ppl.
- Tech
  - HTML5/CSS3
  - AngularJS
  - Chrome App Development
  - Web LocalStorage and Filesystem
  - MongoDB
- Phase
  - Production

### 01/2016 - 02/2016 **devdroy** (WYSIWYG UI Editor with qooxdoo)

- Tasks
  - WYSIWYG UI Editor for qooxdoo (HTML5/CSS3)
  - Read/Write UI layouts in JSON
  - Theming support
  - Localization support
- Info
  - Editor project to build own projects on
  - Free of Charge, Open Source
- Orga
  - In-House, 1ppl, ca. 3 weeks
- Tech
  - C#, .NET 4.5, Reflection, REST Service, JSONP
  - JSON, XML
  - qooxdoo development chain
- Phase
  - Production, available for download

### 01/2016 **KomAn, [Brandmasters](https://www.brandmasters.de/de/)** (Consulting for qooxdoo, Metaforce)

- Tasks
  - Consulting for Metaforce Client and PHP PostgreSQL Backend

### 11/2015 - 12/2015 **devdroy** (C# Configurator Framework)

- Tasks
  - C# Framework For Configuration Based Approach
  - Logic similar to Java Spring
  - Loading of multiple configuration files (XML, JSON)
  - Data driven model in configuration files
    - Module Inheritance
    - Module Referencing
    - Nested Modules
    - Collection Properties
    - etc.
  - Inflating runtime instances using C# reflection
  - Completely unit/integration tested
- Info
  - C# Library (free) used for application configuration
- Orga
  - In-House, 1ppl, ca. 2 weeks
- Tech
  - C#, .NET 4.5, Reflection
  - JSON, XML
  - nunit Unit/Integration Testing
- Phase
  - Production, available for download

### 03/2015 - 12/2015 **[Envision Entertainment](https://www.envision-entertainment.de/)** ("CnC Tiberium Alliances" product)

- Tasks
  - WebUI (qooxdoo, HTML5/CSS3, Javascript, JSON)
    - refactoring, new features e.g.
      - multilanguage server localization support
      - correct timezone handling in backend
      - browser support (e.g. for Edge)
      - SVG based renderer for ingame world map
      - ingame cross-server events
      - ingame mail/forum systems
      - ingame interactive map markers
      - ingame combat simulator
    - feature complete Layout Editor
      - load/save/JSON<->Javascript of layouts
      - resource and WYSIWYG previews
    - qooxdoo upgrade version migration
    - UI theming (appearances, decorators etc.)
  - WebServices (C#)
    - refactoring, new features
  - Backend/Server Simulation (C#)
    - refactoring, new features
  - Configuration Framework (C#)
    - own framework used (similar to Java Spring)
  - Tools (C#)
    - refactoring, new features
    - new tools incl. UI and configurability e.g.
    - data injecting (e.g. system mail) at runtime
    - data structure maintenance at runtime
- Info
  - complex MMORTS (Fremium)
- Orga
  - Developer for ca. 8 months, ca. 5 ppl
- Tech
  - C#: Tools (incl. UI), Backend, Services, Configuration, Unit Testing
  - Javascript: WebUI, SVG
  - qooxdoo: web UI framework (HTML5/CSS3)
- Phase
  - live since 2011 (alliances.commandandconquer.com/)

### 06/2013 - 12/2014 **[Jeppesen](http://ww1.jeppesen.com/) Norway AS, a Boeing Company** (Data synchronisation between heterogenous database models and geografically distributed systems)

- Tasks
  - Backend (DB model and operations)
    - Server modules
    - RESTful services
    - Spring (Configuration Based Approach)
    - Versioning (Synchronization tech)
  - Amazon AWS Services (SNS, SQS, S3 etc.)
  - Documentation
  - Unit Testing (and Integration Testing)
- Info
  - Backend, Frontend, Data Porting
  - NDA: details confidential
- Orga
  - Role: Developer and lead, 1ppl for ca. 6 months, 5ppl starting with 6th Month
  - Geographically distributed team (Boston USA, Saint Petersburg Russia, Egersund Norway, Neu Isenburg Germany, Italy, Israel)
  - Language: Englisch only
  - Process: Agile, Scrum
  - Places of work: Remote Office, Neu Isenburg, Egersund
- Tech
  - Java, Maven, Hibernate, JPA, REST, PostgreSQL, Spring
- Phase
  - Production

### 04/2011 **(NDA)** (CityApp prototype)

- Tasks
  - Android App
  - NDA: all details confidential
- Info
  - Android WebApp for city information
    - current info about a city, weather, events, locations etc.
  - Visuals: HTML5 WebApp with CSS3 effects
  - GUI: own animations, fonts, resources
- Orga
  - Developer and lead for 10 days, 1ppl
- Tech
  - Phonegap, qooxdoo, reverse engineering
- Phase
  - Prototype done and accepted

### 08/2012 - 03/2013 **[EA Phenomic](https://en.wikipedia.org/wiki/EA_Phenomic)** ("CnC Tiberium Alliances" product mobile client)

- Tasks
  - UI via qooxdoo and HTML5/CSS3, Features
- Info
  - complex MMORTS (Fremium), Mobile (cross-platform) Client
- Orga
  - Developer for ca. 8 months, ca. 20ppl
- Phase
  - Production (alliances.commandandconquer.com/)

### 01/2012 - 07/2012 **[EA Phenomic](https://en.wikipedia.org/wiki/EA_Phenomic)** ("CnC Tiberium Alliances" product browser client)

- Tasks
  - UI via qooxdoo and HTML5/CSS3, Features
- Info
  - complex MMORTS (Fremium)
- Orga
  - Developer for ca. 11 months, ca. 20ppl
- Tech
  - UI via qooxdoo, Features
    - e.g. Arabic version implementation (right-to-left UI mirroring) among other things
- Phase
  - Production
- Subproject: qooxdoo WYSIWYG Layout Editor
  - Info
    - Layout Editor for qooxdoo framework, completely with Live-WYSIWYG view and layout import-/export via JSON
  - Orga
    - Developer and lead for 1 month, 1ppl
  - Tech
    - qooxdoo framework
  - Phase
    - Production
- Subproject: interactive in-app tutorial system
  - Info
    - User is led through the app using interactive texts, arrows and blocking views
  - Orga
    - Developer and lead for 3 weeks, 1ppl
  - Tech
    - Reverse Engineering, own script system (on JSON)
  - Phase
    - Production
- Subproject: qooxdoo theme compatible CSS animations
  - Info
    - CSS animations are integrated into qooxdoo theming and started on events like "mouse-over"
  - Orga
    - Developer and lead for 1 week, 1 week
  - Tech
    - Reverse Engineering, theming concepts
  - Phase
    - Production

### 05/2011 - 01/2012 **[EA Phenomic](https://en.wikipedia.org/wiki/EA_Phenomic)** ("Lord of Ultima" product browser client)

- Tasks
  - UI via qooxdoo and HTML5/CSS3, Features
    - e.g. Arabic version implementation (right-to-left UI mirroring) among other things
- Info
  - complex MMORTS (Fremium)
- Orga
  - Developer for ca. 8 months, ca. 20ppl
- Phase
  - Production (www.lordofultima.com)

### 10/2010 - 04/2011 **devdroy** ("DronskyGL" Android live wallpaper app)

- Info
  - Dronsky-Clone with hardware accelerated graphics interface (OpenGL ES 2.0)
  - Goal: implementation with optimized graphics interface
- Orga
  - Developer and lead for 1 week, 1ppl
- Tech
  - 2D/3D-Graphics with OpenGL ES 2.0
- Phase
  - Prototype ready including engine switch (OpenGL or Canvas)

### 10/2010 - 04/2011 **devdroy** ("Dronsky" Android live wallpaper app)

- Info
  - Semi-interactive background animation for Android 2.1
  - Goal: autonomous drones move on screen, fight each other, gather power-ups and evade asteroids
  - Visuals: classic and modern view switch, spawn power-up on touch
  - UI: view options, quality, size/quantity of drones/asteroids
- Orga
  - Developer and lead for 1 week, 1ppl
- Tech
  - Android wallpaper, 2D-Graphics, Performance Optimization, Android options
- Phase
  - Prototype ready but not on GooglePlay

### 10/2010 - 04/2011 **devdroy** ("Cosmosky" Android live wallpaper app)

- Info
  - Semi-interactive background animation for Android 2.1
  - Visuals: star sky with on touch particle cloud animation
- Orga
  - Developer and lead for 1 week, 1ppl
- Tech
  - Android wallpaper, 2D-Graphics
- Phase
  - Production, on GooglePlay

### 10/2010 - 04/2011 **devdroy** ("Snowsky" Android live wallpaper app)

- Info
  - Semi-interactive background animation for Android 2.1
  - Visuals: snow animation with on touch swirl animation
- Orga
  - Developer and lead for 1 week, 1ppl
- Tech
  - Android wallpaper, 2D-Graphics
- Phase
  - Production, on GooglePlay

### 10/2010-04/2011 **devdroy** ("Starsky" Android live wallpaper app)

- Info
  - Semi-interactive background animation for Android 2.1
  - Visuals: multi-coloured star sky with on touch warp travel animation
- Orga
  - Developer and lead for 1 week, 1ppl
- Tech
  - Android wallpaper, 2D-Grafik
- Phase
  - Production, on GooglePlay

### 10/2010 - 04/2011 **devdroy** ("Projectron" Android app)

- Info
  - App for customer oriented small project overview
  - Overview including:
    - General projects, per Projekt: Products (plus producer), Customers
    - Products can be grouped arbitrarily to product suites
    - Product suites can be assigned to customers including customer rating for the suite
- Orga
  - Developer and lead for 3 weeks, 1ppl
- Tech
  - Android Databases, UI
- Phase
  - Prototype ready, not on GooglePlay

### 04/2009 - 08/2010 **[Advancis Software&Services](https://advancis.net)** (WinGuard product, security overview system)

- MultiThreading/-Tasking Engine- for WinGuard (Installation Security Overview System)
  - Info: semi-controlled automatic parallelisation of business processes
  - Orga: Developer and lead for 2 weeks, 1ppl
  - Tech: Threading/Tasking in Windows
  - Phase: Production
- Avigilon Digitalvideo– WinGuard interface
  - Info: Discovery/Management/View of Avigilon cameras/videostreams
  - Orga: developer and lead for 4 weeks, 1ppl
  - Tech: Avigilon SDK
  - Phase: Production
- B-COM Access control system – WinGuard interface
  - Info: Management/View of Kaba/Benzing systems and access logs
  - Orga: developer and lead for 2 weeks, 1ppl
  - Tech: Kaba/Benzing communication protocols
  - Phase: Production
- CTConnect Telecommunication– WinGuard interface
  - Info: Management/View of CSTA Telephony/Stations/Processes
  - Orga: developer and lead for 4 weeks, 1ppl
  - Tech: CSTA, Envox/Syntellect middleware, telephone systems
  - Phase: Production
- EFE Nurse Call System– WinGuard interface
  - Info: Management/View of EFE Room-/Cellcalls in penal/hospital institutions
  - Orga: developer and lead for 8 weeks, 1ppl
  - Tech: EFE communication protocols
  - Phase: Production
- EFE COMSTOP – WinGuard interface
  - Info: Management/View of EFE mobile radio detectors
  - Orga: developer and lead for 2 weeks, 1ppl
  - Tech: EFE communication protocols
  - Phase: Production
- Frogsys Leak Warning System – WinGuard interface
  - Info: View of TTK leak warning systems
  - Orga: developer and lead for 2 weeks, 1ppl
  - Tech: TTK-MODBUS communication protocols
  - Phase: Production
- Gehrke4000 Telecommunication – WinGuard interface
  - Info: Management/View of Gehrke phone systems/stations
  - Orga: developer and lead for 2 weeks, 1ppl
  - Tech: Gehrke communication protocols
  - Phase: Production
- IndigoVision Digital Video System – WinGuard interface
  - Info: Management/View of IndigoVision video systems
  - Orga: developer and lead for 1 week, 1ppl
  - Tech: IndigoVision communication protocols
  - Phase: Production
- Kaba Exos Access Control System – WinGuard interface
  - Info: Management/View of Kaba Exos systems
  - Orga: developer and lead for 2 weeks, 2ppl
  - Tech: Kaba Exos communication protocols
  - Phase: Production
- LTC8x00 Analogous Video – WinGuard interface
  - Info: Management of LTC8x00 video-matrix switching systems
  - Orga: developer and lead for 3 weeks, 1ppl
  - Tech: Allegiance CCL communication protocols
  - Phase: Production
- MBeg multi-user device – WinGuard interface
  - Info: Management/Control of Geutebruck MBeg system
  - Orga: developer and lead for 2 weeks, 1ppl
  - Tech: MBeg communication protocols
  - Phase: Production
- Medicall800 Nurse Call System – WinGuard interface
  - Info: View of Medicall system for hospital institutions
  - Orga: developer and lead for 3 weeks, 1ppl
  - Tech: MC800 communication protocols
  - Phase: production
- Sona6 Perimeter Security – WinGuard interface
  - Info: Management/View of Sona systems
  - Orga: developer and lead for 1 week, 1ppl
  - Tech: Sona6 communication protocols
  - Phase: production
- UBI2 access control system – WinGuard interface
  - Info: Management/View of Autec/SiPort/Tarsos systems
  - Orga: developer and lead for 2 weeks, 1ppl
  - Tech: UBI2 communication protocols
  - Phase: production
- XProtect Digitalvideo – WinGuard interface
  - Info: Management/View of XProtect alarms/cameras/videostreams
  - Orga: developer and lead for 4 weeks, 1ppl
  - Tech: XProtect SDK
  - Phase: production

### 12/2008 - 03/2009 **[rocketsciencegames](https://en.wikipedia.org/wiki/Rocket_Science_Games)** ("Deutschland Singt Online" PC Game)

- Info
  - Karaoke game with licensed music videos, webcam-recording etc.
- Orga
  - Developer and lead in end phase for ca. 15 months, ca. 25ppl
- Tech
  - Video-/Graphics interfaces (Webcam, Video De-/Encoding etc.)
- Phase
  - Production
- Subproject: Video System
  - Info: Play/Record of video data and webcam-livestreams
  - Orga: developer and lead
  - Tech: DirectShow, DirectShow Filter, webcam controls
- Subproject: Video-Editing Studio
  - Info: cut and enrich webcal recordings with bluescreen effects and export as video data file
  - Orga: developer and lead
  - Tech: shader programming, bluescreen effects, special visual effects (procedural lightning etc.), Theora video encoder
- Subproject: Menu-GUI system
  - Info: prototype menu system for viewing complex UI
  - Orga: developer and lead
  - Tech: XML, Lua, Fonts, Statemachines
- Subproject: Archiviing and Encrypting
  - Info: high performance encrypted solution for licensed archived video material
  - Orga: developer and lead
  - Tech: Encryption, Ogre3D PlugIns
- Subproject: Content/Asset-Pipeline Automatisation
  - Info: Convert/Archive/Encrypt tools
  - Orga: developer and lead
  - Tech: script generation
- Subproject: Licensing System
  - Info: user management, license management
  - Orga: developer and lead
  - Tech: Encryption, SecuRom

### 09/2007 - 12/2007 **[rocketsciensegames](https://en.wikipedia.org/wiki/Rocket_Science_Games)** ("Tabaluga" Nindendo DS game)

- Info
  - Child friendly Jump&Run
  - Orga: Developer for ca. 4 months, ca. 20ppl
  - Tech: Game logic, Windows registry, PC CD-Starter
  - Phase: production
