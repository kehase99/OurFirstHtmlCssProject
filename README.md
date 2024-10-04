
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

/*
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
}*/