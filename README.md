# Ex04 Places Around Me
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

## EX 4.HTML
```
<!DOCTYPE html>
<HTML>
    <HEAD>
        <TITLE>My City</TITLE>
    </HEAD>
    <BODY>
        <h1 align="center" style="font-size: xx-large;">
            <font color="black"><b>Tirunelveli</b>
            
            </font>

        </h1>
        <h3 align="center"  style="font-size: larger;">
            <font color="black"><b>INDRAJA S (212222043003)</b></font>
        </h3>

        <CENTER>
            <style>
                .container {
                  
                    display: flex;
  justify-content: space-between;
                   

                }

                .container img {
                    width: 500px;
                    height: auto;
                    padding: 10px;
                    padding-left: 150px;
                    padding-right: 150px;
                
                }
            </style>
            

            <div class="container">
                <img src="http://www.tirunelveli.com/images/map.jpg" alt="image 1">
    
                <img src="C:\Users\Admin\Desktop\tirunelveli\tirunelveli junction.jpg" alt="image 2">
            </div>

            <map name="container">
                <area title="Kalakkadu Sanctuary" href="kalakkadu.html" coords="652,320,880,398" shape="rect">
                <area title="Manimuthar Waterfalls" href="manimuthar.html" coords="452,600,208" shape="circle">
                <area title="Kattabomman Memorial Fort" href="kattabomman.html" coords="819,400,981,881" shape="rect">
                <area title="Nellaiappar Temple" href="nellaiappar.html" coords="705,315,935,337,710,414,637,317" shape="poly">
                <area title="Iruttu Kadai Halwa" href="halwa.html" coords="422,481,119" shape="circle">
            </map>

        </CENTER>
        <p><h4 align="center" style="font-size: large;" style="font-family: copperplate gothic;">
            <font color="black">
                <font family="copperplate"
                <font size="20px">

                
            </font>
Tirunelveli is a city in Tamil Nadu state of southern India.Tirunelveli district is surrounded by Virudhunagar district to the north, Tuticorin district to the east, the Indian Ocean to the south, Kanyakumari district to the southwest,and Kerala state to the west.The famous Courtallam waterfalls are located in Tirunelveli district.         
Kazhugumalai, Sankarankovil, Tenkasi, Papanasam are interesting tourist places in Tirunelveli. Our Tirunelveli map makes your journey easier.           
Tirunelveli, also known as Nellai and historically (during British rule) as Tinnevelly, is a major city in the Indian state of Tamil Nadu. It is the administrative headquarters of the Tirunelveli District.It is the fourth-largest municipal corporation in the state after Chennai, Coimbatore, and Madurai.
The city is considered one of the oldest in the Indian Subcontinent, dating back around 3,000 years. It is located on the west bank of the Thamirabarani River. The name Tirunelveli has been composed of the three Tamil words i.e. ‘Thiru – Nel – Veli’ meaning Sacred Paddy Hedge.
Tirunelveli has a geographical area of 3876.06 sq. km, in the Southeastern portion of Tamil Nadu and is triangular in shape. It lies between 8°.14’ and 9°.07’ of the Northern latitude and 77°.17’ and 77°.97’ of Eastern longitude.
The city is well-connected by road and rail with the rest of Tamil Nadu and India. The nearest domestic airport is Thoothukudi Airport. The nearest international airports are Madurai International Airport and Thiruvananthapuram International Airport. The nearest seaport is Thoothukudi Port.
Industries in Tirunelveli include administrative services, agricultural trading, tourism, banking, agricultural machinery, information technology, and educational services. The city is also known as the Oxford of South India due to the presence of many schools and colleges.
        </h4></p>
    </BODY>
</HTML>
```

## KALAKKADU.HTML
```
<HTML>
    <HEAD>
        <TITLE>Kalakkadu Sanctuary</TITLE>
    </HEAD>
    <body bgcolor="lightblue">
        <h1 align="center" style="font-size: xx-large;">
            
            <font color="black">Tirunelveli</font>
        </h1>
        
        <h3 align="center" style="font-size: larger;">
            <font color="yellow">Kalakkadu Sanctuary</font>
        </h3>
        <hr color="yellow" align="center">
        <br>
        <style>
            .kalakkadu {
              
                display: flex;
                justify-content: center;
            
            }

            .kalakkadu img {
                width: 500px;
                height: auto;
                padding-left: 150px;
                padding-right:150px;
            
            }
        </style>
        

        <div class="kalakkadu">
            <img src="C:\Users\Admin\Desktop\tirunelveli\kalakkadu sanctuary.jpeg" alt="sanctuary">
        </div>
        <p><h4>
            The Kalakkadu Sanctuary, also known as the Kalakad Mundanthurai Tiger Reserve (KMTR), is located in the Tirunelveli and Kanyakumari Districts of Tamil Nadu. It’s one of the few spots in all of South India where tigers are safely protected from poachers.

Established in 1988, the sanctuary is nestled in the serene shades of the majestic Western Ghats. The sanctuary spans an area of 223 square kilometers at the foothills of the Western Ghats and the adjoining areas.

The sanctuary is home to a diverse range of flora and fauna. The vegetation gradually changes from dry thorn forest to dry deciduous. This region is a tropical wet evergreen forest, making it a haven for various species of wildlife.

In addition to tigers, the sanctuary is home to several other animals such as the lion-tailed macaque, Nilgiri langur, Nilgiri tahr, sambar, panther, wild dog, and pangolin. These animals often make appearances for visitors’ viewing pleasure.

Despite being a tiger sanctuary, it’s worth noting that access can be unpredictable and there are no organized sightseeing facilities. However, the sanctuary is a popular tourist destination and offers a unique experience for nature and wildlife enthusiasts
        </h4></p>
    </body>
</HTML>
```

## HALWA.HTML
```
<HTML>
    <HEAD>
        <TITLE>Iruttu Kadai Halwa</TITLE>
    </HEAD>
    <body bgcolor="orange">
        <h1 align="center" style="font-size: xx-large;">
            
            <font color="black">Tirunelveli</font>
        </h1>
        
        <h3 align="center" style="font-size: larger;">
            <font color="lightgreen">Iruttu Kadai Halwa</font>
        </h3>
        <hr color="lightgreen" align="center">
        <br>
        <style>
            .shop {
              
                display: flex;
                justify-content: center;
            
            }

            .shop img {
                width: 500px;
                height: auto;
                padding-left: 150px;
                padding-right:150px;
            
            }
        </style>
    
        <div class="shop">
            <img src="C:\Users\Admin\Desktop\tirunelveli\halwa image.jpg" alt="halwa">
        </div>


        <p><h4 style="font-size: large;" style="font-family: copperplate gothic;">
            Tirunelveli is famous for its unique sweet, the Tirunelveli Halwa. There are several shops in Tirunelveli that sell this delicious sweet, but a few stand out for their history and quality.

One such shop is the Iruttukadai Halwa Shop. This shop was established by a family from Rajasthan about a century ago and is still run by the same family. Despite not having any name board or branding outside their shop, they are world-renowned for their mouth-melting high-quality Halwa. The shop got its name from the dimly lit interiors.
When the shop was started a century ago, it used to operate by candlelight, and the name “Iruttukadai” translates to “Dark Shop” in Tamil.

Another popular shop is TirunelveliHalwa.Net, which offers an online ordering and delivery platform that serves 24 hours a day. They aim to ensure that those who love Tirunelveli Halwa never miss out on its taste.

There are also other online platforms like HalwaHouse and Halwa2Home that offer authentic Tirunelveli Halwa and deliver it directly from traditional shops in Tirunelveli to your doorstep.

These shops have managed to maintain the traditional taste of Tirunelveli Halwa, making it a must-try delicacy for anyone visiting the city or even ordering online. The Halwa is usually served hot and is known to melt in your mouth, offering a unique and unforgettable experience. 
        </h4></p>
    </body>
</HTML>
```

## KATTABOMMAN.HTML
```
<HTML>
    <HEAD>
        <TITLE>Kattabomman Memorial Fort</TITLE>
    </HEAD>
    <body bgcolor="violet">
        <h1 align="center" style="font-size: xx-large;">
            
            <font color="black">Tirunelveli</font>
        </h1>
        
        <h3 align="center" style="font-size: larger;">
            <font color="dark purple">Kattabomman Memorial Fort</font>
        </h3>
        <hr color="maroon" align="center">
        <br>

        <style>
            .kattabomman {
              
                display: flex;
                justify-content: center;
            
            }

            .kattabomman img {
                width: 500px;
                height: auto;
                padding-left: 150px;
                padding-right:150px;
            
            }
        </style>
        

        <div class="kattabomman">
            <img src="C:\Users\Admin\Desktop\tirunelveli\kattabomman fort.jpg" alt="Fort">
        </div>
        <p><h4>
    
            The Kattabomman Memorial Fort, also known as the Panchalamkurichi Fort, is a historic attraction located in Salikulam, Tamil Nadu. This fort was constructed in the 18th century by the Panchalamkurichi King Veera Pandya Kattabomman, who was a Palay-karra of the Madurai Nayak kingdom.
            
            The fort is a testament to the valour of Veerapandiya Kattabomman, a legendary Tamil warrior who led a heroic struggle against the British. The fort was built to withstand the might of invading forces, and its sturdy walls and secret underground passages stand as a testament to Kattabomman’s unwavering courage in the face of adversity.
            
            The present fort was built atop the remnants of the original structure that served as the military base for Kattabomman’s rebellion. Today, the Kattabomman Memorial Fort stands as a living memorial to the heroic spirit of Kattabomman and his compatriots, a testament to their unbreakable will to fight for the freedom of their people.
            
            The fort has been transformed into a museum, showcasing an array of artefacts that offer a glimpse into the life and times of this great man. As you wander through the museum’s labyrinthine corridors, you will be surrounded by a kaleidoscope of sights and sounds: intricate paintings that capture the essence of Kattabomman’s life, awe-inspiring photographs that evoke the spirit of the man himself, and a treasure trove of artefacts that stand as a testament to his greatness.
            
            The fort is a reminder that the struggle for independence and justice is a journey that continues to this day, a journey that demands the courage and bravery of those who came before us. As you stand within the walls of the fort, gazing out at the breathtakingly beautiful landscape that surrounds it, an overwhelming sense of awe and wonder will hold you captive
        </h4></p>
    </body>
</HTML>
```

## MANIMUTHAR.HTML
```
<HTML>
    <HEAD>
        <TITLE>Manimuthar Dam</TITLE>
    </HEAD>
    <body bgcolor="orange">
        <h1 align="center" style="font-size: xx-large;">
            
            <font color="black">Tirunelveli</font>
        </h1>
        
        <h3 align="center" style="font-size: larger;">
            <font color="cyan">Manimuthar Dam</font>
        </h3>
        <hr color="cyan" align="center">
        <br>

        <style>
            .manimuthar {
              
                display: flex;
                justify-content: center;
            
            }

            .manimuthar img {
                width: 500px;
                height: auto;
                padding-left: 150px;
                padding-right:150px;
            
            }
        </style>
        

        <div class="manimuthar">
            <img src="C:\Users\Admin\Desktop\tirunelveli\dam.jpeg" alt="Dam">
        </div>
        <p><h4>
            opilot
The Manimuthar Dam is an impressive engineering marvel located in Manimutharu, about 50.8 kilometers away from Tirunelveli in Tamil Nadu, India. It is the largest reservoir in the Tirunelveli district.

The dam was built in 1958 near Singampatti and Kallidaikurichi by the then Tamil Nadu Chief Minister K. Kamaraj, and K T Kosalram MP. The primary purpose of the dam was to prevent rainwater from mixing with the Bay of Bengal during the rainy season and to use it for irrigation purposes.

The dam is a gravity dam with a height of 118 feet (36 meters) and a foundation height of 150 feet (46 meters). It has a total length of 9,268 feet (2,825 meters) and features 7 chute spillways1. The dam’s total capacity is 5.51 × 10^9 cubic feet (126,492 acre-feet), making it a significant source of water for the region.

The dam is situated at the foothills of the scenic Podhigai Hills. It was built across the Manimuthar River just three kilometers above its confluence with the Thamirabarani River. The river Manimuthar is the major tributary of the Thamirabarani.

The dam irrigates around 65,000 acres of areas in the northern part of the Nanguneri Taluk and Thisayanvilai and southern Veeravanallur, Karispalpatti, which are not irrigated by Pachaiyaaru in the Tirunelveli district. The downstream joins the River Thamirabarani in Kallidaikurichi after 6 km of its journey.

The Manimuthar Dam is not just a significant water resource but also a popular tourist spot. It offers a beautiful garden and peaceful atmosphere, making it an ideal picnic spot3. Boating in this picturesque dam is one of the most memorable things to do in Tirunelveli
        </h4></p>
    </body>
</HTML>
```

## NELLAIAPPAR.HTML
```
<HTML>
    <HEAD>
        <TITLE>Arulmigu Nellaiappar Temple</TITLE>
    </HEAD>
    <body bgcolor="red">
        <h1 align="center" style="font-size: xx-large;">
            
            <font color="black">Tirunelveli</font>
        </h1>
        
        <h3 align="center" style="font-size: larger;">
            <font color="lightgreen">Nellaiappar Temple</font>
        </h3>
        <hr color="lightgreen" align="center">
        <br>

        <style>
            .temple {
              
                display: flex;
                justify-content: center;
            
            }

            .temple img {
                width: 500px;
                height: auto;
                padding-left: 150px;
                padding-right:150px;
            
            }
        </style>
        

        <div class="temple">
            <img src="C:\Users\Admin\Desktop\tirunelveli\nellaiappar temple.jpg" alt="Nellai">
        </div>


        <p><h4>
            The Nellaiappar Temple, also known as the Sri Kasi Viswanathar Temple, is a significant Hindu temple located in Tirunelveli, a city in the South Indian state of Tamil Nadu. The temple is dedicated to the deity Shiva, who is worshipped as Nellaiappar (also called Venuvananathar) represented by the lingam, and his consort Parvati is depicted as Kanthimathi Amman.

The temple is believed to have been built by the Pandyas, while the present masonry structure was added by Cholas, Pallavas, Cheras, and Madurai Nayaks. The temple complex covers an area of 5.9 hectares (14.5 acres) and all its shrines are enclosed with concentric rectangular walls.

The temple is located on the northern banks of the Thamirabarani River in Tirunelveli district. The presiding deity is revered in the 7th century Tamil Saiva canonical work, the Tevaram, written by Tamil saint poets known as the nayanmars and classified as Paadal Petra Sthalam.

The temple has a number of shrines, with those of Swamy Nellaiappar and his consort Sri Kanthimathi Ambal being the most prominent. The temple has six rituals at various times from 6:00 a.m. to 9:00 p.m., and six yearly festivals on its calendar. The Brahmotsavam festival during the Tamil month of Aani (June–July) is the most prominent festival celebrated in the temple.

In modern times, the temple is maintained and administered by the Hindu Religious and Charitable Endowments Department of the Government of Tamil Nadu.
        </h4></p>
    </body>
</HTML>
```






## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
