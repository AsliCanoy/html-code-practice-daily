<!DOCTYPE html>
<html lang="en"><meta charset=UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    
</head>
<body>
    <style>
        

body {
    background-color: #0d0d0d;
    color: #ffffff;
    font-family: 'Orbitron', sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: linear-gradient(90deg, #00d4ff, #0d00ff);
    padding: 20px;
    box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
    border-bottom: 3px solid cyan;
    animation: glow 1.5s infinite alternate;
}

@keyframes glow {
    from { box-shadow: 0 0 15px cyan; }
    to { box-shadow: 0 0 25px cyan; }
}

h1 {
    font-size: 2.5rem;
    text-transform: uppercase;
    letter-spacing: 4px;
    text-shadow: 0 0 10px cyan, 0 0 20px cyan;
}

.parent img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid cyan;
    box-shadow: 0 0 15px cyan;
    transition: transform 0.3s;
}

.parent img:hover {
    transform: scale(1.1);
}

.container1, .container2 {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;
}

.box1, .box2, .box3, .box4 {
    background: rgba(0, 0, 0, 0.8);
    border: 2px solid cyan;
    padding: 20px;
    margin: 10px;
    width: 45%;
    border-radius: 15px;
    box-shadow: 0 0 10px cyan;
    transition: transform 0.3s, box-shadow 0.3s;
}
.box2{
    font-size: x-large;
}

.box1:hover, .box2:hover, .box3:hover, .box4:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px cyan;
}

h2 {
    color: cyan;
    text-shadow: 0 0 5px cyan, 0 0 10px cyan;
}

footer {
    background: rgba(0, 0, 0, 0.9);
    padding: 20px;
    border-top: 3px solid cyan;
    box-shadow: 0 0 15px cyan;
}

.social-icons a {
    text-decoration: none;
    color: cyan;
    font-size: 1.2rem;
    margin: 0 15px;
    display: inline-block;
    transition: 0.3s;
}

.social-icons a:hover {
    color: #0d00ff;
    text-shadow: 0 0 10px cyan, 0 0 20px cyan;
    transform: scale(1.2);
}

    </style>
    

    
   <header>

        <h1><strong>Profile-Resume </strong></h1>
        
    
    <div class="parent">
        <img src="https://scontent.fceb8-1.fna.fbcdn.net/v/t39.30808-6/475153499_1308829673491297_6357466761851747358_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeG0GRP00x19Up4REaz2S6H58yvURShv5ffzK9RFKG_l98dl7IDigBOIlMRampRrBXlXUxAEs0Fg4u1lVTdIlZ09&_nc_ohc=MGG0Lm3T-00Q7kNvgEbHJOt&_nc_oc=Adlm7IaoftcG8c4eD8U4LJSkWlzM-L5bAG2-UE6rif-Eqy-gAMkn8BSWwVt03xdlDb4&_nc_zt=23&_nc_ht=scontent.fceb8-1.fna&_nc_gid=SGnNiW90IAt4Vda3rekKwQ&oh=00_AYHM0FoXoLrJhxzMFV-eXsI_6n9du6lUpWxeT3qAT5FDEg&oe=67E4A77C" alt="">
    </div>
   </header>
    <section class="container1">
        <div class="box1">
          <h2>Canoy, Alfred Asley R.</h2>
          <p><strong>Age:</strong> 21 Years old. </p>
          <p><strong>Birth date:</strong> July 18 2003 </p>
          <p><strong>Place of birth:</strong> Misamis Oriental, Cagayan De Oro. </p>
          <p><strong>Perm Address:</strong> Prk. Sipaway, San Carlos Tukuran Zamboanga Del Sur. </p>
            <h2>contact</h2>
          <p><strong>☎️Cellular no:</strong> 09910537155</p>  
          <p><strong>📱parent's number:</strong> 09773701574 </p>
            

        </div>
        <div class="box2">
            <h2>About Me</h2>
            <p>Hi, its a pleasure for you to visit my website let me introduce my self
            Since you already know my name i'll introduce my nickname instead, you can call me <em>aj,asli,alpe.</em>
            Im a BSIS-ACT student who currently studying at Zamboanga Del Sur Provincial Government College. (ZDS-PGC) Im a first year college student. </p>
        </div>
       

      </section>

      <section class="container2">
        <div class="box3">
            <h2>Educational Background</h2>
            <p><strong>Primary:</strong> Tukuran Sped Center  </p>
            <p><strong>Secondary:</strong> Tukuran Technical Vocational High School</p>
            <p><strong>Tertiary:</strong> Zamboanga Del Sur Provincial Government College.</p>
        </div>
        <div class="box4">
            <h2>Work experience</h2>
            <p><strong>Shell gasoline station:</strong> Pump boy</p>
            <p><strong>Shandys bakeshop:</strong> Baker's Assistant </p>
            <p><strong>B2D-Brunch2Dinner</strong>Service Crew-Cashier</p>
            
        </div>
      </section>









      <footer>
        <div class="social-icons">
            <a href="https://www.facebook.com/johnrebaja.canoy">🌐 facebook<i class="fab fa-facebook"></i></a>
            <a href="https://mail.google.com/mail/u/1/#inbox">Ⓜ️gmail<i class="fab fa-gmail"></i></a>
          </div>

      </footer>




</body></html>
