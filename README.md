# La Petite Sirène Website

This is the website of a French restaurant franchise. The business serves relatively expensive food and also hosts 
events across four locations in Dublin. It's a simple responsive and trendy website that provides visitors with the current menu, 
an opportunity book tables and events and send feedback via email, as well as showing the opening times and locations on an interactive 
map.

## UX

#### User stories

**First Visitor Goals**

* First time visitors want to understand what the service offers, as well as where and when.
* First time visitors want to easily find the information they need, such as restaurant locations.
* First time visitors want to know what the quality of the service is like.

**Returning Visitor Goals**

* Returning visitors want to check the current menu.
* Returning visitors want to check information such as opening times and telephone numbers.
* Returning visitors want to make reservations and leave feedback.

** **

## Design

**Color Scheme**

The site uses a a simple and minimalistic color scheme of black, white and occasionally beige and light orange to highlight 
important elements. The color scheme reflects what one might expect to find the interior of a higher end restaurant to look like. Overall,
the layout is also reminiscent of a menu. 

**Typography**

The site uses the Cedarville Cursive and Cursive fonts. Cedarville Cursive is used for the brand name and some headers. It's a very 
decorative font which makes it excellent for highlighting the most important elements and particularly the brand name, but as it can be 
laborious to read, it was used very sparingly to maintain its impact and ensure clarity of the content. Recursive is used for most of 
the content of the site instead. The fallback fonts are sans-serif and cursive, respectively.

**Imagery**

The site utilizes black and white images that both fit together well with the color scheme of the site and convey the aesthetic of the 
business. The Home page contains a space for a double-background image with the second one having a background color instead to better 
display text. The page for reservations uses a single background image. The rest of the images are the facades and interiors 
of the business on the Locations page.

** **

## Wireframes

Preliminary wireframes were drafted in MS Paint. [Link](#)

## Features

* Responsive on all screen sizes.
* Each page includes a navigation bar.
* Each page includes a footer with links to restaurant's social media and copyright information.
* The main page includes a short description of the business' purpose and buttons to view the menu and contact form.
* Menu page includes the menu.
* Contact page includes a functional contact form, as well as guidance as to what the form is best used for.
* The Loations page includes images of the franchise locations, as well as their address and opening times. This page also includes a 
functional Google Map that can be used to view the restaurant locations or the user's current location.

**Features To Implement**

* A food ordering functionality with a cart that stores selected items and calculates price totals would ideally be available. 
Currently this is beyond the scope of the tools used for this site, however.
* Offering better visibility for customer reviews. This was initially considered, but in general terms most such 
businesses seem to handle customer experiences via external means such as Google. An info window for the Google Maps showing the business' 
Google reviews for a selected marker could be one option. 

** **

## Languages used

* HTML5
* CSS3
* JavaScript

** **

## Frameworks, Libraries & programs

1. Bootstrap 4.5:
* Used for responsive styling.
2. Font Awesome:
* Used for the star icons separating items on the Menu page.
3. Google Fonts:
* Used to import the fonts used for the website.
4. JQuery:
* Used to enhance navbar responsiveness on smaller device sizes.
5. Git:
* Used for version control via the Gitpod terminal.
6. Github:
* Used to store the website’s code after pushing from Git.

** **

## Testing

The W3C Markup Validator and W3C CSS Validator were used to ensure there are no syntax errors.

W3C Markup Validator [Results](#)

W3C CSS Validator [Results](#)

**Known Issues**



## Deployment

**Github Pages**

The project was published on Github Pages with the following steps:
1. Login to Github and locate the [repository](https://github.com/ssruoh/CI_MS2)
2. Locate the Settings button of the repository
3. Scroll down the Settings page to the Github Pages section
4. Under Source, select "Branch: master" from the dropdown menu
5. Click Save, the page will refresh
6. Scroll down to the Github Pages section again and locate the published link to the [site](#)

**Forking The Repository**

The copy of the Github repository can be forked to another account for viewing or editing without affecting the original one with the following steps:

1. Login to Github and locate the [repository](https://github.com/ssruoh/CI_MS2)
2. On top right, right under the Account menu and Notifications, click on the Fork button. This will create a copy of the repository to your Github account.

**Creating A Local Clone**

1. Login to Github and locate the [repository](https://github.com/ssruoh/CI_MS2)
2. Click on the green Code button
3. Click on the clipboard icon under "Clone with HTTPS" to copy the link
4. Open Git Bash
5. Change the current working directory to whereever you want the clone to be created.
6. Type `git clone` and paste the URL you copied from the clipboard:

```
$ git clone https://github.com/ssruoh/CI_MS2
```

7. Press Enter to create a local clone.

```
$ git clone https://github.com/ssruoh/CI_MS2
> Cloning into `Spoon-Knife`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```
** **

## Testing User Requirements In UX section

**First Time Visitors**




## Credits

**Code**

**Bootstrap4**: Various Bootstrap Library resources were used throughout the site.

An altered version of [this solution](https://www.youtube.com/watch?v=bh3UAetYkUI&t=184s) was used for the side-by-side image layout for index.html.

The basic idea for the index.html layout was taken from entry 14. in [this article](https://www.sitebuilderreport.com/inspiration/restaurant-websites) on web design layouts, ‘Zia Sonia.’

The Geolocation functionality of the Google Maps utilized for the locations page relies heavily on [the code provided by Google](https://developers.google.com/maps/documentation/javascript/geolocation#maps_map_geolocation-javascript) for the same functionality.

Similarly, [the Google code for using markers](https://developers.google.com/maps/documentation/javascript/marker-clustering) was used, although it was customized for the purposes of this site to a larger degree.

The fictitious phone numbers for the business were taken from [this site](https://fakenumber.org/ireland) for fake number generation.

**Content**

Site content was written by the developer.

**Media**

The images used for the site were obtained from Google Images.

**Acknowledgments**

Code Institute Tutors for their support.

My Mentor for ideas and feedback.

Friends for helping to test the site.