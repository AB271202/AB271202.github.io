---
layout: default
title: Home
---
<style>
    body {
        font-family: Arial, sans-serif;
    }
    div.container {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap; /* Ensures content adapts to smaller screens */
        margin: 20px;
    }
    div.content {
        max-width: 500px;
        margin: 20px;
        text-align: center;
    }
    img.profile-pic {
        width: 30%;
        max-height: 100%;
        padding: 20px;
    }

    @media screen and (max-width: 768px) {
        div.container {
            flex-direction: column; /* Stack content vertically on smaller screens */
        }
        img.profile-pic {
            width: 90%; /* Adjust image size for mobile */
            max-height: 90%;
        }
    }
</style>

<div class="container">
    <img class="profile-pic" src="me.jpeg" alt="Picture">
    <div class="content">
        I'm Anish Banerjee, a final year undergraduate in Computer Science and Engineering at the Indian Institute of Technology, Delhi. <br> 
        You can navigate the webpage by clicking on the sidebar (top left corner).<br>
        I've done some expository writing, which you can find out about in the <a href="notes">Expository Writing</a> section.<br>
        Find my CV <a href="./Anish_CV.pdf">here</a>.
        <br><br>
        You can contact me at <code>firstnamelastname2002@gmail.com</code>.
        <br><br>
        A big thanks to <a href="https://arponbasu.github.io/">Arpon Basu</a> for lending his website template! Also, thanks to <a href="https://shankhgupta.github.io/">Shankh Gupta</a> for designing the favicon!
    </div>
</div>
