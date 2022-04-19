# Seminar-Seniors
Original App Design Project - README Template
===

# Seminar Seniors

## Table of Contents
1. [Overview](#Overview) 
3. [Product Spec](#Product-Spec)
4. [Wireframes](#Wireframes)
5. [Schema](#Schema)

## Overview
### Description
The concept of this app is to provide students of Alabama A&M different ticket options. Our app design will provide the user with tickets throughout the day, and locations if they need them. The user will be able to create an account, declare the main buildings that they use, and choose what part of campus they use.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category: Location Finder**
- **Mobile: This app will be used to help students find their way arouund campus ang get them the assistance that they need**
- **Story:**
- **Market: Students of AAMU**
- **Habit: People who needs assistance with adjusting to campus**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**For , we will identify the must-haves of the app.**

- [X] User can create a new account
- [X] User can login
- [X] Home Screen is styled 
- [X] Navigation bar is created
- [x] Home screen can show different departments on campus
- [x] Information on different departments added into app
- [x] Users can find information on specific departments
- [ ] Account is personalized
- [ ] User can choose which ticket they would need
- [ ] User can locate the building that they need by using the app


**Optional Nice-to-have Stories**

*

### 2. Screen Archetypes

* Login Screen
   * User can login
   * User can create a new account
* Stream
   * User can view different ticket options
   * User can view blueprint of campus
* Search
   * User can search for specific ticket
### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home
* Profile
* Messages

**Flow Navigation** (Screen to Screen)

* Home
   * Profile
   * Photo
   * Caption
* Profile
    * Settings
    * Personal Info
* Messages
    * Direct Message



## Wireframes
[Add picture of your hand sketched wireframes in this section]
![](https://i.imgur.com/ruz69nP.png)


### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
Post 
| Property | Type | Description |
|--------- | -----| ------------ |
| studentId | String | Gives student option to enter their student ID |
| loginId | String | Student has to login to get further assistance |
| ticketNumber | Integer | Ticket that directions student to right place | 
| departmentId | String | Information on specific department |
| createdAt | String | Date when ticket was created |
| mapId | String | Location of different buildings |
| ticketInfo | String | Description of different department |







### Networking
- Login Screen
  - Create/POST - Input Login information
  - Create/POST - create a login
- Account Page
  - Update/PUT - name, A#, email, phonenumer
  - Update/PUT - update user profile image 
- Map
  - Create/POST - click on building information
- Department 
- Create/Post - dropdown box for each department 
- Info Page
   - Create/Get - all department information,
   - Create/Post - submit a ticket buttion
- Submit a Ticket 
  - Create/Post - creating a submission for a ticket 
  - Create/Post - click submit buttion
- Your Ticket
  - Read/Get - pending ticket info
  - Read/Get - resolved ticket info

https://hackmd.io/da4gNHuISymqRv1dMx6w1Q

https://i.imgur.com/wVe4fCS.gif
