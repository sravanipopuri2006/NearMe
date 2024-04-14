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
## map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color:rgb(222, 218, 135) ;">
    <h1 style="color: brown;"><b><u>IYYAPATHANGAL</u></b></h1>
    <img src="home.png" width="80%" height="60%" usemap="#map" ><br>
    <MAP name="map">
         <AREA shape="RECT" coords="100,100,800,900" href="acs.html" Title="ACS MEDICAL COLLEGE"> </AREA>
         <AREA shape="RECT" coords="500,100,400,400" href="aravind_eye.html" Title="ARAVIND EYE HOSPITAL"> </AREA>
         <AREA shape="RECT" coords="100,100,300,900" href="saveetha_dental.html" Title="ACS MEDICAL COLLEGE"> </AREA>
         <AREA shape="RECT" coords="500,500,400,400" href="svv_madapam.html" Title="ARAVIND EYE HOSPITAL"> </AREA>
         <AREA shape="RECT" coords="100,100,800,900" href="bisleri_company.html" Title="ACS MEDICAL COLLEGE"> </AREA>
         

        
    </MAP>
    <h2 style="text-align: right;">-BY POPURI SRAVANI</h2>
    
</body>
</html>
```
## aravind_eye.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styleacs.css">
</head>
<body style="background-color: rgb(234, 215, 250);">
    <h1>
        <p>WELCOME TO ARAVIND EYE HOSPITAL</p>
    </h1>
    <hr>
    <br>
    <div class="photo">
    <img src="EYE.jpeg" alt="photo" width="800px" height="400px">
</div>
<hr>
<h2>
    ABOUT ARAVIND EYE HOSPITAL
</h2>
<h3>
    The problem of avoidable blindness rapidly escalating remained a major cause of concern in the Indian healthcare scenario. In a developing country like India, the government alone cannot meet the health needs of all owing to a number of challenges like growing population, inadequate infrastructure, low per capita income, aging population, diseases in epidemic proportions and illiteracy.

Realizing this, Dr. Venkataswamy wished to establish an alternate health care model that could supplement the efforts of the government and also be self-supporting. Following his retirement at age 58 in 1976, he established the GOVEL Trust under which Aravind Eye Hospitals were founded.

The hospitals are named after Sri Aurobindo, one of the 20th century’s most revered spiritual leaders. In essence, Sri Aurobindo’s teachings insist on transcendence into a heightened state of consciousness and becoming better instruments for the divine force to work through.

In an eleven bed hospital manned by 4 medical officers, Dr.V saw the potential for what is today, one of the largest facilities in the world for eye care. Over the years, this organisation has evolved into a sophisticated system dedicated to compassionate service for sight.

   </h3> 
</body>
</html>
```
## bisleri_company.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styleacs.css">
</head>
<body style="background-color: rgb(237, 165, 165);">
    <h1>
        <p>BISLERI WATER COMPANY</p>
    </h1>
    <hr>
    <br>
    <div class="photo">
    <img src="BISLERI.jpeg" alt="photo" width="800px" height="400px">
</div>
<hr>
<h2>
    ABOUT BISLERI
</h2>
<h3>
    Drinking water is essential for your health and well-being. It helps you regulate your body temperature, flush out toxins, maintain skin health, prevent dehydration, and more. But not all water is safe and pure. That's why you need Bisleri packaged drinking water, purified and enriched with minerals, to give you the best quality water possible.

Bisleri packaged drinking water is available in different bottle sizes for you to choose from as per your needs. Whether you need a small bottle, or a large water can for your family or office, Bisleri has you covered. You can also subscribe to the Bisleri@Doorstep service (through our website or app) and get your water delivered to your doorstep at regular intervals.

So don't compromise on your health. Choose Bisleri packaged drinking water and enjoy the goodness of pure and safe water every day.
</h3>
    
    
</body>
</html>
```
## saveetha_dental.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styleacs.css">
</head>
<body style="background-color: rgba(0, 255, 255, 0.319);">
    <h1>
        <p>WELCOME TO SAVEETHA DENTAL COLLEGE AND HOSPITAL</p>
    </h1>
    <hr>
    <br>
    <div class="photo">
    <img src="saveethadental.jpeg" alt="photo" width="800px" height="400px">
</div>
<hr>
<h2>
    ABOUT SAVEETHA DENTAL
</h2>
<h3>
    Saveetha dental college begun its journey in dental education with a strength of 40 students. Its here a small tight community of dental professional who have become principals and deans in various institutions began their first steps in their career. The students faculty and staff of those days were so friendly and attached that even today with all our advent into small group learning, we are yet to replicate such a strong sense of community. The alumni who from the very first years are the most active members of the Saveetha old students association (SOSA).From 1988 to date we have travelled a miraculous journey that has transpired the institution from a novice to an expert. Although we stand tall and strong today, we should not forget our historic path; as these valuable experiences have carved our culture over the past 3 decades. 
</h3>
    
</body>
</html>
```

## svv_madapam.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styleacs.css">
</head>
<body style="background-color: rgb(184, 178, 68);">
    <h1>
        <p>SVV KALYANA MADAPAM  </p>
    </h1>
    <hr>
    <br>
    <div class="photo">
    <img src="SVV.jpg" alt="photo" width="800px" height="400px">
</div>
<hr>
<h2>
    ABOUT SVV
</h2>
<h3>
    SVV KALAYANA MANDAPAM
    icon
    Marriage is the beginning to a new life of joy, happiness and togetherness, where else better to start your journey than at a beautiful venue. SVV KALAYANA MANDAPAM is the perfect abode for your family's wedding/function where modern meets tradition, suiting the new generation yet not forgetting the traditional roots.
    
    SVV KALAYANA MANDAPAM is located on poonamallee high road near SAVEETHA DENTAL COLLEGE/opp to ARVIND EYE HOSPITAL, making it easily accessible from any where in the city and avoid the traffic congestion.The wedding is an important day in of the lifetime. Everyone wish to make this day’s celebrations to be grand and memorable forever. The preparation for marriage starts months before the day of the wedding. Each and everything from the bride and grooms dress, decorations, guests, catering, wedding photographer, gifts, etc...

   </h3> 
    
</body>
</html>
```
## acs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styleacs.css">
    
</head>
<body>
    <h1>
        <p>WELCOME TO ACS MEDICAL COLLEGE AND HOSPITAL</p>
    </h1>

    <hr>
    <br>
    <div class="photo">
    <img src="acsimg.webp" alt="photo">
</div>
<hr>
<h2>
    ABOUT ACS
</h2>
<h3>
    Being a developing nation, health and hygiene are mainstays in terms of national priority. With so many people living below the poverty line, statistics reveal that unhealthy living conditions will lead to disease and epidemics, unless a proactive approach by the medical community is put into action. Keeping these in mind, Dr.M.G.R.Educational and Research Institute, Deemed to be University has established A.C.S.Medical College and hospital in 2008. Besides imparting necessary medical and technological skills,
    To create able physicians of global relevance with right proportions of passion and compassion
To provide quality medical care to all sectors of the society at a cost the community can afford
To produce top notch doctors who are capable of performing well in diverse professional and cultural settings
To provide worldclass medical education with opportunities for need based research and to provide holistic health care services to the community.
To use advances medical technologies in medical education and mould our students as experts in medical profession and mould our students as experts in medical profession.
</h3>


        
        
</body>
</html>
```



## OUTPUT
## map.html
![image](https://github.com/sravanipopuri2006/NearMe/assets/139778301/068b4f66-d7b3-4aad-bfbc-dcdef6bba9f8)

## aravind_eye.html
![image](https://github.com/sravanipopuri2006/NearMe/assets/139778301/eba144c2-d89b-4fb7-b918-435edfaa0d2c)

## saveetha_dental.html
![image](https://github.com/sravanipopuri2006/NearMe/assets/139778301/f72008f1-d3df-42ea-894b-a0d883826542)

## bisleri_company.html
![image](https://github.com/sravanipopuri2006/NearMe/assets/139778301/44fedbc6-7081-4790-90ed-6a741beab4fe)

## Svv_madapam.html
![image](https://github.com/sravanipopuri2006/NearMe/assets/139778301/0436f81e-3e43-4ff2-8df4-62e341bb72d0)
## acs.html
![image](https://github.com/sravanipopuri2006/NearMe/assets/139778301/5e73f3f7-d7eb-4435-8a82-974a4119a23f)









## RESULT
The program for implementing image maps using HTML is executed successfully.
