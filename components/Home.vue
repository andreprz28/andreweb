<template>
    <div id="home">
        <div id="homesection">
            <img src="static/selfpic.png" alt="boy smiling standing in front of Columbia Low Library" id="selfpic" width="300px" height="300px"/>
            <div class="intro">
                <p> 👋🏼 Kumusta! I'm Andre Perez </p> 
                <a href="https://www.linkedin.com/in/andreperez28/" target="_blank"><img src="linkedin.png" alt="linkedin icon" height="50px"></a>
                <a href="https://www.facebook.com/andre.perez.357/" target="_blank"><img src="fb.png" alt="facebook icon" height="50px"></a>
                <a href="https://twitter.com/andreprz_" target="_blank"><img src="twitter.png" alt="twitter icon" height="50px"></a>
            </div>
        </div>

        <div>

        </div>

        <div class="About">
            <p>About Me</p>
                <div id="titleabout">
                    <p> Make Science. Teach Science. Write Science.</p>
                </div>
                <div id="contentabout">
                    <p> Hello! I’m Andre, a biomedical engineering student at Columbia University, taking up a minor in entrepreneurship & innovation, and a Named Scholarship recipient. Hailing from the vibrant islands of the Philippines, I aspire to use the intersection of medicine and technology to bridge health inequities in third-world countries, and hopefully, build technologies to solve the world's most pressing issues in medicine. Outside of engineering, I love teaching science and writing about science!</p>
                </div>
        </div>
    </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@800&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital@1&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital@1&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@1,300&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap');
    #selfpic{
        align-items:center;
        margin: 70px 70px 30px 120px;
    }
    .intro{
        text-align: center;
        font-family: 'Playfair Display';
        font-size: 50px;
        font-style: italic;
        margin: 95px 0px 30px 0px;
    }
    #homesection{
        margin: auto;
        display: flex;
        justify-content: space-evenly;
        
    }
    #footer{
        text-align: center;
        font-size: 10px;
        font-family: Playfair Display; 
    }
    #footer{
        margin-top: auto;
        padding-top: 1em;
    }
    #home{
        margin: auto;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }
    .About{
        font-family: 'Playfair Display';
        margin: auto;
        text-align: center;
        width: 70%;
        height: 40%;
        font-size: 40px;
    }
    #titleabout{
        font-family:'Ubuntu';
        font-style: italic;
        font-size: 30px;
    }
    #contentabout{
        font-family: 'Ubuntu';
        font-size: 20px; 
    }
</style>
