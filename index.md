<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Montserrat&amp;display=swap" rel="stylesheet">
    <style>
        body {
            background-color: black;
            height: 100vh;
            /* background-image: url('images/layer.png'); */
        }
        #mainContainer img {
            width: 100%;
            padding: 5px;
        }
        .jumbotron {
            background-color: transparent;
            text-align: center;
        }
        .jumbotron h1 {
            font-weight: bold;
        }
        .jumbotron h1, p {
            font-family: 'Montserrat', sans-serif;
            color: #d7d7d7;
        }
        .jumbotron p {
            font-size: 1rem;
        }
    </style>
</head>
<body>

    <div class="container" id="mainContainer">
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
              <h1 class="display-5">Guddi. VishwaTeja Goud</h1>
              <p class="lead">Sometimes you just need to #Accept</p>
            </div>
        </div>
        <div class="row h-100">
            <div class="col-md-4 p-0">
                <img src="./images/1.jpg" alt="" />
                <img src="./images/11.jpg" alt="" />
                <img src="./images/10.jpg" alt="" />
            </div>
            <div class="col-md-4 p-0">
                <img src="./images/2.jpg" alt="" />
                <img src="./images/12.jpg" alt="" />
                <img src="./images/14.jpg" alt="" />
                <img src="./images/6.jpg" alt="" />
            </div>
            <div class="col-md-4 p-0">
                <img src="./images/3.jpg" alt="" />
                <img src="./images/13.jpg" alt="" />
                <img src="./images/15.jpg" alt="" />
            </div>
        </div>
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
              <p class="lead">Created by Mr.Ram</p>
            </div>
        </div>
    </div>

    <!-- <script>
        var domEle = document.getElementById('mainContainer');
        for(var i = 1; i < 14; i++){
            var ele = document.createElement('img');
            ele.setAttribute('src', `./images/${i}.jpg`);
            domEle.appendChild(ele);
        }
    </script> -->

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
</body>
</html>