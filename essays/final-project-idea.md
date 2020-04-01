---
layout: essay
type: essay
title: "Final Project Idea: Student Discount App"
date: 2020-03-31
labels:
  - Software Engineering
  - Meteor
---

## Overview

**The problem**: One of the many perks of being a student is receiving discounts just for being one, but sometimes it can be difficult to know what discounts are available to you whether online or at your physical location. There are some online resources that connect students to discounts but they tend to only be for online use and not include what is available locally. Hawaii is known for its strong affinity to it residents and its Kama'aina discounts around the island which includes ones available to students they may not be aware of.

**The solution**: Create an online system where students can view discounts available to them and share ones they have found, along with rating the discounts and being shown recommendations for ones they may be interested in.

## Approach

A user will create their profile and specify their common interests. The app will populate a list of available discounts both locally and online that correspond to their specified interests. Users can search for specific discounts by category and by location, along with being able to add information about a discount they are aware of but is not available on the website. A simple star rating system will be used to let users know whether the discount in question is popular by having a high rating, or possibly no longer offered by having a low rating.

**Mock up pages:**

- Landing page
- User creation page
- User home page
- User profile page
- Admin page
- Personalized recommendation page
- Categorized discounts listing page
- Search discounts page
- Submit a discount page
- Listing of discounts by rating page

## Use case ideas

Some of the possible use cases:

- New user goes to landing page, creates an account, sets up profile
- Admin goes to landing page, logs in, edits any discounts needed
- User goes to landing page, logs in, sees recommended discounts
- User goes to landing page, logs in, search's for discount by category
- User logs in, adds a discount not already found
- User logs in, searches for a discount, rates discount

## Beyond the basics

Some considerations after the basic functions have been implemented:

- Notify user by email when a new discount is added that fits their interests
- Create a more elaborate rating system
- Allow users to post comments about a discount
- Allow user to mark an expired discount for possible admin deletion
- Low rated discounts can be flagged for admin deletion
- Map that shows location of businesses
