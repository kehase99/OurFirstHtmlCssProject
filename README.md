
````
.container{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    column-gap: 10px;
    row-gap: 10px;
    margin-top: 15px;
    margin-bottom: 15px;
}
.container .service{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 48%;
    height:250px;
    border-radius: 10px;
    background-color: var(--main-text-color);
}

.container .service:hover{
    transform: scale(1.05);
    transition: transform 0.5s ease;
}
.container .service .image-container{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    height: 65%;
}
.container .service .image-container img{
    display: flex;
    width: 100%;
    height: 100%;
    border-bottom: 3px solid var(--main-content-background-color);
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}
.container .service .text-container{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}
.container .service .text-container h3{
    margin-bottom: 10px;
}


@media (max-width: 768px) {
    .container .service{
        width: 96%;
        
    }

    .container .service .text-container *{
        text-align: center;
    }
    .header{
        text-align: center;
    }
}


````


````
/*contact-cotainer{
    display: flex;
    justify-content: center;
    width: 100%;
    /*align-items: center; commented
    height: 400px;*/
/*}*/

.contact-us-box{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 30%;
    background-color: var(--main-text-color);
    height: 350px;
    margin:20px;
    border-radius: 10px;
    margin-bottom: 20px;

}

form{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    margin-top: 10px;
    width: 100%;
}
contact-form{
    display: flex;
    flex-direction: column;
    /*margin-bottom: 10px;* commented/
   /* height: 100%;
    width: 100%;
}
label, input, textarea{
    margin-bottom: 10px;
    margin-left: 10px;
    margin-right: 10px;
    font-size: 1.2rem;
}
textarea{
    padding: 10px 0;
}
label{
    font-size: 0.8rem;
}

    input[type="submit"]{
    width: 94%;
    margin: 10px;
    padding: 5px;
    background-color: var( --main-navbar-background-color);
    color: var(--main-text-color);
    border: none;
    cursor: pointer;
    border-radius: 5px;
}
/*
@media (max-width:768px) {
    .contact-us-box{
        width: 100%;
        margin: 0 50px;
    }
    input[type="submit"]{
        font-size: 0.8rem;
        margin-left: 5px;
        margin-right: 5px;
        padding: 5px;
    }
}
    


*/
````
````
/*.navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: var(--main-navbar-background-color);
    padding: 15px;
}

.navbar a{
    text-decoration: none;
    color: var(--main-text-color);
    padding: 1.0rem;
}
.logo > a{
    background-color: var(--main-navbar-hover);
    border-radius: 10px;
}
.logo > a > span{
    background-color: var(--main-navbar-background-color);
    padding-top: 16px;
    padding-bottom: 16px;
    margin-left: -13px;
    margin-right: -13px;
    padding-left: 10px;
    padding-right: 10px;
    border-radius: 8px;
}
/*.logo > a{
    background-color: var(--main-navbar-hover);
    border-radius: 10px;
}
.logo > a > span{
    background-color: var(--main-navbar-background-color);
    padding-top: 16px;
    padding-bottom: 16px;
    margin-left: -13px;
    margin-right: -13px;
    border-radius: 8px;
    padding-left: 10px;
    padding-right: 10px;  
}
.logo > a > span{
    font-size: 0.8re;
}*/
/*.navbar-link{
    display: flex;
    list-style-type: none;
}
.navbar-link li{
    margin-left: 20px;
}

.navbar-link a{
    font-size: 1.2rem;
}
.navbar-link a:hover{
    background-color: var(--main-navbar-hover);
    padding: 19px;
}
.active{
    background-color: var(--main-navbar-hover);
}

.humberger{
    display: none;
    flex-direction: column;
    cursor: pointer;
}
.humberger > .line{ 
    width: 25px;
    height: 3px;
    margin: 3px 0;
    background-color:var(--main-text-color);
}*/

@media (max-width: 768px) {
   /* .navbar-link{
        display: none;
        flex-direction: column;
        width: 100%;
        background-color: var(--main-navbar-background-color);
        position: absolute;
        top: 57.5px;
        left: 0;
    }

    .navbar-link > li{
        text-align: center;
        margin: 15px 0;
    }
    .humberger{
        display: flex;
    }*/
    .gallery .image-gallery{
        width: 45%;
    }
    /*.navbar-link a:hover{
        background-color: var(--main-navbar-hover);
        padding: 10px;
        padding-bottom: 10px;
    }
    .active{
        background-color: var(--main-navbar-hover);
        padding-bottom: 10px;
    }*/
}

````

````
/*.register-cotainer{
    display: flex;
    justify-content: center;
    width: 100%;
}
.register-box{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 30%;
    background-color: var(--main-text-color);
    height: 300px;
    margin-top: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
}
form{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    margin-top: 10px;
    width: 100%;
}
.register-form{
    display: flex;
    flex-direction: column;
    height: 100%;
    width: 100%;

}
label, input{
    margin-bottom: 10px;
    margin-left: 10px;
    margin-right: 10px;
    font-size: 1.2rem;
}
label{
    font-size: 0.8rem;
}
input[type="submit"]{
    width: 91%;
    margin: 10px;
    padding: 5px;
    background-color: var( --main-navbar-background-color);
    color: var(--main-text-color);
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
@media (max-width: 299px) {
    .register-box{
        width: 100%;
        margin: 0 10px;
    }
}
@media (min-width: 300px) and (max-width: 768px) {
    .register-box{
        width: 100%;
        margin: 0 200px;
    }
}
*/



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    .row{
      display: grid;
      grid-template-rows: 250px 250px;
      grid-template-columns: 500px 500px;
        
    }
    .column{
      font-size: 3rem;
      background-color: darkviolet;
      border: 2px solid rgb(123, 162, 143);
      color: white;
        
    }
    .column >img{
        width: 100%;
        height: 100%;
    }
    </style>
</head>
<body>
    <div class="row">
        <div class="column"><img src="./Bus.jpg" alt="bus"></div>
        <div class="column"><img src="./Taxi.jpg" alt="Taxi"></div>
        <div class="column"><img src="./Train.jpg" alt="Train"></div>
        <div class="column"><img src="./Boat.jpg" alt="Boat"></div>
    </div>
</body>
</html>
````