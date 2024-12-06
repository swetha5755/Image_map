# Ex04 Places Around Me
# Date:24.11.2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<!DOCTYPE html>
<html>
  <title>MAP OF INDIA</title>
  <style>
    img{
      height: 500px;
      width: 500px;
      border: 3px solid grey;
    }
    body{
      text-align: center;
      background-color: aliceblue;
    }
    h1{
      font-size: 24px;
      margin-top: 20px;
    }
  </style>
<body>
<map>
<img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-02 163827.png" usemap="#image-map" name="image-map">
<area target="_blank" alt="tamilnadu" title="tamilnadu" href="C:\Users\admin\HTML\munnar.html" coords="352,749,317,776,333,825,374,847,419,749" shape="poly">
<area target="_blank" alt="rajasthan" title="rajasthan" href="C:\Users\admin\HTML\rajasthan.html" coords="141,289,245,224,333,304,255,403,158,373" shape="poly"> 
<area target="_ blank" alt="gujarat" title="gujarat" href="C:\Users\admin\HTML\gujarat.html" coords="89,413,167,396,229,426,213,487,125,488" shape="poly">
<area target="_blank" alt="bhutan" title="bhutan" href="C: \Users\admin\HTML\bhutan.html" coords="665, 306,692,272, 745,286,757,310,707,312" shape="poly">
<area target="_blank" alt="megalaya" title="megalaya" href="C:\Users\admin\HTML\megalaya.html" coords="670,347,734,347,777,353,706,401,686,388" shape="poly">
</map> 
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<title>Image1</title>
</head>
<body>
	<header>
		<h1>Munnar</h1>
        <h2>where the clouds kiss the mountains, and the valleys whisper tales of the past</h2>
	</header>
	<main>
		<img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-04 190407.png" alt="andra pradesh">
		<p><h3><i>Munnar, a picturesque hill station in the Western Ghats of Kerala, India,
             is a haven for nature lovers, photographers, and adventure seekers. Located at an
              altitude of 1,600 meters above sea level, Munnar is a tranquil retreat from the hustle and
               bustle of city life. The region's scenic landscape is dominated by rolling hills, verdant tea
                plantations, and dense forests, creating a breathtakingly beautiful panorama that is sure to leave
                 visitors spellbound.
            As one explores Munnar, the sweet fragrance of tea wafts through the air, enticing visitors to stroll
             through the lush green tea plantations. The region is famous for its high-quality tea, and visitors can take
              a tour of the tea factories to learn about the production process and sample some of the local varieties. For
               adventure enthusiasts, Munnar offers a range of activities, including trekking, hiking, and rock climbing. The 
               Anamudi Peak, the highest point in South India, is a popular destination for trekkers, offering breathtaking views of the
                surrounding landscape.</i></h3></p>
	</main>
<style>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #f0f0f0;
	padding: 20px;
	text-align: center;
}

header h1 {
	margin: 0;
}

main {
	display: block;
	padding: 20px;
}

img {
	width: 50%;
	height: auto;
	margin: 20px 350px;
}

p {
	margin-bottom: 20px;
}
</style>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<title>Image1</title>
</head>
<body>
	<header>
		<h1> The Rann of Kutch </h1>
        <h2> A Surreal Landscape of White Salt and Blue Horizon </h2>
	</header>
	<main>
		<img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-03 090933.png" alt="andra pradesh">
		<p><h3><i>The Rann of Kutch, located in the western state of Gujarat,
             India, is a vast and breathtaking salt desert that stretches over 7,500 square kilometers.
              This unique landscape, created by the evaporation of seawater from the Arabian Sea, is a result
               of geological and climatic changes that have occurred over millions of years. The Rann of Kutch is a
                seasonal wonder, transforming into a vast expanse of water during the monsoon months and drying up to form
                 a crust of salt and minerals during the dry season. This ever-changing landscape is home to a diverse range of
                  flora and fauna, including the endangered Indian wild ass, and is a major stopover for migratory birds. The Rann of Kutch
                   is also famous for its cultural and historical significance, with the nearby town of Bhuj being a major center for traditional
                    crafts and textiles. Every year, the Rann of Kutch hosts the Rann Utsav, a vibrant festival that celebrates the region's unique
                     culture and natural beauty.</i></h3></p>
	</main>
<style>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #f0f0f0;
	padding: 20px;
	text-align: center;
}

header h1 {
	margin: 0;
}

main {
	display: block;
	padding: 20px;
}

img {
	width: 50%;
	height: auto;
	margin: 20px 350px;
}

p {
	margin-bottom: 20px;
}
</style>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<title>Image1</title>
</head>
<body>
	<header>
		<h1> Taktshang Palphug Monastery </h1>
        <h2> Tiger's Nest Monastery</h2>
	</header>
	<main>
		<img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-04 205047.png" alt="andra pradesh">
		<p><h3><i>Taktshang Palphug Monastery, also known as the Tiger's Nest Monastery, is a breathtakingly beautiful and sacred Buddhist site
             located in the Paro Valley of Bhutan. Perched precariously on a cliffside, 10,000 feet above sea level, this iconic monastery appears
              to be defying gravity, its stunning architecture blending seamlessly into the surrounding landscape. According to legend, the monastery
               was built in 1692 around the cave where Guru Rinpoche, a revered Buddhist master, meditated and introduced Buddhism to Bhutan. Today, 
               the monastery is a sacred pilgrimage site for Buddhists and a popular tourist destination,
            attracting visitors from around the world with its unique blend of natural beauty, history, and spiritual significance.</i></h3></p>
	</main>
<style>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #f0f0f0;
	padding: 20px;
	text-align: center;
}

header h1 {
	margin: 0;
}

main {
	display: block;
	padding: 20px;
}

img {
	width: 50%;
	height: auto;
	margin: 20px 350px;
}

p {
	margin-bottom: 20px;
}
</style>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<title>Image1</title>
</head>
<body>
	<header>
		<h1>Nohkalikai Falls</h1>
        <h2> a symphony of water and wonder, where nature's melody echoes through the misty veil, touching the heart and soul.</h2>
	</header>
	<main>
		<img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-04 210752.png" alt="andra pradesh">
		<p><h3><i>Nohkalikai Falls, located near Cherrapunji, one of the wettest places on Earth, is a breathtakingly 
            beautiful waterfall that is a testament to the natural splendor of Meghalaya. Plunging from a staggering height of over 1,100 feet,
             Nohkalikai Falls is one of the tallest waterfalls in India, and its sheer force and beauty leave visitors awestruck. The falls are
              surrounded by lush green forests, and the mist created by the falls creates a mystical atmosphere, adding to the falls' ethereal charm.
               According to local legend, the falls are named after a woman named Ka Likai, who jumped off the cliff in grief after her husband killed their daughter.
                Today, Nohkalikai Falls is a popular tourist destination, 
            attracting visitors from around the world with its unparalleled natural beauty and mystical charm.</i></h3></p>
	</main>
<style>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #f0f0f0;
	padding: 20px;
	text-align: center;
}

header h1 {
	margin: 0;
}

main {
	display: block;
	padding: 20px;
}

img {
	width: 50%;
	height: auto;
	margin: 20px 350px;
}

p {
	margin-bottom: 20px;
}
</style>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<title>Image1</title>
</head>
<body>
	<header>
		<h1> Chand Baori </h1>
        <h2>"A stairway to the past, Chand Baori's ancient beauty steps into eternity."</h2>
	</header>
	<main>
		<img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-04 204418.png" alt="andra pradesh">
		<p><h3><i>Chand Baori, located in the Abhaneri village of Dausa district in Rajasthan, is an ancient 
            architectural marvel that showcases the engineering and artistic skills of the region's ancestors. Built in the 8th 
            century AD, this 13-story stepwell is one of the deepest and largest in India, with 3,500 narrow steps leading down to the water level.
             The stepwell's intricate and ornate architecture features beautiful carvings and sculptures on the walls and pillars, depicting various
              mythological and royal scenes. Chand Baori is not only an impressive example of ancient Indian engineering but also a testament to the 
              region's rich cultural and artistic heritage. This ancient wonder has also gained international recognition, featuring in several films and 
            TV shows, and is a must-visit destination for anyone interested in history, architecture, and culture.</i></h3></p>
	</main>
<style>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #f0f0f0;
	padding: 20px;
	text-align: center;
}

header h1 {
	margin: 0;
}

main {
	display: block;
	padding: 20px;
}

img {
	width: 50%;
	height: auto;
	margin: 20px 350px;
}

p {
	margin-bottom: 20px;
}
</style>
</body>
</html>
```
# OUTPUT
![Screenshot 2024-12-06 222635](https://github.com/user-attachments/assets/e3e98d7e-f835-420d-bd54-b7421dd93b25)
![Screenshot 2024-12-06 222135](https://github.com/user-attachments/assets/19a18ecf-4959-4def-a8c8-9497fc469d30)
![Screenshot 2024-12-06 222203](https://github.com/user-attachments/assets/fe33e0c9-5469-4e94-9b89-79445c626bb2)
![Screenshot 2024-12-06 222231](https://github.com/user-attachments/assets/4c95dd16-3c10-4a52-9742-823276725bba)
![Screenshot 2024-12-06 222300](https://github.com/user-attachments/assets/2f7d8e15-415c-42ea-89f2-b0bf1c4e91c4)
![Screenshot 2024-12-06 222324](https://github.com/user-attachments/assets/1e17e5e1-2130-4e24-a605-4142c828fbcf)
# RESULT
The program for implementing image maps using HTML is executed successfully.
