
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