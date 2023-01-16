<template>
    <div class="navbar">
        <NuxtLink to="/" id="home">andre perez.</NuxtLink>
        <div id="links">
            <a href=mailto:avp2141@columbia.edu target="blank">Contact</a>
            <a href="/resume.pdf" target="blank">Resume</a>
            <NuxtLink to="/Activities">What I Do</NuxtLink> 
            <NuxtLink to="/Research">Research & Projects</NuxtLink> 
        </div>
    </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&display=swap');

    #links a{
        display: flex; 
        list-style: none;
        float: right; 
        margin-top: 10px;
        padding: 20px;
        color: black;
        font-family: 'Playfair Display';
        font-weight: lighter;
        font-size: 20px;
        text-decoration: none; 
        cursor: pointer;
    }

    #home{
        float: left;
        text-decoration: none;
        font-family: 'Playfair Display';
        font-weight: 700;
        font-size: 45px;
        margin-left: 20px;
        margin-top: 10px;
        color: black;
    }

    .navbar{
        display: flex; 
        justify-content: space-between; 
    }

</style>
