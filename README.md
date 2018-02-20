<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title>Mat</title>
    <link rel="stylesheet" type="text/css" href="./css/mat.css">
    <meta name="description" content="SlidesJS is a simple slideshow plugin for jQuery. Packed with a useful set of features to help novice and advanced developers alike create elegant and user-friendly slideshows.">
    <meta name="author" content="Nathan Searles">

    <!-- SlidesJS Required (if responsive): Sets the page width to the device width. -->
    <meta name="viewport" content="width=device-width">
    <!-- End SlidesJS Required -->

    <!-- CSS for slidesjs.com example -->
    <link rel="stylesheet" href="css/example.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <!-- End CSS for slidesjs.com example -->

    <!-- SlidesJS Optional: If you'd like to use this design -->
    <style>
        body {
            -webkit-font-smoothing: antialiased;
            font: normal 15px/1.5 "Helvetica Neue", Helvetica, Arial, sans-serif;
            padding-top:70px;
        }

        #slides {
            display: none
        }

        #slides .slidesjs-navigation {
            margin-top:3px;
        }

        #slides .slidesjs-previous {
            margin-right: 5px;
            float: left;
        }

        #slides .slidesjs-next {
            margin-right: 5px;
            float: left;
        }

        .slidesjs-pagination {
            margin: 6px 0 0;
            float: right;
            list-style: none;
        }

        .slidesjs-pagination li {
            float: left;
            margin: 0 1px;
        }

        .slidesjs-pagination li a {
            display: block;
            width: 13px;
            height: 0;
            padding-top: 13px;
            background-image: url(img/pagination.png);
            background-position: 0 0;
            float: left;
            overflow: hidden;
        }

        .slidesjs-pagination li a.active,
        .slidesjs-pagination li a:hover.active {
            background-position: 0 -13px
        }

        .slidesjs-pagination li a:hover {
            background-position: 0 -26px
        }

        #slides a:link,
        #slides a:visited {
            color: #333
        }

        #slides a:hover,
        #slides a:active {
            color: #ffffff;
        }

        .navbar {
            overflow: hidden
        }
    </style>
    <link rel="stylesheet" type="text/css" href="./css/mat.css">
</head>
<body>
<div id="meny">
    <div id="start">
        <h1><a href="index.html">Start</a></h1>
    </div>
    <div id="tider">
        <h1><a href="tider.html">Tider</a></h1>
    </div>
    <div id="mat">
        <h1><a href="mat.html">Mat</a></h1>
    </div>
    <div id="om-oss">
        <h1><a href="om-oss.html">Om oss</a></h1>
    </div>
    <hr id="hr1" width="800px">
    </hr>
</div>
<div id="a">
    <div id="logo">
        <img src="./img/logo copy.png" alt="tranan"/>
    </div>
    <hr color="black" width="1200px" size="5" float="right"></hr>
    <div class="container">
        <div id="slides">
            <img src="img/saft.png">
            <img src="img/fisk.png">
            <img src="img/hamburgggg.png">
            <img src="img/kaffe.png">
            <a href="#" class="slidesjs-previous slidesjs-navigation"><i class="icon-chevron-left icon-large"></i></a>
            <a href="#" class="slidesjs-next slidesjs-navigation"><i class="icon-chevron-right icon-large"></i></a>
        </div>
        <div>
            <ol>
                <ls><h1>Mat</h1></ls>
                <ls><h2>fiskar 100kr</h2></ls>
                <ls><h2>hamburgare 9001kr</h2></ls>
                <ls><h2>löven 1982658912657kr</h2></ls>
                <ls><h2>fin fisk 120kr</h2></ls>
                <ls><h2>finare fisk 130kr</h2></ls>
                <ls><h2>fattigmans fisk 2kr</h2></ls>
                <ls><h1>Dryck</h1></ls>
                <ls><h2>cola 10kr</h2></ls>
                <ls><h2>fanta 10kr</h2></ls>
                <ls><h2>sprite 10kr</h2></ls>
                <ls><h2>dr pepper 15kr</h2></ls>
            </ol>
        </div>
    </div>
    <!-- End SlidesJS Required: Start Slides -->

    <!-- SlidesJS Required: Link to jQuery -->
    <script src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
    <!-- End SlidesJS Required -->

    <!-- SlidesJS Required: Link to jquery.slides.js -->
    <script src="js/jquery.slides.min.js"></script>
    <!-- End SlidesJS Required -->

    <!-- SlidesJS Required: Initialize SlidesJS with a jQuery doc ready -->
    <script>
        $(function() {
            $('#slides').slidesjs({
                width: 940,
                height: 528,
                navigation: false
            });
        });
    </script>
    <!-- End SlidesJS Required -->
</div>
</body>
</html>
