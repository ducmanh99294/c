<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @charset "utf-8";
.box1{
    padding: auto;
    margin: auto;
    width: 950px;
}
.box2{
    padding: 20px 10px;
    background-color: rgb(44, 223, 163);
    margin: auto;
    width: 930px;
}
.box1 ul li.next{
    display: block;
    position: absolute;
    top: 200px;
    margin-left: 890px;
    background-color: rgb(151, 123, 72);
}
.box1 ul li.pre{
    display: block;
    position: absolute;
    float: left;
    top: 200px;
    
    background-color: rgb(151, 123, 72);
}
.box2 ul li.next{
    display: block;
    position: absolute;
    top: 780px;
    margin-left: 850px;
    background-color: rgb(255, 255, 255);
    border-radius: 50%;
}
.box2 ul li.pre{
    display: block;
    position: absolute;
    float: left;
    top: 780px;
    background-color: rgb(253, 253, 253);
    border-radius: 50%;
}
ul li a{
    text-decoration: none;
    width: 60px;
    height: 80px;
    display: block;
}
.box2 ul li a{
    text-decoration: none;
    width: 80px;
    height: 60px;
    display: block;
}
ul{
    margin: 0;
    padding: 0;
    list-style-type: none;
}
li{
padding-top: 20px;
}
.box2 img{
    margin-left: 15px;
    margin-bottom: 10px;
}
.box2 img.pic2{
    margin-left: 90px;
    width: 750px;
}
.box1 img.Pic{
    width: 950px;
}

        
        </style>
</head>
<body>
    <div class="box1">
    <img src="https://get.wallhere.com/photo/landscape-hill-rock-nature-national-park-valley-wilderness-dusk-plateau-Formation-mountain-soil-geology-natural-environment-mountainous-landforms-landform-geographical-feature-wadi-badlands-123218.jpg" alt="" width="800px" class="Pic">
    <ul>
        <li class="next"><a href="#"><img src="https://www.svgrepo.com/show/111205/next.svg" alt=""width="60px"></a></li>
        <li class="pre"><a href="#"><img src="https://www.svgrepo.com/show/13655/back.svg" alt=""width="60px"></a></li>
    </ul></div>
    <div class="box2">
       <img  src="https://res.cloudinary.com/jnto/image/upload/v1/media/filer_public/06/83/0683b6d4-f167-4614-8070-ca04b9eeda02/train_wy0r4y" alt="" width="800px" class="pic2">
       <ul>
        <li class="next"><a href="#"><img src="https://www.svgrepo.com/show/111205/next.svg" alt=""width="50px"></a></li>
        <li class="pre"><a href="#"><img src="https://www.svgrepo.com/show/13655/back.svg" alt=""width="50px"></a></li>
    </ul>
    </div>
</body>
</html>
