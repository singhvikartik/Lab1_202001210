# 202001210_LAB1

LAB 1 - Software Engineering Lab (IT314)

Q.1. Identify FRs and NFRs:

Answer : 

A) FRs 

Why Building? As the size and capacity of the institute is increasing with the time, it has been proposed to develop a Library Information System (LIS)

1) Book borrowing(for member): Members should be able to borrow books through the system in a simple and efficient manner. This means that they should be able to search for books and place a hold on them, view the status of the books they have borrowed, and receive notifications about due dates and renewals with ease while sitting at his/her desk/chamber

2) Book return(for member): Members should be able to return books through the system, either by bringing them to the library or through an online interface again with ease. The book can be returned through middle men. This means that the system should be able to track when books are returned and update the status of the book accordingly.

3) Book renewal(for member): Members should be able to extend the due date of a borrowed book if no other reservation has been made for it. This means that the system should be able to calculate due dates, track renewals, and notify members of any changes to their borrowing status.

4) Transactions handling(for admin): The system should aid library staff in handling day-to-day book transactions, such as check-out and check-in. This means that the system should be able to record when books are borrowed and returned, update the status of the books in the collection, and generate reports on the usage of the collection.

5) Record management(for admin): The system should allow librarians with administrative privileges to enter new records for new books, or remove records for books that have been taken off the shelf. This means that the system should be able to manage the catalog of books, including adding new books, editing existing records, and removing books that are no longer part of the collection.

6) Book browsing(for member/non-member): The system should allow non-members to browse and search books online. This means that the system should have a public interface that allows users to view the collection, search for books, and view book details.

7) Interface: The web application must be able to run only within the institute LAN, meaning that access to the system should be restricted to users on the local network.


The FRs are important for ensuring the product is unique, specify the features and capabilities that the system must have to meet the needs of its users. FRs are the foundation of the system, as they describe what the system is intended to do and what it should be able to accomplish.


B) NFRs

1) Security:  Security is a non-functional requirement of the system. The requirement to take care that confidential information (such as passwords) is not stored in plain text is a security-related requirement. This means that the system should implement proper security measures, such as encryption or hashing, to protect sensitive data. The system is able to run within the institute LAN and implement proper security measures to protect confidential information.

2) Usability: The system is easy to use for both members and library staff. This means that the user interface is intuitive and the functionality is made the interaction of user and admin very easy on a click of button user can borrow,return book and admin can manage the whole system while sitting anywhere in the world. The system will also provide clear and concise feedback to users, such as error messages and confirmation messages.

3) Performance and scalability: As the size and capacity is increasing day to day the system must be able to handle the expected number of transactions and requests without becoming slow or unresponsive. This means that the system should have adequate processing power, memory, and storage to handle the volume of data it will be processing for that we should have adequate amount of servers. It is not possible to accomodate so many servers at the istitute as it would take huge space and will be costly. Instead to scale the servers we can use cloud servers which are cheaper, do not take space on the institute and can be scaled depending upon the traffic.

4) Availability: The system is available for use during the hours that the library is open. This means that the system should have adequate redundancy and failover mechanisms to ensure that it is always available for use, even if there is a failure or outage. So user do not have any discomfort while using the LIS.

5) Maintainability: The system is easy to maintain and upgrade over time. This means that the code should be well-documented and organized, and the system should be designed in a modular way that makes it easy to add or remove features. The system schedules is maintenance every sunday midnight and also notifies the members.

6) Interconnectivity: The system is able to integrate with other systems used by the library, such as the catalog system or the payment system. This means that the system should have the capability to exchange data with other systems and use data from other systems to support its functionality. LIS is partnered with RazorPay where users have multiple ways of payment such as UPI, Walle and Net Banking.


These NFRs are important for ensuring that the LIS is secure, easy to use, performant, scalable, available, maintainable, and interoperable. They help ensure that the system will meet the needs of the library and its users over the long term.

Q.2. Identify scope, features and non-functional aspects of the following problem.

A) Scope:
    
    Scope defines what the project aims to achieve, and it serves as a guide for decision-making during the project      development process by having a clearly defined scope, the project team can focus their efforts on delivering the solution within the specified boundaries and will be always on track about the project and they will know what is neccessary and whay is not?.   
  The scope of the problem is to create a mobile application that addresses the everyday needs of people with disabling hearing loss. The solution will use artificial intelligence to recognize key sound events, provide immediate alerts and continual logging, and be optimized for Android devices with low-latency.

B) Features:
  1) Artificial Intelligence-based recognition of key sound events (e.g. car horns and babies)
  2) Immediate alerts for recognized sound events
  3) Continual logging of sound events
  4) Optimized for Android devices
  5) Low-latency for real-time use

C) Non-Functional Requirements (NFRs):
  1) Scalable - As 466 million people can be the target for the problem
  2) User-friendly interface - Simplest UI to make their life easier
  3) Accessibility for people with disabilities  
  4) Security and privacy of user data 
  5) Performance and responsiveness of the system - As this app would be largely involved in their lives. So performance is      very important for them to make quick decisions. 
  6) Compatibility with different Android devices and operating systems.

