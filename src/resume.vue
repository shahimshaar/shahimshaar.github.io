<template>
  <div id="app">
    <h1 style="text-align:center;color:yellow">Shahim Shaar</h1>
    <h2 style="text-align:center">Personal Website and Portfolio</h2>
    <img src="./assets/me.jpg"> 
    <p style="text-align:left;font-size:16px;color:navy"> Hello and welcome to my website! I am a 22-year-old Senior Computer Science major at Knox College. I am from Aleppo, Syria.</p>
    <p style="text-align:left;font-size:14px"> I am pursuing a career in software engineering, web devlopment, and academic research.</p>
    <p style="text-align:left;font-size:14px"> Ideally, I would like a career in either mobile or web app development. I want to be part of a team full of creative, collaborative individuals whom I can learn from and grow with.</p>
    <p style="text-align:left;font-size:14px"> This website is intended to showcase my personal and class projects to potential employers as well as the Github community. I intend to do a better job of organizing my repos, but this page contains explanations of some of my favorite projects.</p>
    <p style="text-align:left;font-size:14px"> Fun Facts: I am obsessed with/addicted to soccer, I play the Oud, and I love hip hop.</p>
    <h3 style="text-align:center">Biographical Information:</h3>
    <p style="text-align:left;font-size:14px"> Date of Birth: 11/08/1998</p>
    <p style="text-align:left;font-size:14px"> Immigration Status: Asylum Seeker with Work Authorization</p>
    <p style="text-align:left;font-size:14px"> Email: <a href="mailto:sshaar@knox.edu">sshaar@knox.edu</a> </p>
    <h3 style="text-align:center">Links:</h3>
    <p style="text-align:left;font-size:14px"> Repl.it <a href="https://replit.com/@shshimshaar">Page</a> </p>
    <p style="text-align:left;font-size:14px"> Facebook <a href="https://www.facebook.com/ShahimShaar/">Page</a> </p>
    <p style="text-align:left;font-size:14px"> Instagram <a href="https://www.instagram.com/ShahmShaar/">Page</a> </p>
    <h3 style="text-align:center">Resume:</h3>
    <img src="./assets/resume1.jpg">
    <img src="./assets/resume2.jpg"> 
    <h3 style="text-align:center">Portfolio Selection:</h3>
    <b>In The Dead Of Night: Unity3D Mobile Game</b> 
    <p> ____ </p>
    <img src="./assets/indead.jpg">
    <p style="text-align:left;font-size:14px"> Built this game for Android, using Unity3D and C#, for CS 292 with Zach Gregory. the game's main character, Bulby, is positioned in the middle of the screen. Shadow enemies come in from all possible angles at an increasing spawn rate, speed, and health bar. The goal is to survive as long as possible by shooting down the shadow enemies and utilising the power-ups. </p>
    <b>Parallelized Conway's Game of Life</b> 
    <p> ____ </p>
    <p style="text-align:left;font-size:14px"> Wrote this parallelized simulation of Conway's Game of Life in C (see <a href="https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life">Wikipedia</a> entry for more background on the game and its rules) using Pthreads for CS 309. The game starts with an initial grid that spawns depending on the inputted starting likelihood for each cell to be alive. With input for a full initial grid that is 4x4, we get the following game rounds outputted: </p>
    <img src="./assets/conway.jpg">
    </div>
</template>

<script>
export default {
  name: 'resume',
}
</script>