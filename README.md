## WorkExperience

### Skills
<b>Programming Languages (Experience in years):</b> Swift (>3), Objective-C (6), Core Java (6), Python (<1), Web technologies (<1)

<b>iOS Frameworks:</b> UIKit, Foundation, CoreLocation, MapKit, CoreData, AVFoundation, HealthKit, WebKit and Realm, VariantKit, fastlane, SwiftyJSON, AFNetworking, IGListKit, Result, TrustDefender ThreatMetrix Identity Management, Lottie, Observables, Closures, TinyConstraints, XCTest, OHTTPStubs, RxSwift, Taplytics, mParticle, Google Analytics, Bolts, SwiftyBeaver, First Data, Visa Checkout, BLE-based indoor positioning frameworks, Speech-to-text (local and remote), Chatbot integrations

<b>Design Patterns:</b> Custom-VIPER, Observable, MVC, MVVM, Factory, Protocol-Delegate, Category and Extensions,
Target-action, KVO, Notification, Singleton

<b>Tools:</b> Source Tree, Bitbucket, JIRA, Carthage, Jenkins, fastlane, Maxymiser, Apteligent, Sketch and Invision, Swagger, Amplitude, Slack, cocoapods, Hockey App - Microsoft App Center, vim

#### Other Skills
<b>Distributed Systems:</b> Pastry, GFS (Google File System), Chord, Random Walk, Flooding, PlanetLab & DeterLab deployments

<b>Data Sciences:</b> Apache Hadoop, MapReduce, HBase, AWS (EC2, EMR, S3), Storm, Spark, Dist. RPC, Recommender Systems

### Lead iOS Engineer, Lucid Infosystems, Dallas, TX	                                                       08/18 – Present
#### Part of Customer Journey team at Hilton Corporate, working as a Module Lead for Hilton Honors [application](https://itunes.apple.com/us/app/hilton-honors/id635150066?mt=8 "Chick-fil-A Flagship App") project, catering to a 2m+ active user base. The app was awarded #1 Hotel Brand App at World Travel Awards.

* Implemented a/b tests using Maxymiser tool to control navigation flows based on a test split ratio. I used additive programming technique, built gating layers to control user experience using multiple gates viz. config file, variants and feature flags. This helped business evaluate the usage pattern and drive 1M+ increase in Digital Key usage per year.

* Architected Digital Key Sharing feature using MVVM and Factory design patterns. Used dependency injection and functional programming techniques to create highly testable and reusable networking and view model layers, with >80% test coverage. It’s an industry first feature and helped increase 4% app downloads, 70k new user sign ups and 280k+ Digital Key usage.

* Worked on Digital Key and Connected Room projects. Implemented using MVVM architecture, the modules extensively use the CoreBluetooth and 3rd party frameworks to range, connect and interact with peripherals. Completely built on RxSwift, the declarative approach helped monitor and react to various Bluetooth connection states & apply seamless data transformations.

* Analyzed code coverage on the Digital Key project with the help of Xcode Code Coverage tool and a SonarQube instance. Wrote over 400 test cases using XCTest and Nimble test frameworks to increase the coverage to over 60% across all layers. 

* Investigated app store feedbacks and crash reports, used logging info, Network Link Conditioner tool and Xcode Instruments and brought down avg. monthly unique crash count from double digits to below 10, which is an all-time low for this project.

* Utilized extensively the Xcode Developer tools like Time Profiler to analyze the time-taking async tasks. This helped to reduce time taken by a group of network calls (in the range of 100s) from >10s to less than 3 seconds. Also used Leaks tool to identify reference cycles and rectified them using weak and unowned references. This led to effective system resources usage.

Frameworks: Foundation, UIKit, CoreBluetooth, Core Location, MapKit, CoreData, AFNetworking, RxSwift, Onity, Maxymiser
Tools: Xcode, Git, Source Tree, Bitbucket, JIRA, Apteligent, Jenkins, fastlane, Hockey App, TestFlight, Charles Proxy, Swagger, Slack

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton1.jpg" width="175" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton2.jpg" width="175" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton3.jpg" width="175" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton4.jpg" width="175" height="350" />


### Senior Consultant, Capgemini, Atlanta, GA	                                                                 06/16 – 07/18
#### Part of the iOS development team for Chick-fil-A (CFA) flagship [application](https://goo.gl/B86zNS "Chick-fil-A Flagship App") (4+ rating) catering to a 2m+ active user base, #1 on Food & Drink Category on multiple occasions and consistently in top 10, Highest ranking - #37 across all App store categories

* Re-writing an entire project in 100% Swift with a custom-VIPER design pattern, consisting in excess of 200k lines of code. With custom-VIPER, I created a module per screen, creating separation of concerns between Interfaces, View, Navigation, Data Interactor and module creation layers. This pattern helped in reusing the modules efficiently across overlapping features, with dependency injection at the module creation layer, as a result increasing testability of source code. Other patterns also implemented viz. MVC, Protocol oriented, Facade, Factory, Observable and Singleton. Functional and Declarative Style.

* Wrote unit test cases with XCTest and Nimble test frameworks and used OHHTTPStubs to mock network requests. Achieved more than 50% test coverage across the project, resulting in highly testable network, data access and view model layers.

* Built out the Restaurant Selection Feature using CoreLocation and MapKit frameworks. Subclassed MKAnnotation and MKAnnotationView to create custom annotations and added callouts on MapView. Built a convenience class to manage Location preferences and delegates for Location updates. Used CoreData and Realm to manage all and user favorite restaurants info. Built search and filter functionalities around list and map sections for user convenience.

* Implemented UI and Auto layout 100% in code, providing easiest way to apply style and extreme reusability.

* Created a protocol-oriented, dependency injectable architecture for navigation between and within modules. This provided flexibility to setup a hierarchy independent navigation design, custom transitions and frictionless presentation.

* Adapted a framework-based approach to convert not so frequently modified and task focused modules like Network, Analytics, UI Styling and App Configuration layers into their own repositories linked via dependency management. This helped in robust & effective maintenance and sharing of code base across various stakeholder applications.

* Problem: In mobile order dine-in flow, customer despite ordering thru mobile, had to go in queue to register desk and collect an identification object tagged to the order & take a seat, which introduces an unnecessary wait time for the customer.

    Solution: I implemented a BLE-based beacon solution into the app to track the movement of Customer entering restaurant & taking a seat and at the same time notifying restaurant to prepare the order & deliver to the exact table customer is seated at.

    Result: This solution provided a magical customer experience, while also solving one of the important problems at restaurants with high traffic during peak hours, cutting down avg. wait time of a customer by 50%. Also helped CFA team members know Customer’s exact table number which is an imp. info especially for multistoried restaurants in Manhattan, NY.

Frameworks: Realm, AFNetworking, IGListKit, ThreatMetrix, Observables, TinyConstraints, Taplytics, mParticle, Bluetooth
Tools: Xcode, Source Tree, Bitbucket, JIRA, Carthage, Jenkins, fastlane, Hockey App, Charles Proxy, Swagger, Amplitude, Slack

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA1.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA2.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA3.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA4.webp" width="200" height="350" />


### Consultant, Capgemini, Bangalore, India	                                                                     11/13 – 12/14
#### Responsible for developing & Managing SUP (Sybase Unwired Platform) and Rest web services driven Enterprise Mobility solutions on iOS and Android platforms for clients viz. Procter & Gamble, John Deere, Ikea, J&J and SO.IN.

* PetCare Loyalty Project: Implemented UI-rich Master-Detail hierarchical design loaded with data in the form of MBOs (Mobile Business Objects) from an SUP source. MVC pattern was followed and dependency injection was implemented to have the data objects flow into detail screens with necessary abstraction. Data Objects were mostly of type NSSet and NSOrderedSet to make sure objects are unique and order in the list is maintained for certain screens. The application as a whole converted P&G’s Pet Care Loyalty business from paper-based to 100% digital.

* WINGiT Project: Worked on Create and Browse events sections of the project designed in MVC pattern using fragments and adapters for reusability, driven by REST web services to develop a social networking 
[Android application](https://play.google.com/store/apps/details?id=com.soin.wingit "WINGiT App") that brings together best of local events from various social platforms aggregated at the backend.

* Reports Viewer Project: Developed an iPad application that reads MS Excel input files via REST web services and generates dynamic, interactive, 2-way scrollable grid dashboard with hierarchical design, which is achieved in a unique way using two collection views at right angles to scroll together both horizontally and vertically. Search to view date specific data, filter data based on tags, and sort by tapping on column headers. The application eliminated the manual work of data analysis by 100% and brought down analysis and actionable time for each report from 10 minutes to less than 30 seconds.

Frameworks: Foundation, UIKit, CoreData, CoreLocation, MapKit, JASON, AVFoundation

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT1.webp" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT2.webp" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT3.webp" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT4.webp" width="200" height="350" />


### Senior Software Engineer, Ness Technologies, Bangalore, India	                                             07/12 – 10/13
#### Developed and managed iOS applications for Perform Group across platforms for the UK, middle–east and APAC regions

* Created and owned sport and league follower [applications](https://itunes.apple.com/us/app/soccerway/id1193234141?mt=8 "Soccer Apps") with live streaming of events, news, video on demand, Electronic Program Guide, Single Sign on and in app subscription to buy team merchandise

* Developed re-skinnable solutions for white labeled iOS projects with single and multiple targets, working with product & business owners for the entire lifecycle of the project, aided in obtaining end-to-end understanding of the project

* Conducted versioning updates on legacy applications for automatic reference counting (ARC) conversion, iPhone 5 compatibility, storyboard and documented the same for future reference. Contributed in building reliable, reusable set of library components, as part of project development, as well providing easy maintenance of source code.

Ex: Frameworks for video player, calendar, segue-multiple storyboards, custom tabs, local keychain store, localization, custom controls etc.

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P1.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P2.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P3.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P4.jpg" width="200" height="350" />


### Software Engineer, Ness Technologies, Bangalore, India	                                                     07/10 - 06/12

* Developed proof of concepts, working with senior management and sales team, bringing in first set of clients to the team

* Defined product features collecting inputs from client, designed and developed a peer-to-peer text, image and location messaging application over User Datagram Protocol. Defined and Implemented messaging protocol.

