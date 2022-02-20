
# PWA Budget Tracker

Is a progressive Web Application (PWA) that enables the user to add expenses and deposits to their budget even without an online connection. When entering transactions offline, data syncs the total when connected back online.


### Live Application

Link to Live application site => https://nadia-budget-tracker.herokuapp.com/

### Screenshots

![enter image description here](https://raw.githubusercontent.com/nadiaalamgir21/pwa-budget-tracker/master/assets/s1.PNG)
  
![enter image description here](https://raw.githubusercontent.com/nadiaalamgir21/pwa-budget-tracker/master/assets/s2.PNG)

### User Story

AS AN avid traveller

I WANT to be able to track my withdrawals and deposits with or without a data/internet connection

SO THAT my account balance is accurate when I am traveling

  
  

### Acceptance Criteria

GIVEN a budget tracker without an internet connection

WHEN the user inputs an expense or deposit

THEN they will receive a notification that they have added an expense or deposit

WHEN the user reestablishes an internet connection

THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

  

## Table of contents

- [General Info](#Info)

- [Functionality](#Functionality)

- [Install](#Install)

- [Technologies](#Technologies)

- [Author](#Author)

  

# General Info

  

### What is Progressive Web Application (PWA)?

- A Progressive Web App (PWA) is a web app that uses modern web capabilities to deliver an app-like experience to users. These apps meet certain requirements (see below), are deployed to servers, accessible through URLs, and indexed by search engines.

  

### What is required for PWA?

To be considered a Progressive Web App, your app must be:

  

- Progressive - Work for every user, regardless of browser choice, because they are built with progressive enhancement as a core tenet.

  

- Responsive - Fit any form factor, desktop, mobile, tablet, or whatever is next.

  

- Connectivity independent - Enhanced with service workers to work offline or on low quality networks.

  

- App-like - Use the app-shell model to provide app-style navigation and interactions.

  

- Fresh - Always up-to-date thanks to the service worker update process.

  

- Safe - Served via HTTPS to prevent snooping and ensure content has not been tampered with.

  

- Discoverable - Are identifiable as “applications” thanks to W3C manifests and service worker registration scope allowing search engines to find them.

  

- Re-engageable - Make re-engagement easy through features like push notifications.

  

- Installable - Allow users to “keep” apps they find most useful on their home screen without the hassle of an app store.

  

- Linkable - Easily share via URL and not require complex installation.

  

#### Offline Support

- Apps should be able to work offline. Whether that be displaying a proper "offline" message or caching app data for display purpose.

  
  

# Functionality

  

BUDGET-TRACKER Offline Functionality:

- Enter deposits offline

- Enter expenses offline

  

When brought back online:

- Offline entries should be added to tracker.

  

## *In order to achieve OFFLINE SUPPORT, a manifest file and a service worker file must be created.*

  

### Manifest ``` manifest.webmanifest ```

-  #### Purpose

- The manifest file is a simple text file (JSON file) that lists the resources (app's displayed name, icons, as well as splash screen) the browser should cache for offline access.

  

### Service Worker ``` service-worker.js ```

-  #### Purpose

- Service worker provides a programmatic way to cache app resources.

  

-  #### Service Worker Life Cycle

- install

- activate

- fetch

  
  

- The service worker is registered/linked in the front end side (main html ``` index.html ``` ).

  
  

# Install

```bash

npm i install

```

  

### Run

-   Install all dependencies

-   Create a terminal on the project root and run:

```` bash

mongod

````

-   Create another terminal on the same folder and run:

``` bash

npm start

```

# Technologies

- HTML5

- CSS

- jQuery

- Express

- MongoDB

- Mongoose

- IndexedDB

- Bootstrap

  

# Author

- Nadia A Alamgir
