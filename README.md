<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Milk Tea Tour</title>

<style>
    body {
        margin: 0;
        padding: 0;
        background: #d6d1b8;
        font-family: Arial, sans-serif;
    }

    .container {
        width: 100px;
        top: 7px solid black;
        bottom: 7px solid black;
    }

    .top-bar {
        display: flex
        justify-content: flex-end;
        padding: 10px;
    }

    .hamburger {
        width: 35px;
        height: 25px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        cursor: pointer;
    }

    .hamburger span {
        display: block;
        height: 4px;
        background: black;
        border-radius: 2px;
    }

    .section {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 25px 10px;
        flex-wrap: wrap;
    }

    .left {
        width: 55%;
    }

    h1 {
        font-size: 40px;
        margin-bottom: 10px;
        color: #000;
    }

    h3 {
        margin-top: -10px;
        margin-bottom: 20px;
    }

    p {
        font-size: 17px;
        line-height: 1.5;
    }

    .cta {
        margin-top: 20px;
        display: flex;
        gap: 15px;
    }

    .btn {
        padding: 12px 20px;
        font-size: 18px;
        font-weight: bold;
        border-radius: 10px;
        text-decoration: none;
        color: white;
        display: inline-block;
    }

    .join {
        background: red;
    }

    .contact {
        background: green;
    }

    .right img {
        width: 260px;
    }

    .divider {
        height: 7px;
        background: black;
        margin: 20px 0;
    }

    .section2 {
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
        padding: 25px 10px;
        flex-wrap: wrap;
    }

    .left2 {
        width: 55%;
        font-size: 18px;
        line-height: 1.6;
    }

    .left2 ul {
        margin-top: 5px;
        margin-bottom: 10px;
    }

    .right2 img {
        width: 320px;
        border-radius: 5px;
    }

    @media(max-width: 850px) {
        .left, .right, .left2, .right2 {
            width: 100%;
        }
        .right, .right2 {
            text-align: center;
            margin-top: 20px;
        }
    }
</style>

</head>
<body>

<div class="container">

    <div class="top-bar">
        <div class="hamburger">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </div>

    <!-- FIRST SECTION -->
    <div class="section">
        <div class="left">
            <h1>MILK TEA TOUR</h1>
            <h3>Make your self learn about Milk tea!</h3>

            <p>
                This website is dedicated to showcasing and educating about milk tea.
                It will serve those who want to learn new skills to make their own
                milk tea. I hope you enjoy and learn a lot from our lesson in this milk tea tour.
            </p>

            <div class="cta">
                <a href="#join" class="btn join">Join Now!</a>
                <a href="#contact" class="btn contact">Contact Now!</a>
            </div>
        </div>

        <div class="right">
            <img src="milk-tea.png" alt="Milk Tea Illustration">
        </div>
    </div>

    <div class="divider"></div>

    <!-- SECOND SECTION -->
    <div class="section2">
        <div class="left2">
            <p>Greet the customer politely</p>
            <p>Ask for their milk tea choice</p>

            <ul>
                <li>Ask what Flavor they want</li>
                <li>The size ( small, medium, large )</li>
                <li>The sugar level (0%, 25%, 50%, 75%, 100%)</li>
                <li>Ask them if they want an extra tapioca</li>
            </ul>

            <p>
                And their name they want them addressed when their milk tea is ready. <br>
                Confirm their order if you take it correctly.
            </p>
        </div>

        <div class="right2">
            <img src="shop.jpg" alt="Milk Tea Shop">
        </div>
    </div>

</div>

</body>
</html>
