# Advance Java

## 01 Jakarta Version History and Enterprise Application

### What is JavaEE?
- In current time, there are not any term JavaEE, JavaEE change to JakartaEE. Oracle have proprity of JavaEE. In 2015, oracle think its not able to manage the JavaEE or not design at the market standards. Then Oracle make the allience, in that allience **IBM, Apache or RedHat** support the Oracle and All make the effort to go Java the real position, but all that not make the Java better.

- In Java, Python, .net or php, which is good for application perspective view ?
    - **.Net 7.x** version is good for application development.

- continue, oracle lanuched the JavaEE 8 version in Aug 2017, in 2017 oracle declare the he handover the JavaEE beacuse he cannot handle it. Oracle transfer the proprity to Eclipse, then Eclipse change the name from JavaEE to JakartaEE.

    - In Aug 2019, JakaratEE 8 new version launched its fully backward compatiable.
    
### Current Version are - 

| Version | Date or Description | 
| --- | --- |
| 8 | Aug 2019, fully backward compatiable |
| 9 | Dec 2020 |
| 9.1 | May 2021 |
| 10 | Sep 2022 |
    
- Which type of Application we made using JakartaEE ?
    - using JakaratEE we made Enterprise Application.

### Enterprise Application based on 4 layers

| SN | layer | Components | Description |
| :---: | --- | --- | --- |
| 1 | Web Layer | Servlet or JSP | Its used to make web application. |
| 2 | Web Service Layer | Rest API | Its communicate between application and server. |
| 3 | Enterprise Layer | JTA, JPA, JMS or etc | Its used to manage the transaction |
| 4 | Other Layer | Connector or Validators | Its used to managing the server. |

- JTA (Java Transaction API) : Its used to manage the transaction.
- JPA (Java Persistence API) : Its used to manage the database state, JDBC -> JPA -> ORM (Object Relational Mapping) Hybernet.
- JMS (Java Messaging Services) : Its used to managing message system in Bulk.

### Desktop Application GUI

| Component | Description | 
| --- | --- |
| UI | Swing or AWT |
| Data Layer | JDBC |
| Data Management | Collection Framework |

## 02 Web App and Server Internal Processing

There are 3 types of Application
| Application | Description |
| --- | --- | 
| Desktop Application | Which have Physical Boundry |
| Mobile Application | Which application run Mobile Device |
| Web Application | -- |

- Android Development
    - Java
    - Kotlin

- iOS Development
    - Objective C
    - Swift

- Cross Platform
    - Flutter based on DART
    - React Native based on JavaScript

- Difference Between API, Library, Framework

| Feature | API | Library | Framework |
| --- | --- | --- | --- |
| Definition | A set of rules that define how two pieces of software can communicate with each other. | A collection of pre-written code that developers can use in their own applications. | A more comprehensive software development tool than a library that provides a set of pre-written code and conventions that can be used to build a complete application. |
| Use cases | Used to allow developers to integrate their applications with other services. | Used to perform common tasks in software applications. | Used to build complete software applications. |
| Level of control | Developers have complete control over how the API is used in their application. | Developers have complete control over how the library is used in their application. | Developers have less control over how the framework is used in their application, but they benefit from the pre-written code and conventions that the framework provides. |

- Every Web Service is a Web API.

Examples:
- API: Google Maps API, Twitter API, Facebook API.
- Library: Python standard library, NumPy library, OpenCV library.
- Framework: Django web framework, React Native mobile framework, Laravel PHP framework.

- Browser is Desktop or Web Application ?
    - is Desktop Application.

- What is SSL ?
    - SSL (Secure Socket Layer) is a one type of certificate, which provide some encryption.

There are 2 types of web application.
- Web Application
    - Static Web Application (Website)
    - Dynamic Web Application (Web Portal & Web App)

- Web application are deploy some where not install.
- Server is a desktop application.

Server Specification

| Name | Who Made | 
| --- | --- |
| **Tomcat** | **Apache** |
| JBOSS | JBOSS |
| Web Logic | Oracle |
| Web Sphere | IBM |
| Glan Fish | Sun -> Oracle |
