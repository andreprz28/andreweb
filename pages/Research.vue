<template>
    <div>
        <NavBar/>
        <div id="titleresearch">
            <p>Research </p>
        </div> 
            <div id="research1"> 
                <img src="/researchpic1.jpg" alt="boy wearing blue lag gown inside laboratory" id="researchpic1" width="300px" height="200px"/>
                <div class="research1text">
                    <p id="research1title"> Columbia Nanotechnology Initiative - Nuckolls Lab </p>
                    <p class="research1content"> Research Assistant</p>
                    <p class="research1content"> As complex diseases get harder to be detect and diagnose, the need for more efficient biosensing technologies in biomedical devices is more important than ever. In this light, our research focuses on revolutionizing the nanofabrication of Organic Electrochemical Transistors (OECTs) using a newly synthesized moolecule called Macrocyclic Emeralidines as channel material which is a mega slay.  </p>
                </div>
            </div>
            <div id="research2">
                <img src="/cornell.jpg" alt="cornell medical school fornt view" id="cornell" width="300px" height="250px"/>
                <div class="research2text">
                    <p id="research2title">Weill Cornell Medicine COVID-19 Community Education & Empowerment Internship</p>
                    <p class="research2content">Intern</p>
                    <p class="research2content">The COVID-19 pandemic has revealed the need for an improved systemic public health response and has shown the lack of public-wide education about health. The gravity of the situation would've been ameliorated if only education and science has been prioritized. With this, I am working on a capstone research about managing infectious diseases and working with low-income communities around NYC to increase awareness and bridge information on vaccine and protein sciences, epidemiology, drug delivery, and virology.   </p>
                </div>
            </div>
            <div id="research3">
                <img src="/researchpic2.jpg" alt="boy wearing blue lagbown inside laboratory working with glove box" id="researchpic2" width="300px" height="180px"/>
                <div class="research3text">
                    <p id="research3title">Columbia Space Initiative - Space Microbiology Mission</p>
                    <p class="research3content">Researcher</p>
                    <p class="research3content">As part of the biology subgroup, we are studying the effects of microgravity environments on ZnO nanoparticles and studying if microgravity alters or improves the microbicidal properties of these crystals. </p>
                </div>    
            </div>
            <div id="research4">
                <img src="energy.jpg" alt="slide saying energy applications of quantum computing" id="researchpic3" width="300px" height="180px"/>
                <div class="research4text">
                    <p id="research4title">Columbia Summer Physics Research Program</p>
                    <p class="research4content">Research Program Participant</p>
                    <p class="research4content">As quantum technologies get more advanced over the years, our team presented research and related literature during this intensive summer program about the applications of quantum computing and quantum simulations in the energy sector. We delved into material sciences, particle physics, & complex energy processes research that involve quantum technologies and discussed how this revolutionizes sustainable energy production. </p>
                </div> 
            </div>
        <div id="titleproject">
            <p>Projects </p>
        </div>
            <div id="project1">
                <img src="/maternal.png" alt="maternal belt" id="projectpic1" width="300px" height="250px"/>
                <div class="project1text">
                        <p id="project1title">Portable Maternal/Fetal Belt Monitor with Automated Notification System</p>
                        <p id="project1content"> To help alleviate the rise of mortality rates in women living in plaves with no available pregnancy clinics, we've developed a proposal for a belt that can monitor maternal and fetal status and detect possible obstetrical health complications that may arise during the pregnancy. It sends SMS notifications and notifies patients through an alarm system (light, sound, and SMS) </p>
                </div> 
            </div>
            <div id="project2">
                <img src="/greenhouse.jpg" alt="greenhouse" id="projectpic2" width="320px" height="250px"/>
                <div class="project2text">
                        <p id="project2title">Multipurpose Automated Greenhouse and Safety Keeping Agri-tech Device</p>
                        <p id="project2content"> Innovated a greenhouse for low-income farmers that has atmospheric regulation; sensor-modulated soil moisture control; GSM notification; roof that opens/closes depending on precipitation levels; and a crop-drying facility </p>
                </div> 
            </div>
            <div id="project3">
                <img src="firehouse.jpg" alt="fire" id="projectpic3" width="320px" height="280px"/>
                <div class="project3text">
                        <p id="project3title">Automated GSM-Based System for Fire Escape and Pyro – Mitigation</p>
                        <p id="project3content"> Created a robotic system that automatically unlocks the fire exit door and window, notifies the owner and the fire department, alarms the household, and triggers a water sprinkler when a fire is detected. </p>
                </div> 
            </div>
            <div id="project4">
                <img src="wearable.JPEG" alt="wearable technologies" id="projectpic4" width="320px" height="280px"/>
                <div class="project4text">
                        <p id="project4title">Electromagnetic Force and Human-Powered Electricity Generating Device</p>
                        <p id="project4content"> Developed a wearable device that utilizes 55MGOe Neodymium magnets, salvaged from old hard disc drives, to generate electricity by walking </p>
                </div> 
            </div>
    </div> 
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital@1&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital@1&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap');
    #titleresearch{
        text-align:center;
        font-family: Playfair Display;
        font-weight: 800;
        font-size: 40px;
        margin-top: 100px;
    }

    #researchpic1{
        margin: 90px 20px 130px 280px;
    }

    #research1{
        display: flex;
    }
    .research1text{
        max-width: 500px;
        margin: 50px;
    }
    #research1title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic
    }
    .research1content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #research2{
        display: flex;
    }
    .research2text{
        max-width: 500px;
        margin: 50px;
    }
    #research2title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic
    }
    .research2content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #cornell{
        margin: 90px 20px 170px 280px;
    }
    #research3{
        display: flex;
    }
    .research3text{
        max-width: 500px;
        margin: 20px;
    }
    #research3title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic
    }
    .research3content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #researchpic2{
        margin: 40px 50px 140px 280px;
    }
    #research4{
        display:flex;
    }
    #researchpic3{
        margin: 40px 50px 150px 280px;
    }
    .research4text{
        max-width: 500px;
        margin: 50px;
    }
    #research4title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    #titleproject{
        text-align:center;
        font-family: Playfair Display;
        font-weight: 800;
        font-size: 40px;
    }
    #researchpic3{
        margin: 80px 10px 150px 280px;
    }
    .research4content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #project1{
        display: flex;
    }
    .project1text{
        max-width: 500px;
        margin: 50px;
    }
    #project1title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    #project1content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #projectpic1{
        margin: 80px 10px 150px 280px;
    }
    #project2{
        display: flex;
    }
    .project2text{
        max-width: 500px;
        margin: 50px;
    }
    #project2title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    #project2content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #projectpic2{
        margin: 80px 0px 150px 280px;
    }
    #project3{
        display: flex;
    }
    .project3text{
        max-width: 500px;
        margin: 50px;
    }
    #project3title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    #project3content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #projectpic3{
        margin: 80px 0px 150px 280px;
    }
    #project4{
        display: flex;
    }
    .project4text{
        max-width: 500px;
        margin: 50px;
    }
    #project4title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    #project4content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #projectpic4{
        margin: 80px 0px 150px 280px;
    }
</style>
