<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>module 2</title>
    <link rel="stylesheet" href="style.css">
    <style>
      * {
    box-sizing: border-box;
}
h1 {
    font-family: cursive;
    text-align: center;
    margin-bottom: 15px;
}

.container #box1, #box2, #box3 {
    border: 2px solid black;
    background-color: silver;
    padding-left: 5px;
    padding-right: 5px;
    width: 400px;
    margin-left: 35px;
    margin-top: 90px;
    position: relative;

}
.chicken {
    float: right;
    margin-top: 0px;
    border-left: 2px solid black;
    border-bottom: 2px solid black;
    padding: 0px 30px 0px 30px;
    margin-right: -5px;
    font-family: sans-serif;
    background-color: rgba(248,149,152,0.65);


}
.beef {
    float: right;
    margin-top: 0px;
    border-left: 2px solid black;
    border-bottom: 2px solid black;
    padding: 0px 30px 0px 30px;
    margin-right: -5px;
    font-family: sans-serif;
    background-color: rgba(248,8,24,0.65);


}
.sushi {
    float: right;
    margin-top: 0px;
    border-left: 2px solid black;
    border-bottom: 2px solid black;
    padding: 0px 30px 0px 30px;
    margin-right: -5px;
    font-family: sans-serif;
    background-color: rgba(248,232,84,0.65);


}
.p1 {
    clear: left;
    margin-top: 30px;
    font-family: cursive;
    padding-bottom: 0px;
}

@media (min-width: 992px)  {
    .col-lg-1, .col-lg-2, .col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12 {
        float: left;
        border: 2px solid black;
    }


    .col-lg-1 {
        width: 8.33%;
    }

    .col-lg-2 {
        width: 16.66%;
    }
    .col-lg-3 {
        width: 25;
    }

    .col-lg-4 {
        width: 33%;
    }

    .col-lg-5 {
        width: 41.66%;
    }

    .col-lg-6 {
        width: 50%;
    }

    .col-lg-7 {
        width: 58.33%;
    }

    .col-lg-8 {
        width: 66.66%;
    }

    .col-lg-9 {
        width: 74.99%;
    }

    .col-lg-10 {
        width: 83.33%;
    }

    .col-lg-11 {
        width: 91.66%;
    }

    .col-lg-12 {
        width: 100%;
    }
}


@media (min-width: 768px) and (max-width: 991px){
    .col-md-1, .col-md-2, .col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,.col-md-11,.col-md-12 {
        float: left;
        border: 2px solid black;
    }

    .col-md-1 {
        width: 8.33%;
    }

    .col-md-2 {
        width: 16.66%;
    }
    .col-md-3 {
        width: 25;
    }

    .col-md-4 {
        width: 33%;
    }

    .col-md-5 {
        width: 41.66%;
    }

    .col-md-6 {
        width: 50%;
    }

    .col-md-7 {
        width: 58.33%;
    }

    .col-md-8 {
        width: 66.66%;
    }

    .col-md-9 {
        width: 74.99%;
    }

    .col-md-10 {
        width: 83.33%;
    }

    .col-md-11 {
        width: 91.66%;
    }

    .col-md-12 {
        width: 100%;
    }
}

@media (max-width: 767px)  {
    .col-sm-1, .col-sm-2, .col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9,.col-sm-10,.col-sm-11,.col-sm-12 {
        float: left;
        border: 2px solid black;
    }

    .col-sm-1 {
        width: 8.33%;
    }

    .col-sm-2 {
        width: 16.66%;
    }
    .col-sm-3 {
        width: 25;
    }

    .col-sm-4 {
        width: 33%;
    }

    .col-sm-5 {
        width: 41.66%;
    }

    .col-sm-6 {
        width: 50%;
    }

    .col-sm-7 {
        width: 58.33%;
    }

    .col-sm-8 {
        width: 66.66%;
    }

    .col-sm-9 {
        width: 74.99%;
    }

    .col-sm-10 {
        width: 83.33%;
    }

    .col-sm-11 {
        width: 91.66%;
    }

    .col-sm-12 {
        width: 100%;
    }
}
    </style>
</head>
<body>
<h1>Our Menu</h1>

<div class="container">
    <div class="col-lg-4 col-md-6 col-sm-12" id="box1">
        <h4 class="chicken">Chicken</h4>
        <p class="p1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla imperdiet elit at libero semper lacinia.
            Quisque maximus turpis dolor, eu imperdiet metus tincidunt sit amet.</p>
    </div>
    <div class="col-lg-4 col-md-6 col-sm-12" id="box2">
        <h4 class="beef">Beef</h4>
        <p class="p1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla imperdiet elit at libero semper lacinia.
            Quisque maximus turpis dolor, eu imperdiet metus tincidunt sit amet.</p>
    </div>
    <div class="col-lg-4 col-md-12 col-sm-12" id="box3">
        <h4 class="sushi">Sushi</h4>
        <p class="p1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla imperdiet elit at libero semper lacinia.
            Quisque maximus turpis dolor, eu imperdiet metus tincidunt sit amet.</p>
    </div>
</div>
</body>
</html>
