# HTML-PROJECT
HTML TEMPLATE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
    background-color:#8db0db;
}
h2,h6{
    text-align: center;
}
img{
    height: 400px;
}
h3,h5{
    text-align: right;
    font-style: italic;
}
#image {
    margin-left: 750px;
    margin-bottom: 20px;
}
#logo{
     img{
        height: 100px;
     }
    margin-left: 1200px;
}
h2{
    background-color: #da5a26;
}
#last{
    height: 40px;
}
pre,#main,h4{
    background-color:#48699c;
    width: 500px;
}
    </style>
    
</head>
<body>
    <div id="logo">
        <img src="https://beta-cdn.contractorforeman.net/0000_sandbox/35647/estimates/large/logo.png" id="1"/>
    </div>
    <header>
        <h2>PROJECT NAME</h2>
    </header>
    <h6>ESTIMATE_TITLE</h6>
    <p>Date:ESTIMATE_DATE</p>
    <div id="image">
    <img src="https://wallpaperboat.com/wp-content/uploads/2020/12/07/63377/construction-02-920x518.jpg"alt="image"/>
    </div>
    <main>
    <div id="main">
    <h4> Presented TO </h4>
    <pre>COUSTEMER_FIRST    CUSTOMER_LAST</pre>
     <pre>COUSTEMER_STREET</pre>
     <pre id="last">COUSTEMER_CITY  COUSTEMER_STATE  COUSTEMER_ZIP</pre>
    </div>
    </main>
    <br/>
    <footer>
    <h3>Presented BY</h3>
    <h5 style="color:red">ARYAN SHAH</h5>
    </footer>
</body>
</html>
