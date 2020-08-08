# 100 Days Of Code - Log

## Day 0: 7/7/20

### Today's Progress

Committed to #100DaysOfCode challenge.

## Day 1-2

### Today's Progress

- Reviewed the principles of REST.
- Defined route paths for clothing store app.
- Studied [CS50](https://online-learning.harvard.edu/course/cs50-introduction-computer-science) Lecture 2: Arrays.

### Thoughts

Today I got to understand the principle of Stateless in REST.

In REST applications, the session state is entirely managed by the client and the request must contain all the necessary information to be understood by the server.

If the server requires a shopping cart checkout, for example, each request must contain all the information required. This will most likely look like this: /user/1234/shopping-cart or /shopping-cart?userID=1234

The point is, everything needed to process the request should be in the request.

### Link(s) to work

- [Source code](https://github.com/ntochi/doremas-place/commit/d684d6f5624b440b1b87be8c7af5e75424c79b13)

## Day 3

### Today's Progress 

- I continued studying [CS50](https://online-learning.harvard.edu/course/cs50-introduction-computer-science) Lecture 2: Arrays.
- Read [Dan Abramov's](https://twitter.com/dan_abramov) Just JavaScript article on values & variables.

### Thoughts

From Dan's article, I loved the thrill I felt when I understood the concept of understanding variables as "wires". I used to think variables work like values maybe because of how the syntax is used interchangeably in tutorials and study materials.

I can now build on this mental model anytime I need to interpret code. Variables are "wires". Wires point to values. Values are of two types: Primitive values & Objects (and functions).

## Day 4

### Today's Progress

Couldn’t code much today. Spent some time working on the “about me” section of my portfolio. Also read a few tech articles.

### Thoughts

I enjoyed reading the Values & Variables article by Dan Abramov. He illustrated that the JavaScript world can be seen from two angles: the inside world & the outside world.

Studying JavaScript from the inside should be the foundation of our knowledge as opposed to the lower-level details that only serve as additions.

The exercises at the end of the articles really drives the concepts home.

## Day 5

### Today's Progress 

I continued working on my clothing store app. I was able to include header & footer partials in the relevant pages. I also installed & configured Tailwind CSS, decided that I will be using Tailwind to design the app.

### Thoughts

I hit a roadblock trying to install Tailwind in my Express app. After some research, I found that I needed to install & configure PostCSS globally in the app.

It was my first time hearing about PostCSS. I believe it is what I'd usually hear tech folks refer to as CSS in JavaScript. PostCSS is a development tool that uses JavaScript-based plugins to automate routine CSS operations.

After a few failed attempts, this [article](https://flaviocopes.com/tailwind-setup/) made it clearer and I was able to successfully configure Tailwind!

### Link(s) to work

- [Source code 1](https://github.com/ntochi/doremas-place/commit/b7c744515265e5c9bee033f781dd49024df2f7ab)
- [Source code 2](https://github.com/ntochi/doremas-place/commit/1b5b8403a6b79bee910b5a6aed7d7063a77f8fcc)

## Day 6-7

### Today's Progress 

For the online store app:

- I worked on the navigation bar; added some nav links for relevant routes.

- Read the documentation for Tailwind

### Link to work

- [Source code](https://github.com/ntochi/doremas-place/commit/2185224545d0e8b20a34720dc628fd0ef72dcd6d)

## Day 8

### Today's Progress 

Worked on a dropdown menu for the user account.

Today was one of those days when you’re not quite sure why your code isn't working 😩. Didn’t have much time to code today, would try again tomorrow 🚶🏻‍♀️

### Thoughts

Had a challenge getting the user dropdown menu to work. Wasn't sure if it was because of my files linked incorrectly or wrong code. Would review it again tomorrow.

Also, Tailwind is revealing a lot of my knowledge gaps in CSS. Whelp!

## Day 9-12

### Today's Progress 

Worked on the hero section of my portfolio. Also learned some cool tricks on how to make SVGs responsive with CSS.

### Link to work

- [Tweet](https://twitter.com/ntochi_/status/1285558276193693697?s=20)

## Day 13

### Today's Progress 

Solved some code challenges on JavaScript objects & properties.

## Day 14-16

### Today's Progress 

Found out there is more to Tailwind than I expected & I’m loving it!

Had to slow down to revisit some CSS layout concepts. Also redesigned the layout of my app to meet utility-first criteria.

### Thoughts

Spent some time reading about all things Tailwind. Read through most of the sections of the official documentation.

Deciding to incorporate Tailwind in my project revealed some CSS knowledge gaps I had 😑. I am glad this framework has an active community too!

## Day 17-19

### Today's Progress 

- Took a deeper look into APIs; data formats, endpoints, making requests, etc
- Researched various APIs available for a clothing store

### Thoughts

Using the wall socket & electricity distributors analogy, API can easily be related to consuming clients and service providers while the agreed "standards" between them keeps the API economy running effectively.

I was able to connect the dots with this [API 101 series](https://www.programmableweb.com/api-university/what-are-apis-and-how-do-they-work).

## Day 20-21

### Today's Progress 

- Worked on the index view page that displays a list of all products.

### Link to work

- [Source code](https://github.com/ntochi/doremas-place/commit/7338d2332415ee8b3515206a2a50552d4a469a6b)

## Day 22-23

### Today's Progress 

- Connected app to a database.
- Defined Mongoose schema & model.
- Created seed data that populates each time the app is reloads.

### Thoughts

Coding this part of the project gave me a better understanding of linking the MongoDB database, defining schema & compiling models.


### Link(s) to work

- [Source code 1](https://github.com/ntochi/doremas-place/commit/f03d087d8aeb443e7d3eb5b50085b14d18c57418)
- [Source code 2](https://github.com/ntochi/doremas-place/commit/ea7123651fed7a7b12d6e48a8b3269d303e21e8c)

## Day 24

### Today's Progress 

Coded a page that shows more information about the product when clicked. I did this by finding the product ID & then rendering the product info page.

### Thoughts

Today I noticed I'm beginning to understand why I have errors in my code and the bug that's responsible for that. It's exciting (for now 😅). Achieved this faster than I thought I would.

### Link(s) to work

- [Source code](https://github.com/ntochi/doremas-place/commit/0d180d4b1a513ecf90b82a4cea8c0578fea25c8d)

## Day 25-26

### Today's Progress 

- Redesigned the layout of the product info page.
- Fixed image responsiveness on smaller breakpoints.
- Added size & fit details.

### Thoughts

These kids are so cuteeee 🥺, can't help eeeet! On a technical note, is it safe to say I like flexbox?

### Link(s) to work

- [Tweet](https://twitter.com/ntochi_/status/1291738678860173312)
- [Source code](https://github.com/ntochi/doremas-place/commit/6f87fe10a57ad9c4c371e0e55c78aafae06742c7)
