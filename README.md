# Software Requirement Specification 


## Problem Statement: A few sentences to describe the problem you are trying to solve, i.e., justify why this software is needed.

Every month, about 200 goods are posted to the WeChat group. This number is still limited by the number of people in the WeChat group. There are only 500 people in one wechat group at most. 

There are many problems with using WeChat as an online marketplace.
* Many people don't want to add so many people on wechat.
* After a seller/buyer posts something in the WeChat group, in a few days people may not know that she has posted these things
* a lack of classification. Sometimes you only want to buy something when you see it, and sometimes you just want to buy something that is free. Sometimes you don’t know what others intended to sell, so you may not ask.
* There are still many problems (transaction records, evaluations of buyers and sellers, searches, etc.), because WeChat groups are not designed for buying and selling.



## Potential Clients: Who are influenced by this problem and would benefit from the proposed solution? (i.e. the potential users)
College Students
## Proposed Solution: Write a few sentences that describe how a software solution will solve the problem described above.
Online platform to buy and sell second hand goods.
Users can search items, so that people will not miss their potential buyers/sellers.

## Functional Requirements: List the (functional) requirements that software needs to have in order to solve the problem stated above. It is useful to try to group the requirements into those that are essential (must have), and those which are non-essential (but nice to have).
## Must have


1. Recommendation Algorithm,
 As a user of the app, I want to have good recommendations, so that I do not need to search in a wide range of products.
1. Online Chat
As a user of the app, I want to directly talk to the seller/buyer, so that I do not need to give out my phone number.




## Nice to have
1. Group Chat
As a user of the app, I want to have a group chat place, so that I  can receive group text messages from every like minded people. 
1. Third party login. 
As a user of the app, I want to login with my good account, so that I i do not need to spend time signing up. 

## Software Architecture



Client Side:
Client.js: Develop custom React components for data manipulations and to display data in UI
login.js: implement OpenID Connect Client to login with Google.

Server Side:
server.java: Create an java springboot server that interacts with MySQL and Create Java servlets with RESTful APIs to handle HTTP requests and responses.
item.java: Built relational (MySQL) database to capture event data 
Recommendation.java:   Recommendation Algorithm
User A likes Item A, Item C. User B likes Item B. User C likes Item A, Item C, Item D.
=> User A shares similar preference as User C compared to User B. User C also likes Item D=> User A may like Item D. 
Using Model-View Controller software design pattern.


## Wireframes

![GitHub Logo](https://github.com/aaronwu2017/mybooksapp/blob/master/123.png)

![GitHub Logo](https://github.com/aaronwu2017/mybooksapp/blob/master/1233.png)
