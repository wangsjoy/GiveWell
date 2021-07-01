Original App Design Project - README Template
===

# GiveWell

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Connects users to verified charities which most effectively "save or improve lives per dollar" (Givewell Mission statement). Would be used for financial transactions and developing a personal, philanthropic profile/footprint.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Fundraising/Crowdfunding
- **Mobile:** Mobile is essential since most charitable transactions occur on the web. By hosting an easy to navigate interface where users can make donations easily and share photos/media of donations made and impact, this can help encourage users to give charitably more frequently.
- **Story:** Creates a trusted network between organizations and "donors." Empowers people to donate any amount they can give (starting from $1 up), taking away the pressure of large donations. Creates a social impact footprint they can track in their profile.
- **Market:** Any individual can donate to organizations that have been verified on the app. (Commission-free transactions)
- **Habit:** Users are encouraged to check this app frequently to keep up their charitable footprint associated to their profile. By having a feature to share out their donations through social media, users can be reminded to use the app.
- **Scope:** V1 would allow users to search based on category tags for organizations. V2 would have location features to filter for organizations in their area. V3 would incorporate a log/charitable footprint associated to their account. V4 would incorporate social media options to share out their charitable giving.


## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User logs in to access donation platform
* User browses through GiveWell verified charities and feed, their impact statements, and media
* User can search based on tags (e.g. education, malaria fund, etc.)
* User can make financial transactions to organizations directly on the app without being redirected to the website.
* Profile pages for each user with past history of personal transactions and "impact calculator"

**Optional Nice-to-have Stories**

* When a user donates to an organization, they have the option to share a customizable post on social media
* Users are connected to others who have recently donated to the same organization
* Users can filter charities based on location tags

### 2. Screen Archetypes

* [Login / Register] - User signs up or logs into their account
   * A user must log in to gain access to the donation platform.
* [Organization Stream] - User can scroll through charity mission statements
   * User browses through GiveWell verified charities and feed
   * User can search based on tags (e.g. education, malaria fund, etc.) (search bar) 
* [Detail] - Organization Page
   * User can view the specifics of an organization (e.g. their impact per dollar, past recipients, relevant media)
* [Financial Transaction Screen] - Make donations
    * User can make financial transactions to organizations directly on the app without being redirected to the website.
* [Creation] - (Optional User Story) Social Media Share-out
   * When a user donates to an organization, they have the option to share a customizable post on social media
* [Profile] - User History
   * User can view their profile page with past history of personal transactions and "impact calculator" and any updates shared by organizations they have donated to in the past
* [Settings]
   * Lets people change language, and app notification settings.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Organization Stream
* Profile

Optional:
* Creation (Internal Feed)

**Flow Navigation** (Screen to Screen)

* Login
   * -> Account creation if no log in is available
   * -> Organization Stream
* Organization Stream
   * -> Detail
   * -> Financial Transaction Screen
* Profile
   * -> Settings
* Creation (Internal Feed) 
    * -> None, but future version will likely involve navigation to a detailed screen to see comments for each post

## Wireframes

![](https://i.imgur.com/eICghiY.jpg)

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
