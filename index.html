const canvas = document.getElementById('matrixCanvas');
const ctx = canvas.getContext('2d');

let fontSize = 20;
let columns = Math.floor(window.innerWidth / fontSize);
let rows = Math.floor(window.innerHeight / fontSize);

const chars =
  '0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz' +
  '!@#$%^&*()_+-=[]{};:\'",.<>?/|~`' +
  'アァカサタナハマヤャラワガザダバパイィキシチニヒミリヰギジヂビピウゥクスツヌフムユュルグズブヅプエェケセテネヘメレヱゲゼデベペオォコソトノホモヨョロヲゴゾドボポヴッン' +
  'ከጀደኘነዠኀዘቸዐተቨጨጰጸፀፈፐ' +
  'אבעכרקגדזסשמחניטואצלתךףץפםןונה';

let drops = Array.from({ length: columns }, () => Math.random() * rows);

function resizeCanvas() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
  columns = Math.floor(canvas.width / fontSize);
  rows = Math.floor(canvas.height / fontSize);
  drops = Array.from({ length: columns }, () => Math.random() * rows);
}

window.addEventListener('resize', resizeCanvas);
resizeCanvas();

function drawMatrixRain() {
  ctx.fillStyle = 'rgba(0, 0, 0, 0.1)';
  ctx.fillRect(0, 0, canvas.width, canvas.height);
  
  ctx.font = `${fontSize}px monospace`;
  ctx.shadowBlur = 12;
  ctx.shadowColor = '#0f0';
  ctx.fillStyle = '#0f0';
  
  for (let i = 0; i < columns; i++) {
    const x = i * fontSize;
    const y = drops[i] * fontSize;
    const char = chars.charAt(Math.floor(Math.random() * chars.length));
    ctx.fillText(char, x, y);
    
    drops[i] += 0.5;
    if (drops[i] >= rows) drops[i] = 0;
  }
}

function animate() {
  drawMatrixRain();
  requestAnimationFrame(animate);
}

animate();
