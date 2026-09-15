# My-Education-Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>EDUCATION MANDHA MOHIT</title>

<style>
*{
    box-sizing:border-box;
}

body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f7fb;
    color:#222;
}

header{
    background:#173b73;
    color:white;
    padding:16px;
    text-align:center;
    position:sticky;
    top:0;
    z-index:10;
}

header h1{
    margin:0;
    font-size:25px;
}

nav{
    margin-top:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 8px;
    font-size:14px;
}

.hero{
    padding:55px 20px;
    text-align:center;
    background:linear-gradient(135deg,#173b73,#2878d0);
    color:white;
}

.hero h2{
    font-size:40px;
    margin:15px 0;
}

.hero h2 span{
    color:#ffd45c;
}

.hero p{
    font-size:18px;
}

.btn{
    display:inline-block;
    background:#ffd45c;
    color:#222;
    padding:15px 25px;
    border-radius:10px;
    text-decoration:none;
    font-weight:bold;
    margin-top:15px;
}

.container{
    max-width:1000px;
    margin:auto;
    padding:40px 18px;
}

.title{
    text-align:center;
    color:#173b73;
    font-size:32px;
}

.subtitle{
    text-align:center;
    color:#687386;
    font-size:17px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-top:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 15px #00000012;
}

.card .emoji{
    font-size:42px;
}

.card h3{
    color:#2862a5;
}

.card p{
    line-height:1.6;
    color:#687386;
}

/* QUIZ */

.quiz-box{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 15px #00000012;
    max-width:700px;
    margin:25px auto;
}

.option{
    display:block;
    width:100%;
    border:0;
    padding:14px;
    margin:10px 0;
    border-radius:9px;
    background:#eef3fa;
    text-align:left;
    cursor:pointer;
    font-size:16px;
}

.option:hover{
    background:#dce9fb;
}

.option.selected{
    background:#c9ddff;
}

.option.correct{
    background:#c9f7d5;
}

.option.wrong{
    background:#ffd1d1;
}

.quiz-btn{
    border:0;
    background:#173b73;
    color:white;
    padding:13px 20px;
    border-radius:9px;
    cursor:pointer;
    margin:5px;
}

#feedback{
    font-weight:bold;
    font-size:18px;
}

#result{
    font-size:22px;
    font-weight:bold;
    color:#173b73;
}

footer{
    background:#173b73;
    color:white;
    text-align:center;
    padding:25px;
    margin-top:30px;
}

@media(max-width:600px){

    header h1{
        font-size:20px;
    }

    nav a{
        margin:0 4px;
        font-size:12px;
    }

    .hero h2{
        font-size:30px;
    }

    .title{
        font-size:27px;
    }
}
</style>
</head>

<body>

<!-- HEADER -->

<header>

<h1>📚 EDUCATION <span style="color:#ffd45c;">MANDHA MOHIT</span></h1>

<nav>
<a href="#home">Home</a>
<a href="#courses">Courses</a>
<a href="#quiz">Quiz</a>
<a href="#study">Study</a>
<a href="#about">About</a>
</nav>

</header>


<!-- HOME -->

<section class="hero" id="home">

<p>🎓 Learn • Practice • Improve</p>

<h2>
EDUCATION <span>MANDHA MOHIT</span>
</h2>

<p>
आपकी पढ़ाई को आसान बनाने का एक प्रयास।
</p>

<p>
Learn English, Practice Questions & Prepare Better for Exams.
</p>

<a class="btn" href="#courses">
Start Learning →
</a>

</section>


<!-- COURSES -->

<section class="container" id="courses">

<h2 class="title">
Our Courses / हमारे Courses
</h2>

<p class="subtitle">
Learn step-by-step with easy explanations and smart practice.
</p>


<div class="grid">

<div class="card">

<div class="emoji">🔤</div>

<h3>English Vocabulary</h3>

<p>
One Word Substitution, meanings,
examples and easy tricks.
</p>

</div>


<div class="card">

<div class="emoji">💡</div>

<h3>Idioms & Phrases</h3>

<p>
English + Hindi meaning with
simple memory tricks.
</p>

</div>


<div class="card">

<div class="emoji">📝</div>

<h3>Exam Preparation</h3>

<p>
Practice questions, revision
and exam-focused learning.
</p>

</div>

</div>

</section>


<!-- STUDY -->

<section class="container" id="study">

<h2 class="title">
Study Material / अध्ययन सामग्री
</h2>

<p class="subtitle">
Useful content for regular learning and revision.
</p>


<div class="grid">

<div class="card">

<div class="emoji">📖</div>

<h3>Notes</h3>

<p>
Important English notes and
revision material.
</p>

</div>


<div class="card">

<div class="emoji">🧠</div>

<h3>Tricks</h3>

<p>
याद करने के आसान mnemonic
और root-word tricks.
</p>

</div>


<div class="card">

<div class="emoji">📚</div>

<h3>Revision</h3>

<p>
Quick one-line revision से
अपनी तैयारी मजबूत करें।
</p>

</div>

</div>

</section>


<!-- QUIZ -->

<section class="container" id="quiz">

<h2 class="title">
📝 Quiz / टेस्ट
</h2>

<p class="subtitle">
अपनी तैयारी को test करें।
</p>


<div class="quiz-box">

<p id="qno"></p>

<h3 id="question"></h3>

<div id="options"></div>

<button class="quiz-btn" id="submit">
Submit Answer
</button>

<button class="quiz-btn" id="next" style="display:none;">
Next Question →
</button>

<p id="feedback"></p>

<p id="result"></p>

</div>

</section>


<!-- ABOUT -->

<section class="container" id="about">

<h2 class="title">
About / हमारे बारे में
</h2>

<div class="card">

<h3>EDUCATION MANDHA MOHIT</h3>

<p>
यह educational website English learning,
vocabulary, idioms, exam preparation
और quiz practice के लिए बनाई गई है।
</p>

<p>
हमारा उद्देश्य है कि पढ़ाई को
simple, interesting और आसान बनाया जाए।
</p>

</div>

</section>


<!-- FOOTER -->

<footer>

© 2026 EDUCATION MANDHA MOHIT

<br><br>

Learn • Practice • Improve 🚀

</footer>


<!-- QUIZ JAVASCRIPT -->

<script>

const quiz = [

{
q:"Bibliophile means:",
o:[
"A book lover",
"A dictionary maker",
"A teacher",
"A traveller"
],
a:0
},

{
q:"Lexicographer is a person who:",
o:[
"Writes poems",
"Compiles dictionaries",
"Teaches Maths",
"Reads newspapers"
],
a:1
},

{
q:"Philogynist means:",
o:[
"A lover of books",
"A lover of women",
"A dictionary maker",
"A person who hates learning"
],
a:1
},

{
q:"Aerodrome is a place for:",
o:[
"Trains",
"Ships",
"Aircraft",
"Buses"
],
a:2
},

{
q:"Aquarium is a place where:",
o:[
"Books are kept",
"Live fish are kept",
"Planes are kept",
"Cars are kept"
],
a:1
}

];


let current = 0;
let score = 0;
let answered = false;


const qno =
document.getElementById("qno");

const question =
document.getElementById("question");

const options =
document.getElementById("options");

const submit =
document.getElementById("submit");

const next =
document.getElementById("next");

const feedback =
document.getElementById("feedback");

const result =
document.getElementById("result");


function loadQuestion(){

answered = false;

feedback.textContent = "";

result.textContent = "";

submit.style.display = "inline-block";

next.style.display = "none";


qno.textContent =
"Question " + (current + 1) +
" of " + quiz.length;


question.textContent =
quiz[current].q;


options.innerHTML = "";


quiz[current].o.forEach((text,index)=>{

let button =
document.createElement("button");

button.className = "option";

button.textContent =
String.fromCharCode(65 + index)
+ ". " + text;


button.onclick = function(){

if(answered) return;

document
.querySelectorAll(".option")
.forEach(btn =>
btn.classList.remove("selected")
);

button.classList.add("selected");

button.dataset.choice = index;

};


options.appendChild(button);

});

}


submit.onclick = function(){

if(answered) return;


let selected =
document.querySelector(".option.selected");


if(!selected){

feedback.textContent =
"⚠️ पहले एक option चुनो।";

return;

}


answered = true;


let choice =
Number(selected.dataset.choice);


document
.querySelectorAll(".option")
.forEach((button,index)=>{

if(index === quiz[current].a){

button.classList.add("correct");

}

if(index === choice &&
choice !== quiz[current].a){

button.classList.add("wrong");

}

});


if(choice === quiz[current].a){

score++;

feedback.textContent =
"✅ Correct! सही उत्तर";

}

else{

feedback.textContent =
"❌ Wrong! सही उत्तर: " +
String.fromCharCode(65 + quiz[current].a);

}


submit.style.display = "none";

next.style.display = "inline-block";

};


next.onclick = function(){

current++;


if(current < quiz.length){

loadQuestion();

}

else{

qno.textContent = "";

question.textContent =
"🎉 Quiz Complete!";


options.innerHTML = "";

submit.style.display = "none";

next.style.display = "none";

feedback.textContent = "";

result.textContent =
"Your Score: " +
score + " / " + quiz.length;


let restart =
document.createElement("button");

restart.className = "quiz-btn";

restart.textContent =
"Restart Quiz";


restart.onclick = function(){

current = 0;

score = 0;

loadQuestion();

};


options.appendChild(restart);

}

};


loadQuestion();

</script>

</body>
</html>
