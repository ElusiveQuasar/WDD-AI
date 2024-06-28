# WDD-AI
Summer Camp
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>20 Divs with Borders</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: white;
        }
        .banner {
            text-align: center;
            padding: 20px;
            background-color: #f0f0f0;
            border-bottom: 2px solid #ccc;
        }
        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .banner p {
            margin: 5px 0 0;
            font-size: 1.2em;
            color: #555;
        }
        .bordered-div {
            border: 1px solid black;
            margin: 5px;
            padding: 10px;
        }
        .image-500 {
            width: 500px;
            height: 500px;
        }
        .container {
            display: flex;
        }
        .left-column {
            flex: 60%;
        }
        .right-column {
            flex: 40%;
            padding-left: 20px;
        }
        .name-cards {
            display: flex;
            justify-content: space-between;
        }
        .name-card {
            border: 1px solid #ccc;
            padding: 10px;
            width: 22%;
            text-align: center;
        }
        .name-card img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="banner">
        <h1>Welcome to my Webpage</h1>
        <p>By: Elusive Quasar</p>
    </div>
    <div id="div1" class="bordered-div">
        <div class="container">
            <div class="left-column">
                <img src="https://www.asurams.edu/images/news/Student-Center-900x600.png" alt="Student Center" class="image-500">
            </div>
            <div class="right-column">
                <h2>AI is working</h2>
                <p>Summer 2024, WDD Using AI at Albany State University</p>
                <a href="https://www.asurams.edu">Visit Albany State University</a>
                <p>A webpage is a stack of &lt;div&gt;'s. Each &lt;div&gt; is a block that is designed separately. There are four styles for each &lt;div&gt;.</p>
                <ul>
                    <li>Brief room style: like Whitehouse webpage</li>
                    <li>Lowe's style that lists categories of products</li>
                    <li>Artist style that shows a very meaningful picture with some description</li>
                    <li>Documentation Style</li>
                </ul>
            </div>
        </div>
    </div>
    <div id="div2" class="bordered-div">
        <div class="name-cards">
            <div class="name-card">
                <img src="https://mobileimages.lowes.com/productimages/41df5bfb-5d89-4273-aa06-8ab48ad328a4/65113889.jpg?size=xl" alt="French Door Refrigerator">
                <p>French Door Refrigerator</p>
                <p>$1,399</p>
            </div>
            <div class="name-card">
                <img src="https://mobileimages.lowes.com/marketingimages/1ed97d3b-c4ea-412f-aab3-46831d4cee74/primer-when-to-use-porous-surfaces.png?im=Resize,width=351&fmt=webp" alt="Multi-Purpose Primer">
                <p>Multi-Purpose Primer</p>
                <p>$29.99</p>
            </div>
            <div class="name-card">
                <img src="path/to/image3.jpg" alt="Person 3">
                <p>Name: Person 3</p>
                <p>Title: Title 3</p>
                <p>Contact: contact3@example.com</p>
            </div>
            <div class="name-card">
                <img src="path/to/image4.jpg" alt="Person 4">
                <p>Name: Person 4</p>
                <p>Title: Title 4</p>
                <p>Contact: contact4@example.com</p>
            </div>
        </div>
    </div>
    <div id="div3" class="bordered-div">Div 3</div>
    <div id="div4" class="bordered-div">Div 4</div>
    <div id="div5" class="bordered-div">Div 5</div>
    <div id="div6" class="bordered-div">Div 6</div>
    <div id="div7" class="bordered-div">Div 7</div>
    <div id="div8" class="bordered-div">Div 8</div>
    <div id="div9" class="bordered-div">Div 9</div>
    <div id="div10" class="bordered-div">Div 10</div>
    <div id="div11" class="bordered-div">Div 11</div>
    <div id="div12" class="bordered-div">Div 12</div>
    <div id="div13" class="bordered-div">Div 13</div>
    <div id="div14" class="bordered-div">Div 14</div>
    <div id="div15" class="bordered-div">Div 15</div>
    <div id="div16" class="bordered-div">Div 16</div>
    <div id="div17" class="bordered-div">Div 17</div>
    <div id="div18" class="bordered-div">Div 18</div>
    <div id="div19" class="bordered-div">Div 19</div>
    <div id="div20" class="bordered-div">Div 20</div>
</body>
</html>