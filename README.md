# functions-tasks
My answers to the tasks on &lt;https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Functions>


Task 1:
let names = ['Chris', 'Li Kang', 'Anne', 'Francesca', 'Mustafa', 'Tina', 'Bert', 'Jada']
let para = document.createElement('p');

// Add your code here

function chooseName(){
  let randomName = names[Math.floor(Math.random()*names.length)];
  para.textContent = randomName;
}

chooseName();

// Don't edit the code below here!

section.innerHTML = ' ';

section.appendChild(para);
    
    
Task 2:
let canvas = document.querySelector('canvas');
let ctx = canvas.getContext('2d');

let x = 50;
let y = 60;
let width = 100;
let height = 75;
let color = 'blue';

// Add your code here
function draw(){
  ctx.clearRect(0,0,4000,4000);
  ctx.beginPath();
  ctx.rect(x, y, width, height);
  ctx.strokeStyle = color;
  ctx.stroke();
}
draw();
    
Task 3:
let names = ['Chris', 'Li Kang', 'Anne', 'Francesca', 'Mustafa', 'Tina', 'Bert', 'Jada']
let para = document.createElement('p');

// Add your code here

function chooseName(x, y){
  let newArray = names.slice(x, y);
  let result = random(newArray);
  para.textContent = result;
}

function random(newNames){
  let randomName = newNames[Math.floor(Math.random()*newNames.length)];
  return randomName;
}

chooseName(2, 4);

// Don't edit the code below here!

section.innerHTML = ' ';

section.appendChild(para);
    
