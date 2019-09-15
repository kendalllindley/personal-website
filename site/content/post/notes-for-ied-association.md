---
title: Notes for IED Association
date: 2019-08-25T14:27:38.124Z
description: Keeping my ideas in one place.
location: (This shouldn't be here.)
---
## Functional Requirements

* Add Color
* Event management
  * Online Registration
  * Online Payment
  * Calendar display options grid and list to help guide final decision.
* Membership signup / renewal
* Online Store capability tied to PayPal
* Email/newsletter Subscription

## Colors brainstorm:

* Primary: #165153 - I like the green earthy tone. The deep natural color feels welcoming.

## Theme Options

### Neve

[Demo](http://justfreethemes.com/demo/?theme=Neve)

#### Pros

* newsletter subscription
* bright colors / smooth animations
* shopping cart experience

#### Cons

* no event management out of the box
* no additional layout options

#### Other

* Based on WooCommerce

### Social Care Lite

[Demo](http://justfreethemes.com/demo/?theme=Social%20Care%20Lite)

#### Pros

* Contact info is easy to find
* strong use of color

#### Cons

* Slider on the homepage
* Inconsitent fonts on shopping cart
* lower shopping eperience (versus neve)
* No Event Management

### Fundraiser Lite

[Demo](https://www.sktperfectdemo.com/demos/fundraiser/)

#### Pros

* Colors
* Post (event?) layout options
* Mulitple Call to Action Paths (for members, events, volunteers, etc)
* Services page allows for the different functions of the association to be represented (Chapters, annual events, shows, etc.)
* Many additional layout options

#### Cons

* No Shopping Experience
* No Event Management

### Theme Installation

I had to increase my upload max filesize.

1. In File Explorer, open xampp/php/php.ini in notepad.
2. Find (CTRL + F) "upload_max_filesize"
3. replace "upload_max_filesize=2M" with "upload_max_filesize=8M"
4. Save the file.
5. Stop and Start Apache in the XAMPP Control Pannel.

## Meeting Notes 2019-09-03

* can the "inner page header" be changed on each page?
* security is important
* Robin likes the social care theme

### Thought Capture

* Double check mobile use
* Try colors for demo
* Add some real content
* Check functional requirements and document required plugins

## 2019-09-12

I managed to make color changes to the theme by copying the inline styles from \wp-content\themes\social-care-lite\inc\customizer.php and pasting them into my child themes css file and adding !important to my changes. I decided not to change the original theme files. Figured that !important, while ugly, are better than having the theme break next time they upgrade.

## 2019-09-15
.header-top .container .logo needs a max width of 400px.
