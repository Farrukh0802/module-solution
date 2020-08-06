
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/main.css">
    <title>Assignment Solution for Module 2</title>
<style>
    body{
    width: 100%;
    
}
.wrapper{
    margin: 3rem auto;
    display: flex;
    justify-content: center;
    font-family: sans-serif;
}
h1{
    text-align: center;
    margin: 20px 0;
}
section{
    margin: 0 10px;
}
.first{
    background-color: #999999;
    width: 28%;
    padding: 10px;
    position: relative;
    border: 2px solid black;
    
}
.second{
    background-color: #999999;
    width: 28%;
    padding: 10px;
    position: relative;
    border: 2px solid black;
}
.third{
    background-color: #999999;
    width: 28%;
    padding: 10px;
    position: relative;
    border: 2px solid black;
}
.chicken{
    background-color: #D59898;
    font-size: 18px;
    position: absolute;
    top: -1px;
    right: -1px;
    padding: 5px 15px;
    border: 1px solid black;
    width: 20%;
    text-align: center;
}
.beef{
    background-color: #C14543;
    color: #ffffff;
    font-size: 18px;
    position: absolute;
    top: -1px;
    right: -1px;
    padding: 5px 15px;
    border: 1px solid black;
    width: 20%;
    text-align: center;
}
.sushi{
    background-color: #E5D198;
    font-size: 18px;
    position: absolute;
    top: -1px;
    right: -1px;
    padding: 5px 15px;
    border: 1px solid black;
    width: 20%;
    text-align: center;
}
.text{
    padding-top: 28px;
    padding-bottom: 10px;
}
@media (min-width: 992px) and (max-width: 1200px){
    .wrapper{
        width: 100%;
    }
}
@media (min-width: 768px) and (max-width: 991px){
    .first{
        width: 42%;
    }
    .second{
        width: 42%;
    }
    .third{
        width: 89%;
        margin-top: 10px;
    }
    .wrapper{
        display: flex;
        flex-wrap: wrap;
    }
}
@media (min-width: 400px) and (max-width: 767px){
    .first{
        width: 85%;
    }
    .second{
        width: 85%;
        margin-top: 10px;
    }
    .third{
        width: 85%;
        margin-top: 10px;
    }
    .wrapper{
        display: flex;
        flex-wrap: wrap;
    }
}

</style>
</head>
<body>
    <h1>Our Menu</h1>
    <div class="wrapper">
<section class="first">
    <div class="chicken">Chicken</div>
    <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti minus 
        iste sint doloribus, dolor, quam quibusdam nisi repudiandae, consectetur corporis vero 
        aliquam voluptate odio possimus Lorem ipsum dolor sit amet consectetur adipisicing laborum quo  </div>
</section>   
<section class="second">
    <div class="beef">Beef</div>
    <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti minus 
        iste sint doloribus, dolor, quam quibusdam nisi repudiandae, consectetur corporis vero 
        aliquam voluptate odio possimus Lorem ipsum dolor sit amet consectetur adipisicing laborum quo  </div>
</section>   
<section class="third">
    <div class="sushi">Sushi</div>
    <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti minus 
        iste sint doloribus, dolor, quam quibusdam nisi repudiandae, consectetur corporis vero 
        aliquam voluptate odio possimus Lorem ipsum dolor sit amet consectetur adipisicing  laborum quo</div>
</section>  
</div>
</body>
</html>
