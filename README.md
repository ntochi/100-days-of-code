# 100 Days Of Code - Log

## Day 0: 7/7/20

### Today's Progress

Committed to #100DaysOfCode challenge.

## Day 1-2

### Today's Progress

- Reviewed the principles of REST.
- Defined route paths for clothing store app.
- Studied CS50 Lecture 2: Arrays.

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
