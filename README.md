<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>FriendFinder Readme</title>

    <!-- Latest compiled and minified CSS & JS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    <script src="https://code.jquery.com/jquery.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>

    <!-- Font Awesome Glyphicons -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css">

</head>

<body>

    <div class="container">

        <div class="jumbotron">
            <h1>
                <i class="fa fa-facebook-square" aria-hidden="true"></i> Friend Finder</h1>
            <hr>
            <h2>Answer a few basic questions. </h2>
            <h2>Then find the friend with the greatest compatibility!</h2>
            <br>

            <div>
           
                
            </div>

        </div>

        <div class="container">
            <div>
                <lu>
                    <h2>

                        <p> The survey will have 10 questions. Each answer will be on a scale of 1 to 5 based on how much the
                            user agrees or disagrees with a question.
                        </p>
                        <br>

                        <p> The npm packages used express, body-parser and path.
                        </p>
                        <br>

                        <p>
                            The htmlRoutes.js file contains two routes: A GET Route to /survey that displays the survey page, and catch-all route that
                            leads to home.html that displays the home page.
                        </p>
                        <br>

                        <p>
                            Your apiRoutes.js file contains two routes: A GET route with the url /api/friends. Which displays a JSON of all possible
                            friends, and a POST route /api/friends. This handles incoming survey results.
                        </p>
                        <br>
                        <p>
                            The compatibility logic is to convert each user's results into a simple array of numbers
                        </p>
                        <br>
                        <p>
                            (ex: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]).
                        </p>
                        <br>
                        <p>
                            With that done, compare the difference between current user's scores against those from other users, question by question.
                            Add up the differences to calculate the totalDifference. Example:
                        </p>
                        <br>
                        <p>
                            User 1: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1] User 2: [3, 2, 6, 4, 5, 1, 2, 5, 4, 1]
                        </p>
                        <br>
                        <p>
                            Total Difference: 2 + 1 + 2 = 5
                        </p>
                        <br>
                        <p>
                            You should save your application's data inside of app/data/friends.js as an array of objects. Each of these objects should
                            roughly follow the format below.
                        </p>
                        <br>
                        <p>
                        After identifying the compatible friend, the result will display as a modal pop-up.
                    </h2>
            </div>
        </div>
        <!-- end of container -->

        <footer class="footer">
            <div class="container">
                <p>
                   <a href="https://serene-ridge-11950.herokuapp.com/">FriendFinder</a> |
                    <a href="https://github.com/pcheno/friendfinder">GitHub Repo</a>
                </p>
            </div>
        </footer>

    </div>


</body>

</html>