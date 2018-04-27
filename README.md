<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
</head>

<body>

</body>
<header>
    <h1>Friend Finder</h1>
</header>
<section>
    <br>
    <h1>Description</h1>
    <h2>The survey will have 10 questions. Each answer will be on a scale of 1 to 5 based on how much the user agrees or disagrees
        with a question.</h2>
    <br>
    <h2>The htmlRoutes.js file contains two routes: A GET Route to /survey that displays the survey page, and catch-all route
        that leads to home.html that displays the home page.</h2>
    <br>
    <h2>Your apiRoutes.js file contains two routes: A GET route with the url /api/friends. Which displays a JSON of all possible
        friends, and a POST route /api/friends. This handles incoming survey results.</h2>
    <br>
    <h2>The application data stored inside of app/data/friends.json as json</h2>
    <br>
    <h2>The most compatible friend is determined using the following as a guide:</h2>
    <br>
    <h2>Convert each user's results into a simple array of numbers (ex: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]).</h2>
    <br>
    <h2>Now compare the difference between current user's scores against those from other users, question by question. Add up the differences to calculate the totalDifference.</h2>
    <br>
    <h2>User 1: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]</h2>
    <br>
    <h2>User 2: [3, 2, 6, 4, 5, 1, 2, 5, 4, 1]</h2>
    <br>
    <h2>Total Difference: 2 + 1 + 2 = 5</h2>
    <br>
    <h2>The closest match is the user with the least amount of difference.</h2>
    <br>
    <h2>The most compatible friend will be display as a modal pop-up.</h2>
    <br>
    <h1>Packages -Node used</h1>
    <br>
    <h2>express, body-parser and path</h2>
    <br>
    <h2>
        <a href="https://github.com/pcheno">Paul Chenoweth</a>
    </h2>
    <br>
    <h2>
        <a href="https://serene-ridge-11950.herokuapp.com/">FriendFinder</a>
    </h2>
</section>