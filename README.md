# cs260-startup
Personal project for CS260

Programming Pair: Harrison Cole

For our project, we are going to do a Blackjack simulator. Blackjack is one of the most popular betting games at the casino for the simple reason that it seems so easy to cheat. The point is for the players to reach 21 with a combination of cards dealt to them. We will simulate this game but with a little twist: Our blackjack simulator will be different however because it will cheat back, ensuring that the return on investment for the casino is greater. We hope to teach people the follies of gambling. In our game of blackjack the house always wins.

I had a hard time getting my table to fit within my section and not overflow into other sections as space was moved around but I figured out it was because I used absolute instead of relative. Fun stuff

For the Simon CSS I learned a lot about how to better structure my Startup page and keep it simple. 
For the UX design I realized a lot I need to change about my startup. I should at minimum get matching color schemes

2/22 HTML CSS deliverable
    CSS is a very interesting language. It's very frustrating when you get something set up just the way you want it, and then you go to adjust something else and it messes up what you just finished working on. It's a lot like tightening bolts on a car tire, you have to work evenly on all the elements in order to get it set up right, otherwise if you focus too much on one you will mess up everything else, or this thing you just spent time on as you go to mess with your other elements.

2/23 JS
    I cant say I really understand why I need arrow functions. If I'm making an arrow function why does it need to be a function in the first place. but hopefully i can find a use for them
    I think the differences between objects and classes are really interesting. I  really need to get more exposure to these concepts to understand their intricacies and why they are used in certain contexts so I can have a greater appreciation for them all

2/28 DOM
    So much fun working on injecting code into the DOM. I spent hours researching how to create elements and have them inherit the style I had set for cousin elements as well as have their own unique identifiers (card number and suit) and it was so much fun. I am so excited to finish up my blackjack game

3/6 Simon JS
    I learn best for sure when I just jump into the deep end and figure it out. I try and use all the practices to work on my startup and think of how I can use them correctly. It was great to see the examples in Simon and think of how I can implement them in my startup. I especially found helpful seeing the use of asyncs and promises to help me get an idea for what goes on in there and a more real life application as opposed to a simple "moo" that doesn't really convey the full usefullness.

3/10 Startup JS
    I loved to make this project. CSS and html without Javascript feel so empty, but as soon as you add in the javaScript the code sputters to life. Suddenly I have a reason to make my html elements and css elements functional. My buttons actually mean something. My website actually has purpose. Up next I need to work on making my functions async and returning promises so that they can run in tandem with my main thread.

3/22 Node.js/Express
    It's so easy to use. Writing get and posts are so simple, it formats the url for you and all you have to do is tell it what to accept. 
    "const apiRouter = express.Router();
    app.use(`/api`, apiRouter);"
    this well set up your path and allow you to handle all requests that include /api. from there you can differentiate between what they have after /api with other calls in a similar fashion. It's so simple.

3/24
    MongoDB Atlas was one of the most frustrating parts of this yet. I spent 5 hours trying to get it to work and it all came down to the fact that I hadn't given my user permissions because I thought that they had default permissions, because why am I creating a user why can't access the database??
    then I had to undo all the testing I had done in order to be able to launch to my website. very annoying
    
3/27 Simon Login
    I'm so excited to be able to fully implement my startup. MongoDB is such an interesting database. I have worked with SQLite before and it is very rigid, but that makes it so I'm always sure of whats going to happen. MongoDB has been easier to set up but I'm not entirely sure how to use it. I am excited to learn but the findOne returning a document is a little confusing
    
3/29 WebSockets
    I'm a little worried about attaching the websockets to my startup. My goal is to be able to have players play blackjack together but I may have bitten off more than I can chew. As I was reviewing the Simon websockets I was planning how I can use it to help me make my startup. 
    
4/5
    I think this is so cool. I hate porting my code so it's gonna be a total pain to change everything over, but I do appreciate the understanding of the HTML, CSS, and the appreciation I can have going forward being able to use frameworks. One thing I really think is cool is that the CLI will set up AND setup for deployment all for me. I don't have to worry about compressing the files or anything of the like.
