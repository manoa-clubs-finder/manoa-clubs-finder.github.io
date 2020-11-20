## Table of contents

* [Overview](#overview)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Contact Us](#contact-us)



## Overview

Manoa Clubs Finder is a web application that provides a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, meeting times and locations, URLs to their websites (if any), contact information for officers, and a few select photos.

Manoa Clubs Finder has three user roles, all of whom login with their UH ID. Regular users browse the directory. Club Admins have the ability to edit the data associated with their club. Super Admins make sure site content is appropriate and grant “club admin” privileges to selected users.

Users can sort through all the clubs using catagories or keywords and can specify interest areas, and be notified when a new club is created matching that interest area (or an existing club adds that interest area).

This web application uses information from [Student Life and Development at UH Manoa](http://www.manoa.hawaii.edu/studentlife/studentorg/rio.php) to get all the Registered Independent Organizations at UH Manoa.

## User Guide

This section provides a walkthrough of the Manoa Clubs Finder user interface and its capabilities.

### Sign in and sign up

Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" to go to the following page and login. You must have been previously registered with the system to use this option:

![](images/Login.PNG)

Alternatively, you can select "Sign up" to go to the following page and register as a new user:

![](images/register.PNG)

### Home Pages

After logging in, you are taken to the home page depending what role you have on the site. The different roles are club admin, user, and super admin.

#### Club Admin Home

When you login to this site with the club admin role, you are taken to this page. It shows you the things you can do being a club admin.

![](images/clubadminhome.PNG)

#### Super Admin Home

When you login to this site with the super admin role, you are taken to this page. It shows you the things you can do being a super admin.

#Super Admin Home image here!

#### User Home

When you login to this site with the user role, you are taken to this page. It shows you the things you can do being a user.

#User home image here!

### Club Search

This is the page where users can view all the clubs in Manoa. You can filter the club by certain catagories.

#club search image here!

## Community Feedback

We are interested in your experience using Manoa Clubs Finder!  If you would like, please take a couple of minutes to fill out the [Manoa Clubs Finder Feedback Form](https://docs.google.com/forms/d/e/1FAIpQLSdTZstgumOwQexxq4t9Ax4-_o3eCTdFLJ3gSHCjZxQBMfPI4Q/viewform?usp=pp_url). It contains only five short questions and will help us understand how to improve the web application.

## Developer Guide

This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, visit the [Manoa Clubs Finder application github page](https://github.com/manoa-clubs-finder/manoa-clubs-finder), and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo.  However you do it, download a copy of the repo to your local computer.

Third, cd into the bowfolios/app directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Application Design

## Development History

## Contact Us

If you have any questions or queries you can contact any of the developers below.

* Jake Uyeda (jakeu@hawaii.edu)
* Tri Pham (tripham@hawaii.edu)
* Christian Siador (cjsiador@hawaii.edu)
