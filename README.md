# Ex04 Places Around Me
## Date : 21/10/23
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
# index.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="Map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Chennai Central" title="Chennai Central" href="/static/central/central.html" coords="962,331,1127,450" shape="rect">
        <area target="_blank" alt="Chennai Egmore " title="Chennai Egmore " href="static/egmore/egmore.html" coords="87,666,263,723" shape="rect">
        <area target="_blank" alt="Rajiv Gandhi Govt Hospital" title="Rajiv Gandhi Govt Hospital" href="/static/hospital/hospital.html coords="1031,487,1192,567" shape="rect">
        <area target="_blank" alt="Fort St. George Museum" title="Fort St. George Museum" href="/static/fort/fort.html" coords="1444,495,1647,597" shape="rect">
        <area target="_blank" alt="Nehru Stadium" title="Nehru Stadium" href="/static/nehru/nehru.html" coords="667,229,809,360" shape="rect">
    </map>
</body>
</html>
    
```
# nehru.html
```
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Nehru Stadium</title>
   <style>
      *{
         margin: 0;
         padding: 0;
      }
      div{
         display: flex;
         flex-direction: column;
         /* justify-content: center; */
         height: 100vh;
         align-items: center;
         background-color: cyan;
      }
      .image{
        height: 200px;
      }
   </style>
</head>
<body>
   <div>
      <img src="nehru.jpg" alt="Nehru Stadium" class="image"/>
      <h1>Jawaharlal Nehru Stadium (Chennai)</h1>
      <p class="bio">The stadium was built on the area where the old Madras Zoo was located before it was shifted to its present location in at Vandalur.[4] It was known as the Corporation stadium until the 1980s and used to witness houseful audience for even the city league matches. When C. R. Viswanathan, then the Secretary of the Tamil Nadu Football Association, was keen on bringing the Nehru Cup international football tournament to Chennai, a stadium of international standard was required. He approached the then Chief Minister J Jayalalithaa with a plan to convert the old Corporation stadium into a brand-new ultra-modern facility.[5] The Chief Minister soon gave her approval[6] and the new stadium was built in 1993, within a span of 234 days, at a cost of ₹440 million (US$5.5 million).[2] In January 1993, the competition was conducted successfully in the new facility that was acknowledged to be arguably the best in the country also doubling up as a track and field venue.[6] In 2012, the Government of Tamil Nadu renovated the indoor stadium at a cost of ₹120 million (US$1.5 million) with a new skating rink.[7] In 2013, Government of Tamil Nadu upgraded the synthetic athletics track, football turf, floodlights and upgrading added a warm-up track north of the stadium at a cost of ₹331 million (US$4.1 million)</p>
   </div>
</body>
</html>

```
# central.html
```
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Central</title>
   <style>
      *{
         margin: 0;
         padding: 0;
      }
      div{
         display: flex;
         flex-direction: column;
         /* justify-content: center; */
         height: 100vh;
         align-items: center;
         background-color: cyan;
      }
      .image{
        height: 200px;
      }
   </style>
</head>
<body>
   <div>
      <img src="central.jpg" alt="central" class="image"/>
      <h1>Chennai Central</h1>
      <p class="bio">Chennai Central, officially Puratchi Thalaivar Dr. M.G. Ramachandran Central Railway Station, and formerly known as Madras Central (station code: MAS), is the main railway terminus in the city of Chennai, Tamil Nadu, India. It is the busiest railway station in South India and one of the most important hubs in the country. It is connected to Moore Market Complex railway station, Chennai Central metro station, Chennai Park railway station, and Chennai Park Town railway station. It is about 1.8 km (1.1 mi) from the Chennai Egmore railway station. The terminus connects the city to northern India, including Kolkata, Mumbai, and New Delhi, and all the different parts of India.

         The century-old building of the railway station, designed by architect George Harding, is one of the most prominent landmarks in Chennai.[4] The station is also a main hub for the Chennai Suburban Railway system. It lies adjacent to the current headquarters of the Southern Railway and the Ripon Building. During the British Raj, the station served as the gateway to South India, and the station is still used as a landmark for the city and the state.
         
         The station was renamed twice: first to reflect the name change of the city from Madras to Chennai in 1998, it was renamed from Madras Central to Chennai Central, and then to honor the AIADMK founder and the former chief minister of Tamil Nadu M. G. Ramachandran, it was renamed as Puratchi Thalaivar Dr. M.G. Ramachandran Central Railway Station on 5 April 2019.[5]
         
         About 550,000 passengers use the terminus every day, making it the busiest railway station in South India.[6] Along with Chennai Egmore and Coimbatore Junction, the Puratchi Thalaivar Dr. M.G. Ramachandran Central is among the most profitable stations of the Southern Railway.[7] As per a report published in 2007 by the Indian Railways, Puratchi Thalaivar Dr. M.G. Ramachandran Central and Secunderabad Junction were awarded 183 points out of a maximum of 300 for cleanliness, the highest in the country.</p>
   </div>
</body>
</html>
```
# fort.html
```
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Fort St. George Museum</title>
   <style>
      *{
         margin: 0;
         padding: 0;
      }
      div{
         display: flex;
         flex-direction: column;
         /* justify-content: center; */
         height: 100vh;
         align-items: center;
         background-color: cyan;
      }
      .image{
        height: 200px;
      }
   </style>
</head>
<body>
   <div>
      <img src="fort.jpg" alt="Fort St. George Museum" class="image"/>
      <h1>Fort St. George Museum</h1>
      <p class="bio">The East India Company (EIC), which had entered India around 1600 for trading activities, had begun licensed trading at Surat, which was its initial bastion. However, to secure its trade lines and commercial interests in the spice trade, it felt the necessity of a port closer to the Malaccan Straits, and succeeded in purchasing a piece of coastal land, originally called Chennirayarpattinam or Channapatnam, where the Company began the construction of a harbour and a fort. The fort was completed on 23 April 1644 at a cost of £3,000,[5] coinciding with St. George's Day, celebrated in honour of the patron saint of England. The fort, hence christened Fort St. George, faced the sea and some fishing villages, and it soon became the hub of merchant activity. It gave birth to a new settlement area called George Town (historically referred to as Black Town), which grew to envelop the villages and led to the formation of the city of Madras. It also helped to establish English influence over the Carnatic region and to keep the kings of Arcot and Srirangapatna, as well as the French forces based at Pondichéry, at bay. In 1665, after the EIC received word of the formation of the new French East India Company, the fort was strengthened and enlarged while its garrison was increased.[6]

         According to the 17th-century merchant and traveller Thomas Bowrey, Fort St. George was:
         
         without all dispute a beneficial place to the Honourable English India Company, and with all the Residence of theire Honourable Agent and Governour all of their Affaires Upon this Coast and the Coast of Gingalee, the Kingdoms also of Orixa, (Orissa) Bengala (Bengal), and Pattana (Patna), the said Governour and his Councell here resideigne, for the Honour of our English Nation keepinge and maintainneinge the place in great Splendour, Civil and good Government, Entertaineinge nobly all Foraign Embassadors, and provideinge great quantities of Muzlinge (Muslin) Callicoes (Calico) &c. to be yearly transported to England.[7]</p>
   </div>
</body>
</html>
```
# egmore.html
```
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Egmore Chennai</title>
   <style>
      *{
         margin: 0;
         padding: 0;
      }
      div{
         display: flex;
         flex-direction: column;
         /* justify-content: center; */
         height: 100vh;
         align-items: center;
         background-color: cyan;
      }
      .image{
        height: 200px;
      }
   </style>
</head>
<body>
   <div>
      <img src="egmore.jpg" alt="Egmore Chennai" class="image"/>
      <h1>Egmore Chennai</h1>
      <p class="bio">The earliest references to Egmore occur in the inscriptions of the Chola king Kulothunga I.[1] Under the Chola Empire, Egmore was the headquarters of an administrative division or Nadu called Elumbur Nadu.[1] An inscription of the Nellore Chola king Vijaya Kanda Gopal dated 2 September 1264 speaks of a village in Elumur-Tudarmuni Nadu in Pulal Kottam. A Vijayanagar period inscription of Sriranganatha Yadavaraya records an endowment to a monastery in Thiruvottriyur by a resident of Serruppedu (identified with the present day Chetpet) in Elumur-Tudarmuni Nadu.

         Egmore is the Anglicised form of "Ezhumbur", the name of a pre-British era village situated on the northern banks of the River.[2] Despite the fact that Egmore had been a part of the East India Company's possessions since 1720, it was not until the "Golden age of British rule" stretching from 1858 to 1947 that Egmore witnessed some real growth. The Egmore Museum was one of the first notable monuments to be constructed here. The construction of this famous landmark was undertaken immediately after the Sepoy Mutiny of 1857. The Connemara Library was created as an annex housing the Museum's vast book collection and became operational in 1896.
         
         Egmore, in 1796, was the site of the Military Male Orphan Asylum near Madras. This asylum was headed by Andrew Bell, who invented the Madras System for schooling there.</p>
   </div>
</body>
</html>
```
## OUTPUT

![image](https://github.com/Dhiyanesh24/NearMe/assets/118362288/1873b461-fd7b-4380-b29d-0909c66ed0ad)
![image](https://github.com/Dhiyanesh24/NearMe/assets/118362288/058c6f4b-51e1-4253-beb5-dd3f770558fe)
![image](https://github.com/Dhiyanesh24/NearMe/assets/118362288/c95815d4-c0ce-440b-b622-1fd59c445c4f)
![image](https://github.com/Dhiyanesh24/NearMe/assets/118362288/614244cf-841d-43e8-8ec7-90b342c949a2)
![image](https://github.com/Dhiyanesh24/NearMe/assets/118362288/f6c0dca7-eef3-4023-a0f6-768fb33dbde0)

## RESULT
The program for implementing image maps using HTML is executed successfully.
