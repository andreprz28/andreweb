<template>
    <div>
        <NavBar/>
        <div id="titleactivities">
            <p>Activities</p>
        </div> 
        <div id="activitiesintro">
            <br>
                Make Science. Teach Science. Write Science.
            <br>
                These three ethos have always guided me with how I optimize my skills for the benefit of the people. Coming from a far-flung town in the Philippines, resources for STEM has always been subpar and my firsthand experiences has allowed me to delve into mass-wide science communication and science & health education.
        </div>
        <div id="activity1">
            <img src="/logo.jpg" alt="inspire logo" id="logo1" width="200px" height="200px"/>
            <div class="activity1text">
                    <p id="activity1title"> EINS(pi)RE </p>
                    <p class="activity1content"> Founder & Executive Director</p>
                    <p class="activity1content"> I've established this non-profit with goals of bridging educational resources in low-income indegneous communities in the Philippines. Our weekly tutoring sessions and academic resources has helped hundreds of kids like me and have allowed education to become available for all. If you care about kids, donate asap. </p>
            </div>
        </div>
        <div id="activity2">
            <img src="/sheal.jpeg" alt="s-heal logo" id="logo2" width="200px" height="200px"/>
            <div class="activity2text">
                    <p id="activity2title"> Students for Health Education, Access, and Literacy (S-HEAL) </p>
                    <p class="activity2content"> Health Educator </p>
                    <p class="activity2content"> S-HEAL aims to increase knowledge in medicine and pre-pubescent health by visiting underfunded high schools in the greater New York City by spearheading classroom dicussions and creating comprehensive health curriculums. </p>
            </div>
        </div>
        <div id="activity3">
            <img src="/scribes.png" alt="scribes" id="logo3" width="180px" height="250px"/>
            <div class="activity3text">
                    <p id="activity3title"> Tuguegarao City Scribes </p>
                    <p class="activity3content"> Science & Technology Page Head Editor </p>
                    <p class="activity3content"> Dessiminated sceintific information and raised awareness on latest scientific breakthrough by writing 50+ articles for the publication. Nationally-acclaimed journalist, National Press Conference Cohort Member, with multiple awards in science and technology writing. </p>
            </div>
        </div>
        <div id="activity4">
            <img src="/cause.jpg" alt="cause philippines" id="logo4" width="210px" height="200px"/>
            <div class="activity4text">
                    <p id="activity4title"> CAUSE Philippines </p>
                    <p class="activity4content"> Mentorship Program Associate Director and Mentor </p>
                    <p class="activity4content"> Nationwide non-profit organization that helps underprivileged Filipino students to pursue undergraduate education abroad. Helped 200+ students win 〜19 million worth of scholarships from 90+ universities worldwide. </p>
            </div>
        </div>
    </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital@1&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital@1&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap');
    #titleactivities{
        text-align:center;
        font-family: Playfair Display;
        font-weight: 800;
        font-size: 40px;
        margin-top: 100px;
    }
    #activitiesintro{
        font-family: 'Ubuntu';
        font-size: 20px; 
        text-align: center;
        max-width: 850px;
        margin-left: auto;
        margin-right: auto;
    }
    #activity1{
        display:flex;
    }
    #logo1{
        margin: 110px 20px 130px 280px;
    }
    .activity1text{
        margin-top: 100px;
        max-width: 600px;
    }
    #activity1title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    .activity1content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #activity2{
        display:flex;
    }
    #logo2{
        margin: 110px 20px 130px 280px;
    }
    .activity2text{
        margin-top: 100px;
        max-width: 600px;
    }
    #activity2title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    .activity2content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #activity3{
        display:flex;
    }
    #logo3{
        margin: 110px 40px 130px 280px;
    }
    .activity3text{
        margin-top: 100px;
        max-width: 600px;
    }
    #activity3title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    .activity3content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
    #activity4{
        display:flex;
    }
    #logo4{
        margin: 110px 20px 130px 280px;
    }
    .activity4text{
        margin-top: 100px;
        max-width: 600px;
    }
    #activity4title{
        font-family: 'Ubuntu';
        font-size: 30px;
        font-style: italic;
    }
    .activity4content{
        font-family: 'Ubuntu';
        font-size: 15px;
    }
</style>