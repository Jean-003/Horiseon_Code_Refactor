# Title 

Horiseon Code Refactor Project

## Objective 

This project utilised HTML and CSS to to refactor existing code for a webpage to make it more accessible by meeting a certain set of standards

### The URL of the deployed page

https://jean-003.github.io/Horiseon_Code_Refactor/

### The URL of the GitHub repository that contains the code:

https://github.com/Jean-003/Horiseon_Code_Refactor

## Usage

To view the alternative text for all the images and icons on this webpage, the user should:

Open the Chrome DevTools by pressing Control+Shift+I (Windows) or Command+Option+I (macOS). This opens a pane to the side of the webpage or below the webapage in the browser. Next, the user should look for the HTML tag that says 'alt= "_Description_" ' The text that can be seen in the HTML pane represented here by _Description_ is the alt text.

**Images displaying the website in the browser**

1.
![Screenshot 2024-02-28 104851](https://github.com/Jean-003/Horiseon_Code_Refactor/assets/152238337/0c50f5ba-e812-4e44-ae5d-e63be16b50ad)






2.
![Screenshot 2024-02-28 105043](https://github.com/Jean-003/Horiseon_Code_Refactor/assets/152238337/719292dd-4eb1-4ebe-b61b-f9b3c344ba74)






3.
![Screenshot 2024-02-28 104918](https://github.com/Jean-003/Horiseon_Code_Refactor/assets/152238337/94465d37-4b84-4bc5-868c-a94218268769)



## Licences 

 None

## References 

The following starter code was supplied by edX:

### HTML file:

<!-- <!DOCTYPE html>
<html lang="en-gb">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>

<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="hero"></div>
    <div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </div>
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png"></img>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    <div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </div>
</body>

</html> -->

### CSS file:

<!-- * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: #d9dcd6;
}

.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

.header h1 {
    display: inline-block;
    font-size: 48px;
}

.header h1 .seo {
    color: #d9dcd6;
}

.header div {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

.header div ul {
    list-style-type: none;
}

.header div ul li {
    display: inline-block;
    margin-left: 25px;
}

a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}

.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}

.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

.footer h2 {
    font-size: 20px;
} -->










