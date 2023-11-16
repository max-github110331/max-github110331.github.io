<!DOCTYPE html>
<html>
    <head>
        <title>Max's Info</title>
        <link rel="icon" type="image/x-icon" href="https://cdn.discordapp.com/attachments/987515939434168363/1168905439820382259/1011016_esztfSBz.png?ex=65537706&is=65410206&hm=5dc9e6f3c6a8c6a7359b0c166fb3689d71bb6338bc4a536e034a3276e082e741&">
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Edu+TAS+Beginner&display=swap');
            @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
            @import url('https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap');
            @import url('https://fonts.googleapis.com/css2?family=IM+Fell+English+SC&display=swap');
            html {
                overscroll-behavior: smooth;
            }
            body {
                background-image: url("IMG_8788.gif"); 
                background-repeat: no-repeat; 
                background-attachment: fixed; 
                background-size: cover; 
                background-position: center; 
                display: flex; 
                align-items: center; 
                justify-content: center;
                cursor: grab;
            }
            div {
                postition: absolute; 
                top: 50%; 
                transform: translate(0, 15%); 
                padding: 10px;
                width: 45%; 
                height: 700px; 
                overflow-y: auto; 
                box-sizing: border-box;
                margin:0 auto;
                box-shadow: 0 0 16px 8px #000000;
                transition: transform .3s; 
                border-radius: 5px; 
                text-align: center;
            }
            h3 {
                color: #ffffff; 
                font-size: 12px; 
                font-family: "Press Start 2P";
            }
            p {
                color: #ffffff; 
                font-size: 20px;
                font-family: "Edu TAS Beginner", cursive;
            }
            button {
                box-shadow: 0 0 16px 8px #ffffff;
                color: #ffffff; 
                font-family: "Shadows Into Light", cursive;
                font-size: 20px;
                background: #000000; 
                background: rgba(0, 0, 0, 0.4);
                padding: 10px 35px; 
                width: 95%;
                text-align: center;
                border-radius: 5px;
                transition: transform 0.2s ease;
                cursor: grab;
            }
            button:hover {
                transform: scale(105%);
            }
            text {
                font-family: "IM Fell English SC", serif;
                color: #ffffff; 
                font-size: 10px;
            }
            @media (max-width: 1023px)  {
                body {
                    background-image: url('IMG_8788.gif'); 
                    background-repeat: no-repeat; 
                    background-attachment: fixed; 
                    background-size: cover;
                    display: flex; 
                }
                div {
                    postition: absolute; 
                    top: 50; 
                    transform: translate(0, 40%); 
                    padding: 0;
                    margin: 0; 
                    width: 90%;
                    height: 900px; 
                }
                h3 {
                    font-size: 20px;
                }
                p {
                    font-size: 30px;
                }
                button {
                    font-size: 30px;
                }
                text {
                    font-size: 15px;
                }
            }
        </style>
    </head>
    <body>
        <div class="info-box">
            <h3 id="text-1"></h3>
            <script>
                var text = "Hello! I am Max! Nice to meet you! Welcome to my info website!";
                var currentIndex = 0;
                var myTextElement = document.getElementById("text-1");


                var timer = setInterval(function() {
                    myTextElement.innerHTML += text[currentIndex];
                    currentIndex++;

                    
                    if (currentIndex === text.length) {
                        clearInterval(timer);
                    }
                }, 100);
            </script>
            <p>General Info</p>
            <a href="https://www.gov.hk/"><button>Hong Kong</button></a>
            <br>
            <button>Male</button>
            <br>
            <a href="https://www.plklsp.edu.hk/"><button>F.1 Student</button></a>
            <br>
            <a href="https://www.cgcbot.com/"><button>CGC HK Team Owner & Developer</button></a>
            <br>
            <p>Contact Info</p>
            <a href="https://www.instagram.com/max.ig110331/"><button>IG: <br>max.ig110331</button></a>
            <br>
            <a href="https://www.instagram.com/max.close_ig110331/"><button>IG: <br>max.close_ig110331</button></a>
            <br>
            <a href="https://discord.com/users/709748491873943644/"><button>Discord: <br>max.dc110331</button></a>
            <br>
            <br>
            <br>
            <text>©️Produced by max-github110331, all rights reserved and no plagiarism allowed©️</text>
        </div>
    </body>
</html>
