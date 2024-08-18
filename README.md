## WorkExperience

### Skills
<b>Programming Languages (Experience in years):</b> Swift (>5), Objective-C (5), Core Java (3), Python (<1), Web technologies (<1)

<b>iOS Frameworks:</b> Foundation, Combine, SwiftUI, UIKit, CoreLocation, MapKit, CoreData, AVFoundation, HealthKit, WebKit and Realm, SwiftyJSON, AFNetworking, XCTest, OHTTPStubs, RxSwift, TinyConstraints, IGListKit, Identity Management: Akamai & TrustDefender ThreatMetrix, Lottie, Observables, Closures, Taplytics, mParticle, Google Analytics, Bolts, SwiftyBeaver, First Data, Visa Checkout, BLE-based indoor positioning frameworks, Speech-to-text (local and remote), Chatbot integrations

<b>Design Patterns:</b> TCA, Flow (MVVM + UDF), Custom-VIPER, Observable, MVC, MVVM, Factory, Protocol-Delegate, Category and Extensions, Target-action, KVO, Notification, Singleton

<b>Tools:</b> Source Tree, Bitbucket, JIRA, cocoapods, Carthage, Jenkins, FastLane, Zeplin, Sketch and Invision, Swagger, Amplitude, MS Teams, Slack, Hockey App - Microsoft App Center, vim

#### Other Skills
<b>Distributed Systems:</b> Pastry, GFS (Google File System), Chord, Random Walk, Flooding, PlanetLab & DeterLab deployments

<b>Data Sciences:</b> Apache Hadoop, MapReduce, HBase, AWS (EC2, EMR, S3), Storm, Spark, Dist. RPC, Recommender Systems

### Principal iOS Engineer, Porsche Digital, Palo Alto, CA                                                      03/23 – Present
#### Leading a team of 5 iOS engineers including 3 direct reports, developing My Porsche CarPlay [application](https://apps.apple.com/us/app/my-porsche/id1542743354), catering to 60K+ daily active users. Porsche is the first vehicle manufacturer to integrate vehicle functions within an app in Apple CarPlay.
* Architected and developed CarPlay features using MVVM Architecture. Developed reusable vehicle engineering frameworks using modular architecture and integrated them via SPM. Used dependency injection techniques to create highly testable and reusable layers with >30% test coverage. Instilled the team with a culture of writing unit tests for every code change.
* Proposed and architected a framework to abstract out all vehicle related communication. Defined the API interface using Delegate design pattern to allow flexibility for clients to manage different connector types. They interact with corresponding vehicle engineering framework to scan, discover, connect, and exchange information with the vehicle. This allows easy maintenance of the vehicle interaction code and provides a pattern to integrate future architectures without client-side changes.
* Developed proof-of-concepts for next generation CarPlay i.e. Ferrite. Created light weight applications using AppClips template to interact with the vehicle without ever downloading the full-size app, which has led to 5k+ new user sign ups.
* Investigated app store feedback and crash reports, used logging info, Network Link Conditioner tool and Xcode Instruments and brought down avg. monthly unique crash count from double digits to below 10, which is an all-time low for this project.
* Used SonarQube instance to conduct static code analysis to identify potential code vulnerabilities and fixed them.
* Onboarded and mentored team members on the new architecture and iOS frameworks such as Combine and Swift. Actively participated in mob sessions and resolved blockers for the team aiding quicker resolutions and developer productivity.


Frameworks: Combine, SwiftUI, Foundation, UIKit, BluetoothLE, XCTest, CoreData, Vehicle Engineering, Instabug, Firebase
Tools: Xcode, SPM, CocoaPods, Charles Proxy, GitHub, Sourcetree, CI/CD scripts, fastlane, Slack, MS Teams, Figma, Atlassian Tools


### Senior iOS Engineer, Lucid Infosystems, Dallas, TX/ Sunnyvale, CA                                            08/18 – 02/23
#### Part of the Customer Journey team for Hilton Worldwide Inc., working as a Module Lead on the Hilton Honors [application](https://itunes.apple.com/us/app/hilton-honors/id635150066?mt=8 "HHonors App") project, catering to a 4m+ active user base. The app was awarded #1 Hotel Brand App at World Travel Awards.
* Architected Digital Key Sharing feature using Flow design pattern, combining concepts from MVVM and UDF. Used reactive programming and dependency injection techniques. Created highly testable and reusable layers with >80% test coverage. It’s an industry first feature and helped increase 100k+ Digital Key usage in the first month after rollout.
* Implemented a/b tests using Maxymiser tool to control navigation flows based on a test split ratio. I used additive programming technique, built gating layers to control user experience using multiple gates viz. config file, variants and feature flags. This helped business evaluate the usage pattern and drive 1M+ increase in Digital Key usage per year.
* Worked on Digital Key and Connected Room projects. Implemented using MVVM architecture, the modules extensively use CoreBluetooth and 3rd party frameworks to range, connect and interact with peripherals. Built using RxSwift, the declarative approach helped monitor and react to various Bluetooth connection states & apply seamless data transformations.
* Analyzed code coverage on the Digital Key project with the help of Xcode Code Coverage tool and a SonarQube instance. Wrote over 600 test cases using XCTest framework to increase test coverage to over 60% across all layers. 
* Investigated app store feedbacks and crash reports, used logging info, Network Link Conditioner tool and Xcode Instruments and brought down avg. monthly unique crash count from double digits to below 10, which is an all-time low for this project.
* Utilized extensively the Xcode Developer tools like Time Profiler to analyze the time-taking async tasks. This helped to reduce time taken by a group of network calls (in the range of 100s) from >10s to less than 3 seconds. Also used Leaks tool to identify reference cycles and rectified them using weak and unowned references. This led to effective system resources usage.
* Conducted knowledge sharing sessions to the team about design patterns, HealthKit and novel 3rd party frameworks.


Frameworks: Combine, SwiftUI, Foundation, UIKit, CoreBluetooth, XCTest, CoreData, AFNetworking, RxSwift, Onity, Maxymiser
Tools: Xcode, Git, Sourcetree, CocoaPods, Charles Proxy, Atlassian tools, Embrace, Jenkins, fastlane, Hockey App, MS Teams


<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton1.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton2.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton3.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Hilton/Hilton4.jpg" width="200" height="350" />

### Senior Consultant, Capgemini, Atlanta, GA                                                                     06/16 – 07/18
#### Part of the iOS development team for Chick-fil-A (CFA) flagship [application](https://goo.gl/B86zNS "Chick-fil-A Flagship App") (4+ rating) catering to a 2m+ active user base, #1 on Food & Drink Category on multiple occasions and consistently in top 10, Highest ranking - #37 across all App store categories

* Re-wrote an entire project in 100% Swift with a custom-VIPER design pattern, consisting in excess of 200k lines of code. With custom-VIPER, I created a module per screen, creating separation of concerns between Interfaces, View, Navigation, Data Interactor and module creation layers. This pattern helped in reusing the modules efficiently across overlapping features, with dependency injection at the module creation layer, as a result increasing testability of source code. Other patterns also implemented viz. MVC, Protocol oriented, Facade, Factory, Observable and Singleton. Functional and Declarative Style.

* Wrote unit test cases with XCTest and Nimble test frameworks and used OHHTTPStubs to mock network requests. Achieved more than 50% test coverage across the project, resulting in highly testable network, data access and view model layers.

* Created a protocol-oriented, dependency injectable architecture for navigation between and within modules. This provided flexibility to setup a hierarchy independent navigation design, custom transitions and frictionless presentation.

* Implemented UI and Auto layout 100% in code, providing easiest way to apply style and extreme reusability.

* Implemented Continuous Integration-Continuous Delivery (CI/CD) build process between BitBucket, Jenkins with fastlane build scripts and Hockey App, efficiently tracking multiple versions of builds across environments.

* Investigated app store feedbacks and crash reports, used logging info, Network Link Conditioner tool and Xcode Instruments and brought down avg. unique crash count from double digits to below 10, which is an all-time low for this project.

* Problem: In mobile order dine-in flow, customer despite ordering thru mobile, had to go in queue to register desk and collect an identification object tagged to the order & take a seat, which introduces an unnecessary wait time for the customer.

    Solution: I implemented a BLE-based beacon solution into the app to track the movement of Customer entering restaurant & taking a seat and at the same time notifying restaurant to prepare the order & deliver to the exact table customer is seated at.

    Result: This solution provided a magical customer experience, while also solving one of the important problems at restaurants with high traffic during peak hours, cutting down avg. wait time of a customer by 50%. Also helped CFA team members know Customer’s exact table number which is an imp. info especially for multistoried restaurants in Manhattan, NY.

Frameworks: Realm, AFNetworking, IGListKit, ThreatMetrix, Observables, TinyConstraints, Taplytics, mParticle, Bluetooth
Tools: Xcode, Source Tree, Bitbucket, JIRA, Carthage, Jenkins, fastlane, Hockey App, Charles Proxy, Swagger, Amplitude, Slack

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA1.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA2.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA3.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/CFA/CFA4.webp" width="200" height="350" />



### Consultant, Capgemini, Bangalore, India                                                                         11/13 – 12/14
#### Responsible for developing & Managing SUP (Sybase Unwired Platform) and Rest web services driven Enterprise Mobility solutions on iOS and Android platforms for clients viz. Procter & Gamble, John Deere, Ikea, J&J and SO.IN.

* PetCare Loyalty Project: Implemented UI-rich Master-Detail hierarchical design loaded with data in the form of MBOs (Mobile Business Objects) from an SUP source. MVC pattern was followed and dependency injection was implemented to have the data objects flow into detail screens with necessary abstraction. Data Objects were mostly of type NSSet and NSOrderedSet to make sure objects are unique and order in the list is maintained for certain screens. The application as a whole converted P&G’s Pet Care Loyalty business from paper-based to 100% digital.

* WINGiT Project: Worked on Create and Browse events sections of the project designed in MVC pattern using fragments and adapters for reusability, driven by REST web services to develop a social networking 
[Android application](https://play.google.com/store/apps/details?id=com.soin.wingit "WINGiT App") that brings together best of local events from various social platforms aggregated at the backend.

* Reports Viewer Project: Developed an iPad application that reads MS Excel input files via REST web services and generates dynamic, interactive, 2-way scrollable grid dashboard with hierarchical design, which is achieved in a unique way using two collection views at right angles to scroll together both horizontally and vertically. Search to view date specific data, filter data based on tags, and sort by tapping on column headers. The application eliminated the manual work of data analysis by 100% and brought down analysis and actionable time for each report from 10 minutes to less than 30 seconds.

Frameworks: Foundation, UIKit, CoreData, CoreLocation, MapKit, JASON, AVFoundation

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT1.webp" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT2.webp" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT3.webp" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/WINGiT/WINGiT4.webp" width="200" height="350" />


### Senior Software Engineer, Ness Technologies, Bangalore, India                                                 07/12 – 10/13
#### Developed and managed iOS applications for Perform Group across platforms for the UK, middle–east and APAC regions

* Created and owned sport and league follower [applications](https://itunes.apple.com/us/app/soccerway/id1193234141?mt=8 "Soccer Apps") with live streaming of events, news, video on demand, Electronic Program Guide, Single Sign on and in app subscription to buy team merchandise

* Developed re-skinnable solutions for white labeled iOS projects with single and multiple targets, working with product & business owners for the entire lifecycle of the project, aided in obtaining end-to-end understanding of the project

* Conducted versioning updates on legacy applications for automatic reference counting (ARC) conversion, iPhone 5 compatibility, storyboard and documented the same for future reference. Contributed in building reliable, reusable set of library components, as part of project development, as well providing easy maintenance of source code.

Ex: Frameworks for video player, calendar, segue-multiple storyboards, custom tabs, local keychain store, localization, custom controls etc.

<img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P1.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P2.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P3.jpg" width="200" height="350" /> <img src="https://github.com/darshangulur/WorkExperience/blob/master/Assets/Perform/P4.jpg" width="200" height="350" />

### Software Engineer, Ness Technologies, Bangalore, India                                                         07/10 - 06/12

* Developed proof of concepts, working with senior management and sales team, bringing in first set of clients to the team

* Defined product features collecting inputs from client, designed and developed a peer-to-peer text, image and location messaging application over User Datagram Protocol. Defined and Implemented messaging protocol.
