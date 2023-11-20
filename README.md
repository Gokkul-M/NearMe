![Screenshot 2023-11-20 210019](https://github.com/Gokkul-M/NearMe/assets/144870543/01217cef-e7e8-40c6-a039-9d8c5d30cb96)# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

```
map.html:
<html>
<head>
<title>MY CITY</title>
<style type="text/css">
    img {
      width:100%;
    }
    </style>    
</head>
<body bgcolor="#FF69B4">
<h1 align="center">
<font color="#00FFFF"><b>Madurai</b></font>
</h1>
<h3 align="center">
<font color="cyan"><b>GOKKUL M (23014201)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="881" width="1920">
<map name="MyCity">
<area shape="rect" coords="1016,397,664,518"  href="Temple.html" title="Meenakshi Amman Temple">
<area shape="rect" coords="1123,521,820,622"  href="Palace.html" title="Nayyakar Palace">
<area shape="rect" coords="1130,682,1467,546"  href="Holypond.html" title="Mariyamman Teppakulam">
<area shape="rect" coords="1398,308,1023,469"  href="museum.html" title="Gandhi museum">
<area shape="poly" coords="239,146,264,132,288,152,310,173,357,195,400,207,444,215,486,229,528,246,562,258,589,268,620,281,654,286,705,317,733,327,752,337,779,354,813,369,781,386,720,366,679,344,617,315,550,276,486,254,467,259,445,256,417,247,391,247,350,220,334,207,313,207,278,190"  href="River.html" title="Vaigai River">
</map>
</center>
</body>
</html>

```
```
Holypond.html:
<html>
    <head>
        <title>HolyPond</title>
    </head>
    <body bgcolor="coral">
        <h1 align="center">
            <font color="yellow"><b>Vandiyur mariyamman kovil Teppakulam</b></font>
        </h1>
        <h2 align="center">
            <font color="lavender"><b>Tourist Place</b></font>
        </h2>
        <hr size="3" color="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="yellow">
                Vandiyur Mariamman Teppakulam, is a large temple tank located in the Vandiyur village of Madurai, Tamil Nadu, India. 
                It is one of the prominent teppakulams (tank with a mandapam or pavilion in the center) in the region and holds cultural, religious, and historical significance. 
            </font>
        </p>
        </body>
</html>
```
```
museum.html:
<html>
    <head>
        <title>Museum</title>
    </head>
    <body bgcolor="darkblue">
        <h1 align="center">
            <font color="lavender"><b>Gandhi Museum</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>Tourist Place</b></font>
        </h2>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                The Gandhi Museum, dedicated to the life and teachings of Mahatma Gandhi, is a place of historical and cultural significance. Typically located in various parts of the world, these museums aim to preserve and showcase the legacy of one of the most influential figures in modern history.
                The museum often begins with an introduction to Gandhi's early life, detailing his upbringing, education, and formative experiences. Exhibits may include photographs, personal artifacts, and documents that provide insight into his journey. Visitors can trace Gandhi's evolution from a young lawyer in South Africa to the leader of India's nonviolent independence movement.
                One key aspect of the museum is its emphasis on Gandhi's philosophy of nonviolence (Ahimsa) and his principles of truth, simplicity, and self-reliance. Exhibits may feature quotes, writings, and audiovisual presentations that highlight these principles, offering a deeper understanding of his ideologies.
            </font>
        </p>
        </body>
</html>
```
```
palace.html:
<html>
    <head>
        <title>Palace</title>
    </head>
    <body bgcolor="#101820" align="center">
        <h1 align="center">
            <font color="yellow"><b>Nayyakar Palace</b></font>
        </h1>
        <h2 align="center">
            <font color="blu green"><b>TOURIST Palace</b></font>
        </h2>
        <hr size="3" color="DarkOrchid">
        <p align="justify">
            <font face="Times New Roman" size="6" color="yellow">
                The 'Temple City' not only holds the history and pride of holding various temples, but also stands atop in having a national monument. "Thirumalai Nayakar Mahal", a palace built by the king Thirumalai Nayakar with the help of an Italian architect, in the 17th century. The amalgamation of the Dravidian and Islamic architecture style resulted in the erection of this glorious majestic palace. This site is famous for its pillars, which stands at a height of 82 feet and at a width of 19 feet. The palace has an arcaded octagon covered by a dome of 60-70 feet high, which is held up and supported by stone ribs. What arouses our curiosity is how they built the palace? The palace was built using bricks, stucco and the white egg of an yolk. It really bristles when pondering of how many eggs were used for building this palace. The palace was built in a way that it was comprised into: Sorga Vilasam and Ranga Vilasa, but the saddest part is that only the former part of the palace still remains. The palace, then, was so huge and extended up to the North Masi Street with the combination of both Sorga Vilasam and Ranga Vilasam.
                The grandson of Thirumalai Nayakar, Chokkanadha Nayak, wasted and demolished the palace by transporting the things and removed most of the jewels when he shifted his Nayak dynasty to Trichy. The Governor of Madras (1886), Lord Napier, took an initiative and renovated the palace as much as he could. The Palace was erected 4 times bigger than what you see now. This palace is meant for its beautiful and minute architecture perfectly sculpted in the ceilings. The interior of the palace attracts the tourists with those big, big pillars constructed in the palace. Many film shoots have been shot, especially the 'Kannalane' song from the movie Bombay was shot here because of the the attraction given by those pillars. The government now decorated the entry of the palace with a garden that adds scenic beauty to the palace. There is a full sized statue of Thirumalai Nayakar inside the palace.
            </font>
        </p>
        </body>
</html>
```
```
river.html:
<html>
    <head>
        <title>River</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="#317773"><b>Vaigai river</b></font>
        </h1>
        <h2 align="center">
            <font color="#FF69B4"><b>Tourist Place</b></font>
        </h2>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Times New Roman" size="6" color="#317773">
                The Vaigai River is a prominent river in the Indian state of Tamil Nadu, and it holds cultural and historical significance, particularly in the city of Madurai. Here's a description of the Vaigai River in the context of Madurai:
                The Vaigai River gracefully meanders through the ancient city of Madurai, adding to the city's charm and providing a lifeline to the region. Originating in the Varusanadu Hills, the river flows eastward, eventually reaching the Vaigai Dam.
                In Madurai, the Vaigai River is not just a geographical feature but a cultural and historical icon. The river has been a witness to the city's rich history, with its banks dotted by temples, ghats, and vibrant local life. The riverbanks often serve as a place for religious ceremonies, rituals, and social gatherings.
            </font>
        </p>
        </body>
</html>
```
```
temple.html:
<html>
    <head>
        <title>TEMPLE</title>
    </head>
    <body bgcolor="#CCF381">
        <h1 align="center">
            <font color="#4831D4"><b>Meenakshi amman kovil</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>Thiruttani - My Home Town</b></font>
        </h2>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Times New Roman" size="6" color="#4831D4">
                Meenakshi Amman Temple, commonly known as the <b>Meenakshi Temple</b>, is a historic Hindu temple located in the city of Madurai in the Indian state of Tamil Nadu. The temple is dedicated to Goddess Meenakshi, who is considered a form of the Goddess Parvati, and her consort Lord Sundareswarar, a form of Lord Shiva.
                <br>
                Here are some key features and aspects of the Meenakshi Amman Temple:
                <h3><b>Architecture:</b></h3> The temple is renowned for its stunning Dravidian architecture, characterized by towering gopurams (ornate entrance towers), intricate carvings, and vibrant paintings. The temple complex covers a vast area and is surrounded by a high wall.
                <h3><b>Gopurams:</b></h3> The temple has 14 gopurams, with the tallest one standing at the southern entrance, reaching a height of about 52 meters. Each gopuram is adorned with colorful sculptures and intricate designs depicting various mythological stories and deities.
                <h3><b>Main Shrines:</b></h3> primary shrines within the temple are dedicated to Meenakshi and Sundareswarar. The Meenakshi shrine houses an idol of the goddess with a green complexion, while the Sundareswarar shrine features a lingam (symbol of Lord Shiva).
                <h3><b>Hall of Thousand Pillars:</b></h3> temple complex includes the "Hall of Thousand Pillars" or "Ayiram Kaal Mandapam," known for its numerous intricately carved pillars. Each pillar is said to emit different musical sounds when struck.
                <h3><b>Tank and Golden Lotus Pond:</b></h3> The temple complex also includes a sacred tank called "Porthamarai Kulam" or the Golden Lotus Pond. Pilgrims often take ritual baths in this tank.
                <h3><b>Festivals:</b></h3> The Meenakshi Amman Temple is a center for various festivals, with the most prominent being the "Meenakshi Thirukalyanam" or the divine marriage of Meenakshi and Sundareswarar. This grand celebration attracts a large number of devotees and tourists.
                <h3><b>Significance:</b></h3> The temple holds immense cultural and religious significance in South India and is considered one of the holiest sites dedicated to Goddess Meenakshi. It attracts millions of pilgrims and visitors each year.

            </font>
        </p>
        </body>
</html>
```
## OUTPUT
![Screenshot 2023-11-20 211243](https://github.com/Gokkul-M/NearMe/assets/144870543/3a114ab5-3872-43ea-84ce-f1c4d6eb3173)
![Screenshot 2023-11-20 210019](https://github.com/Gokkul-M/NearMe/assets/144870543/f5fa2efc-8e60-49bc-8ba5-3890d27c7319)
![Screenshot 2023-11-20 210030](https://github.com/Gokkul-M/NearMe/assets/144870543/1a4857b8-1859-41b2-b484-53e422f0da35)
![Screenshot 2023-11-20 210040](https://github.com/Gokkul-M/NearMe/assets/144870543/e08052de-316e-4ff1-9913-761f0f017fe7)
![Screenshot 2023-11-20 210049](https://github.com/Gokkul-M/NearMe/assets/144870543/f6bc0a00-7587-4e6b-be5e-65b1990d1523)
![Screenshot 2023-11-20 210958](https://github.com/Gokkul-M/NearMe/assets/144870543/7d5b6b79-68fa-4938-a409-f066ee46173b)

## RESULT
The program for implementing image maps using HTML is executed successfully.
