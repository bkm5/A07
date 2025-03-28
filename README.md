# A07
body {
    font-family: Arial, sans-serif;
    margin-top: 0;
    margin-bottom: 0;
    margin-right: auto;
    margin-left: auto;
    padding: 0;
    border-width: 3px;
    border-color: #931420;
    width: 600px;
    background-color: white;
}

.container {
    width: 50%;
    margin: 20px auto;
    background-color: white;
    border: 3px solid maroon;
    position: relative;
}

header {
    background-color: #f4d47c;
    padding-top: 1.5em;
    padding-bottom: 2em;
    display: flex;
    align-items: center;
    border-bottom: 3px solid maroon;
    background: linear-gradient(40deg, 
    #f6bb73 0%, 
    #f6bb73 30%, 
    white 50%, 
    #f6bb73 80%, 
    #f6bb73 100%);
}

.header-content {
    display: flex;
    align-items: center;
}

.header-text1{
    color: maroon;
    margin: 0;
    font-size: 22px;
}

.header-text2{
    color: #555;
    font-size: 16px;
}

.logo {
    width: 60px;
    padding-left: 30px;
    padding-right: 30px;
}


h2 {
    color: #555;
    font-size: 16px;
}

.content {
    padding: 20px;
    padding-left: 30px;
    padding-right: 30px;
}

.mission, .ticket-packages, .guest-speakers {
    margin: 20px 0;
    padding-bottom: 10px;
}

h3 {
    color: maroon;
    font-size: 18px;
}

p {
    text-indent: 30px;
    line-height: 1.5;
}

blockquote {
    font-style: italic;
    margin-left: 30px;
    color: #333;
}

ul {
    list-style-type: disc;
}

.speaker-title{
    color: black;
    border: 3px solid maroon;
    border-radius: 5px;
    box-shadow: 5px 5px 10px grey;
    padding: 10px;
}

.speaker {
    margin-top: 15px;
}

.speaker img {
    width: 80px;
    height: 80px;
    display: block;
    margin-top: 5px;
}

a {
    color: #0645ad;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
}

footer {
    background-color: maroon;
    color: white;
    text-align: center;
    padding: 10px;
    padding-right: 40px;
    font-size: 14px;
    border-top: 6px solid maroon;
}
