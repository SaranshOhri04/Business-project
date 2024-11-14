# Business-project
This webpage is likely for a small business. It includes a contact form and a brief description of their business model, highlighting the importance of customer relationships and profit margins.
![Screenshot (77)](https://github.com/user-attachments/assets/1553a8b3-036e-43b9-b711-0fa1913c63f6)
![Screenshot (78)](https://github.com/user-attachments/assets/2ba5238e-215b-4a95-b118-f7e597e1d023)
![Screenshot (80)](https://github.com/user-attachments/assets/be520b64-0e38-4efa-93e1-eb0f4ad27c8b)
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: darkgray;
            color: #333;
            padding-bottom: 25px;
        }

        header {
            background-color: #002366;
            /* Dark Blue */
            color: white;
            padding: 15px;
            text-align: center;
        }

        header .box1 {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        .box2 {
            background: url('banner.jpg') no-repeat center center/cover;
            color: blue;
            padding: 75px;
            text-align: center;
            background-color: white;
            border-radius: 50%;
        }

        .box1 {
            width: 80%;
            margin: 0 auto;
        }

        .box3 {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            color: black;
            background-color: white;
            border-radius: 4px;
            display: flex;
            align-items: center;
            flex-direction: column;
        }

        .box3 p {
            font-size: 20px;
        }

        .box4 {
            width: 80%;
            margin: 0 auto;
            color: black;
            background-color: lightgoldenrodyellow;
            padding-left: 10px;
            padding-top: 5px;
            border-collapse: collapse;
            border-radius: 5px;
            padding-bottom: 5px;
        }

        .box4 ul li {
            font-size: 20px;
        }

        section {
            padding: 20px 0;
        }

        .box5 {
            width: 80%;
            margin: 0 auto;
            background-color: white;
            border-radius: 2px;
            text-align: center;
            padding: 5px;
        }


        .box6 {
            border: 2px solid black;
            width: 300px;
            padding: 10px;
            background-color: white;
        }

        .header {
            text-align: center;
            padding: 10px 0;
            font-size: 1.2em;
            font-weight: bold;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th,
        td {
            border: 1px solid black;
            text-align: center;
            padding: 5px;
            color: aliceblue;
        }

        th {
            background-color: purple;
            color: white;
            font-weight: bold;
        }

        .total-row td {
            font-weight: bold;
        }

        footer {
            background-color: #333;
            color: lightskyblue;
            text-align: center;
            padding: 15px 0;
        }

        form {
            max-width: 500px;
            margin: 0 auto;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input,
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;

        }

        input[type="submit"] {
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
            width: 100%;
        }

        input[type="submit"]:hover {
            background-color: #555;
        }

        .box7 {
            width: 80%;
            margin: 0 auto;
            background-color: azure;
            padding-top: 5px;
            padding-bottom: 5px;
            padding-left: 20px;
            padding-right: 10px;
            border-radius: 25px;
        }

        .box8 {
            width: 80%;
            margin: 0 auto;
        }
    </style>
</head>

<body>
    <header>
        <div class="box1">
            <h1>Anil Kumar & Co.</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#Products">Products</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="home" class="box2">
        <h2>Welcome to My Business</h2>
        <p>We provide exceptional services to meet your needs.</p>
    </section>
    <section id="about">
        <div class="box3">
            <h2>About Us</h2>
            <p>Myself Anil Ohri,I am the owner of this company named <b>Anil kumar & Co</b>. I work as a prop-writer and
                deals in Wheat,Atta and maida.
                My company is committed to delivering high-quality products with large quantity. My company deals within
                north-india and lot of dealers work with our company to sell their brand product in every part of
                north-india.</p><br>

            <img src="data:image/jpeg;base64,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"
                alt="center" class="about-image">
            </p>
        </div>
    </section>
    <section id="Products">

        <div class="box5">
            <h2>Products</h2>
            <marquee>
                <pre>
<img src="data:image/jpeg;base64,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" alt="click me">               <img src="data:image/jpeg;base64,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" alt="click me">               <img src="data:image/jpeg;base64,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" alt="click me" class="Product-image">
<p><b>Flour                                 Wheat                                     Maida</b></p>
</pre>
            </marquee>
        </div>

        <div id="box6">
            <div class="header">Products</div>
            <table>
                <tr>
                    <th>Product Price[Per quintal]</th>
                    <th>Flour</th>
                    <th>Maida</th>
                    <th>Wheat</th>
                </tr>
                <tr>
                    <td>2023-24</td>
                    <td>Rs.3000</td>
                    <td>Rs.2925</td>
                    <td>Rs.2275</td>
                </tr>
                <tr>
                    <td>2024-25</td>
                    <td>Rs.3700</td>
                    <td>Rs.3215</td>
                    <td>Rs.2425</td>
                </tr>
            </table>

        </div>
    </section>
    <section id="services">
        <div class="box4">
            <h2>Our Services</h2>
            <ul>
                <li>We consult to our dealers with the best quality of products with some named brands and give it
                    to the coustmer or another dealers at reasonable rate.</li>
                <li> My development of the company depends upon the new market season and the number of dealer at
                    product rate so in total it approximately gives me 2-3% of the rate of every quintal.</li>
                <li>My dealers are the ones who support me because I am the one who gave the best product to another
                    dealer or coustomer so that they can get another regular customer or dealer which helps me to
                    get the best profit % out of the Business.</li>
            </ul>
        </div>
    </section>
    <section id="contact">
        <div class="box7">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
                <input type="submit" value="Submit">
            </form>
        </div>
    </section>
    </main>
    <footer>
        <div class="box8">
            <p>&copy; 2024 My Business. All rights reserved.</p>
        </div>
    </footer>
</body>

</html>
