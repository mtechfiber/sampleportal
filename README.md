<!DOCTYPE html>
<html lang="en" data-theme="dark" data-portal-theme="clean" data-portal-style="glass">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Service Restricted</title>
<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Segoe UI', sans-serif;
}

body {
height: 100vh;
background: linear-gradient(-45deg, #0f172a, #0b1120, #111827, #0a0f1f);
background-size: 400% 400%;
animation: gradientBG 12s ease infinite;
display: flex;
justify-content: center;
align-items: center;
color: white;
overflow: hidden;
}

@keyframes gradientBG {
0% { background-position: 0% 50%; }
50% { background-position: 100% 50%; }
100% { background-position: 0% 50%; }
}

.container {
width: 360px;
padding: 30px;
border-radius: 20px;
background: rgba(255,255,255,0.05);
backdrop-filter: blur(20px);
border: 1px solid rgba(255,255,255,0.1);
text-align: center;
transform: scale(0.88);
transform-origin: center;
}

.logo img {
width: 250px;
margin-bottom: 15px;
}

h2 {
font-size: 18px;
font-weight: 750;
margin-bottom: 10px;
color: #aaaaaa;
}

.notice-box {
background: rgba(255, 0, 0, 0.15);
padding: 12px;
border-radius: 10px;
font-size: 14px;
margin: 15px 0;
color: hsl(0, 0%, 66%);
}

.pay-now {
padding: 14px;
border-radius: 10px;
font-weight: bold;
margin-top: 15px;
background: linear-gradient(135deg, #22c55e, #16a34a);
cursor: pointer;
}

.footer {
font-size: 11px;
margin-top: 18px;
opacity: 0.6;
}

.payment-group {
display: none;
gap: 10px;
margin-top: 12px;
flex-wrap: wrap;
}

.payment-group button {
flex: 1 1 140px;
padding: 14px;
border-radius: 10px;
border: none;
color: white;
font-weight: bold;
cursor: pointer;
}

.gcash-btn {
background: linear-gradient(135deg, #007dff, #005fcc);
}

.maya-btn {
background: linear-gradient(135deg, #00b14f, #008f3f);
}

.bpi-btn {
background: linear-gradient(135deg, #b11116, #7a0c10);
}

.gotyme-btn {
background: #00D9E8;
color: #1B1F2E !important;
}

.maribank-btn {
background: linear-gradient(135deg, #f97316, #ea580c);
}

.bdo-btn {
background: linear-gradient(135deg, #0050a4, #003b7a);
}

.contact-btn {
display: block;
padding: 14px;
border-radius: 12px;
font-weight: bold;
margin-top: 18px;
cursor: pointer;
background: #111827;
color: #e5e7eb;
transition: 0.2s ease;
}

.contact-btn:hover {
background: #0b1120;
transform: scale(1.02);
}

.modal {
display: none;
position: fixed;
z-index: 9999;
left: 0;
top: 0;
width: 100%;
height: 100%;
background: rgba(0, 0, 0, 0.2);
backdrop-filter: blur(6px);
justify-content: center;
align-items: center;
animation: fadeIn 0.2s ease;
}

.modal-content {
background: #111827;
padding: 28px;
border-radius: 18px;
text-align: center;
position: relative;
width: 360px;
animation: pop 0.2s ease;
transform: scale(0.88);
transform-origin: center;
}

@keyframes pop {
from { transform: scale(0.80); opacity: 0; }
to { transform: scale(0.88); opacity: 1; }
}

.modal-content img {
width: 100%;
border-radius: 12px;
margin-top: 10px;
}

.close-btn {
position: absolute;
top: 12px;
right: 16px;
font-size: 20px;
cursor: pointer;
}

.number-box {
background: rgba(255,255,255,0.08);
padding: 12px;
border-radius: 8px;
margin-top: 10px;
font-weight: bold;
}

.copy-btn {
background: #22c55e;
border: none;
padding: 12px;
border-radius: 8px;
font-weight: bold;
cursor: pointer;
color: white;
width: 100%;
margin-top: 10px;
}

.option-btn {
margin-top: 14px;
padding: 16px;
border-radius: 14px;
width: 100%;
font-weight: bold;
border: none;
cursor: pointer;
color: white;
text-decoration: none;
font-size: 16px;
display: flex;
justify-content: center;
align-items: center;
gap: 10px;
transition: 0.2s ease;
}

.option-btn:hover {
transform: scale(1.03);
}

.call-btn {
background: linear-gradient(135deg, #22c55e, #16a34a);
}

.text-btn {
background: linear-gradient(135deg, #6b7280, #4b5563);
}

.payment-note {
font-size: 12px;
margin-top: 12px;
opacity: 0.8;
line-height: 1.4;
}

@media(max-width:480px){
body {
padding: 10px;
}

.container {
width: 390px;
max-width: 100%;
transform: scale(0.86);
}

.modal-content {
width: 390px;
max-width: 92%;
transform: scale(0.86);
}

@keyframes pop {
from { transform: scale(0.78); opacity: 0; }
to { transform: scale(0.86); opacity: 1; }
}
}


/* ===== GENERATED PORTAL BLUE SKIN ===== */
body {
background: linear-gradient(-45deg, #020617, #081225, #0f172a, #0b1120) !important;
background-size: 400% 400% !important;
}

.container,
.modal-content {
background: rgba(15,23,42,0.82) !important;
border: 1px solid rgba(56,189,248,0.20) !important;
box-shadow: 0 22px 55px rgba(0,0,0,0.45) !important;
}

.notice-box {
background: rgba(37,99,235,0.14) !important;
border: 1px solid rgba(56,189,248,0.18) !important;
color: #cbd5e1 !important;
}

.pay-now,
.copy-btn,
.call-btn {
background: linear-gradient(135deg, #2563eb, #38bdf8) !important;
color: #ffffff !important;
}

.contact-btn,
.text-btn {
background: #0f172a !important;
color: #e5e7eb !important;
border: 1px solid rgba(56,189,248,0.20) !important;
}

.number-box {
background: rgba(37,99,235,0.14) !important;
border: 1px solid rgba(56,189,248,0.18) !important;
}

h2,
.footer,
.payment-note {
color: #cbd5e1 !important;
}

/* ===== FIVE PROFESSIONAL PORTAL THEMES ===== */
:root {
--page-1:#050816;
--page-2:#111827;
--surface:rgba(15,23,42,.90);
--surface-solid:#0f172a;
--surface-soft:rgba(255,255,255,.065);
--border:rgba(148,163,184,.22);
--text:#f8fafc;
--muted:#cbd5e1;
--accent:#8b5cf6;
--accent-2:#22d3ee;
--shadow:rgba(0,0,0,.48);
--glow-1:rgba(34,211,238,.22);
--glow-2:rgba(139,92,246,.20);
--button-shadow:rgba(139,92,246,.28);
}

html[data-portal-theme="clean"] {
--page-1:#eef4ff;
--page-2:#ffffff;
--surface:rgba(255,255,255,.94);
--surface-solid:#ffffff;
--surface-soft:#f1f5f9;
--border:#dbe4f0;
--text:#0f172a;
--muted:#475569;
--accent:#2563eb;
--accent-2:#38bdf8;
--shadow:rgba(15,23,42,.14);
--glow-1:rgba(56,189,248,.18);
--glow-2:rgba(37,99,235,.13);
--button-shadow:rgba(37,99,235,.24);
color-scheme:light;
}

html[data-portal-theme="ocean"] {
--page-1:#031525;
--page-2:#063b5c;
--surface:rgba(5,34,55,.91);
--surface-solid:#082f49;
--surface-soft:rgba(14,165,233,.12);
--border:rgba(103,232,249,.25);
--text:#ecfeff;
--muted:#bae6fd;
--accent:#0284c7;
--accent-2:#22d3ee;
--shadow:rgba(2,12,27,.50);
--glow-1:rgba(34,211,238,.22);
--glow-2:rgba(2,132,199,.20);
--button-shadow:rgba(2,132,199,.28);
}

html[data-portal-theme="emerald"] {
--page-1:#021b17;
--page-2:#064e3b;
--surface:rgba(3,45,36,.91);
--surface-solid:#064e3b;
--surface-soft:rgba(16,185,129,.12);
--border:rgba(110,231,183,.24);
--text:#ecfdf5;
--muted:#a7f3d0;
--accent:#059669;
--accent-2:#34d399;
--shadow:rgba(1,20,16,.52);
--glow-1:rgba(52,211,153,.22);
--glow-2:rgba(5,150,105,.20);
--button-shadow:rgba(5,150,105,.28);
}

html[data-portal-theme="sunset"] {
--page-1:#210b24;
--page-2:#7c2d12;
--surface:rgba(48,16,39,.91);
--surface-solid:#3b122f;
--surface-soft:rgba(249,115,22,.13);
--border:rgba(253,186,116,.25);
--text:#fff7ed;
--muted:#fed7aa;
--accent:#ea580c;
--accent-2:#ec4899;
--shadow:rgba(24,5,19,.52);
--glow-1:rgba(236,72,153,.20);
--glow-2:rgba(234,88,12,.22);
--button-shadow:rgba(234,88,12,.28);
}

html[data-portal-theme="royal"] {
--page-1:#0e0923;
--page-2:#312e81;
--surface:rgba(30,20,67,.92);
--surface-solid:#24184f;
--surface-soft:rgba(139,92,246,.13);
--border:rgba(196,181,253,.25);
--text:#f5f3ff;
--muted:#ddd6fe;
--accent:#7c3aed;
--accent-2:#a78bfa;
--shadow:rgba(8,4,25,.54);
--glow-1:rgba(167,139,250,.22);
--glow-2:rgba(124,58,237,.22);
--button-shadow:rgba(124,58,237,.30);
}

html[data-portal-theme="ruby"] {
--page-1:#21060d;
--page-2:#881337;
--surface:rgba(55,11,25,.92);
--surface-solid:#4c0d22;
--surface-soft:rgba(225,29,72,.13);
--border:rgba(253,164,175,.25);
--text:#fff1f2;
--muted:#fecdd3;
--accent:#be123c;
--accent-2:#fb7185;
--shadow:rgba(28,3,10,.54);
--glow-1:rgba(251,113,133,.21);
--glow-2:rgba(190,18,60,.23);
--button-shadow:rgba(190,18,60,.30);
}

html[data-portal-theme="gold"] {
--page-1:#1c1403;
--page-2:#713f12;
--surface:rgba(52,36,5,.92);
--surface-solid:#422d06;
--surface-soft:rgba(245,158,11,.13);
--border:rgba(253,230,138,.27);
--text:#fffbeb;
--muted:#fde68a;
--accent:#d97706;
--accent-2:#fbbf24;
--shadow:rgba(26,17,2,.54);
--glow-1:rgba(251,191,36,.21);
--glow-2:rgba(217,119,6,.23);
--button-shadow:rgba(217,119,6,.30);
}

html[data-portal-theme="graphite"] {
--page-1:#07090d;
--page-2:#1f2937;
--surface:rgba(20,25,33,.94);
--surface-solid:#171c24;
--surface-soft:rgba(148,163,184,.11);
--border:rgba(203,213,225,.22);
--text:#f9fafb;
--muted:#cbd5e1;
--accent:#475569;
--accent-2:#94a3b8;
--shadow:rgba(0,0,0,.56);
--glow-1:rgba(148,163,184,.16);
--glow-2:rgba(71,85,105,.20);
--button-shadow:rgba(71,85,105,.30);
}

html[data-portal-theme="rose"] {
--page-1:#26091c;
--page-2:#831843;
--surface:rgba(61,13,43,.92);
--surface-solid:#4a1034;
--surface-soft:rgba(219,39,119,.13);
--border:rgba(249,168,212,.25);
--text:#fdf2f8;
--muted:#fbcfe8;
--accent:#be185d;
--accent-2:#f472b6;
--shadow:rgba(31,4,21,.54);
--glow-1:rgba(244,114,182,.21);
--glow-2:rgba(190,24,93,.22);
--button-shadow:rgba(190,24,93,.30);
}

body {
min-height:100svh !important;
height:auto !important;
padding:24px 14px !important;
overflow:auto !important;
background:
radial-gradient(circle at 12% 12%, var(--glow-1), transparent 30%),
radial-gradient(circle at 88% 88%, var(--glow-2), transparent 32%),
linear-gradient(145deg,var(--page-1),var(--page-2)) !important;
color:var(--text) !important;
animation:none !important;
}

.container {
width:min(390px,100%) !important;
padding:28px !important;
border-radius:24px !important;
background:var(--surface) !important;
border:1px solid var(--border) !important;
box-shadow:0 26px 70px var(--shadow) !important;
backdrop-filter:blur(22px) !important;
transform:none !important;
}

.logo img {
width:min(250px,100%) !important;
max-height:110px;
object-fit:contain;
margin-bottom:18px !important;
}

h2 {
font-size:20px !important;
line-height:1.25;
color:var(--text) !important;
margin-bottom:12px !important;
}

.notice-box {
padding:14px !important;
border-radius:14px !important;
background:var(--surface-soft) !important;
border:1px solid var(--border) !important;
color:var(--muted) !important;
line-height:1.45;
}

.pay-now,
.copy-btn,
.call-btn {
background:linear-gradient(135deg,var(--accent),var(--accent-2)) !important;
box-shadow:0 10px 24px var(--button-shadow) !important;
}

.pay-now,
.contact-btn,
.option-btn,
.copy-btn,
.payment-group button {
min-height:48px;
border-radius:13px !important;
transition:transform .18s ease, filter .18s ease !important;
}

.pay-now:hover,
.contact-btn:hover,
.option-btn:hover,
.copy-btn:hover,
.payment-group button:hover {
transform:translateY(-1px) !important;
filter:brightness(1.06);
}

.contact-btn,
.text-btn {
background:var(--surface-solid) !important;
color:var(--text) !important;
border:1px solid var(--border) !important;
}

.payment-group {
gap:8px !important;
}

.payment-group button {
flex:1 1 46% !important;
}

.modal {
padding:16px;
background:rgba(2,6,23,.68) !important;
}

.modal-content {
width:min(390px,100%) !important;
max-height:92svh;
overflow:auto;
padding:28px !important;
border-radius:22px !important;
background:var(--surface-solid) !important;
border:1px solid var(--border) !important;
color:var(--text) !important;
box-shadow:0 24px 70px var(--shadow) !important;
transform:none !important;
}

@keyframes pop {
from { transform:translateY(8px) scale(.98); opacity:0; }
to { transform:translateY(0) scale(1); opacity:1; }
}

.number-box {
background:var(--surface-soft) !important;
border:1px solid var(--border) !important;
color:var(--text) !important;
}

.footer,
.payment-note {
color:var(--muted) !important;
}

html[data-portal-theme="clean"] .contact-btn,
html[data-portal-theme="clean"] .text-btn {
background:#f8fafc !important;
}

@media(max-width:480px){
body{padding:14px 10px !important;align-items:flex-start !important}
.container{padding:22px 18px !important;border-radius:20px !important}
.modal-content{padding:24px 18px !important}
}

/* ===== OPTIONAL FLAT / 2D STYLE ===== */
html[data-portal-style="flat"] body {
background:var(--page-1) !important;
}

html[data-portal-style="flat"] .container {
background:var(--surface-solid) !important;
border:2px solid var(--border) !important;
border-radius:14px !important;
box-shadow:none !important;
backdrop-filter:none !important;
}

html[data-portal-style="flat"] .notice-box,
html[data-portal-style="flat"] .number-box {
background:var(--surface-soft) !important;
border-radius:8px !important;
box-shadow:none !important;
}

html[data-portal-style="flat"] .pay-now,
html[data-portal-style="flat"] .copy-btn,
html[data-portal-style="flat"] .call-btn {
background:var(--accent) !important;
box-shadow:none !important;
}

html[data-portal-style="flat"] .contact-btn,
html[data-portal-style="flat"] .text-btn,
html[data-portal-style="flat"] .option-btn,
html[data-portal-style="flat"] .copy-btn,
html[data-portal-style="flat"] .pay-now,
html[data-portal-style="flat"] .payment-group button {
border-radius:7px !important;
box-shadow:none !important;
transform:none !important;
}

html[data-portal-style="flat"] .payment-group button:hover,
html[data-portal-style="flat"] .contact-btn:hover,
html[data-portal-style="flat"] .option-btn:hover,
html[data-portal-style="flat"] .copy-btn:hover,
html[data-portal-style="flat"] .pay-now:hover {
transform:none !important;
filter:brightness(.94);
}

html[data-portal-style="flat"] .modal {
backdrop-filter:none !important;
}

html[data-portal-style="flat"] .modal-content {
border:2px solid var(--border) !important;
border-radius:12px !important;
box-shadow:none !important;
animation:none !important;
}

html[data-portal-style="flat"] .gcash-btn{background:#0879e8 !important}
html[data-portal-style="flat"] .maya-btn{background:#079447 !important}
html[data-portal-style="flat"] .bpi-btn{background:#9f171c !important}
html[data-portal-style="flat"] .gotyme-btn{background:#00bcca !important;color:#071827 !important}
html[data-portal-style="flat"] .maribank-btn{background:#e85d0b !important}
html[data-portal-style="flat"] .bdo-btn{background:#07549d !important}

</style>
</head>

<body data-theme="dark" data-portal-theme="clean" data-portal-style="glass">

<div class="container">
<div class="logo">
<img src="logo.gif" alt="Logo">
</div>

<h2>Service Temporarily Restricted</h2>

<div class="notice-box">
Your internet service has been temporarily suspended due to an unpaid balance.
Please settle your account to restore access.
</div>


<div class="pay-now" onclick="togglePayments()">💳 PAY NOW</div>
<div class="payment-group" id="paymentOptions"></div>


<div class="contact-btn" onclick="openContact()">💬 Contact Support</div>

<div class="footer">© 2026 YOUR BRAND | Secure Access Portal</div>
</div>

<div id="qrModal" class="modal" onclick="closeAll()">
<div class="modal-content" onclick="event.stopPropagation()">
<span class="close-btn" onclick="closeAll()">✖</span>
<h3 id="qrTitle">Scan to Pay</h3>
<img id="qrImage">
<div id="payName">XXXXXXXXXXXXX</div>
<div class="number-box" id="payNumber">XXXXXXXXXXXXX</div>
<button class="copy-btn" onclick="copyQRNumber(this)">COPY NUMBER</button>

<div class="payment-note">
Once the payment has been sent, kindly provide the account name and
reference number through Messenger or SMS.
<br><br>Facebook: FACEBOOK PAGE
<br>Phone: 0912-345-6789
</div>
</div>
</div>

<div id="contactModal" class="modal" onclick="closeAll()">
<div class="modal-content" onclick="event.stopPropagation()">
<span class="close-btn" onclick="closeAll()">✖</span>
<h3>Contact Support</h3>

<a href="tel:+639123456789" class="option-btn call-btn">
📞 Call Now
</a>

<button type="button" class="option-btn text-btn" onclick="copyContactNumber(this)">
📋 Copy Number
</button>
</div>
</div>

<script>
const payments = [{"id":"gcash1","type":"gcash","label":"GCash","title":"Scan to Pay (GCash)","image":"gcash.png","name":"GCASH NAME","number":"0912-345-6789","copy":"09123456789"},{"id":"maya1","type":"maya","label":"Maya","title":"Scan to Pay (Maya)","image":"maya.png","name":"MAYA NAME","number":"0912-345-6789","copy":"09123456789"}];
let currentCopyNumber = "";

function escapeHTML(text){
return String(text)
.replaceAll("&","&amp;")
.replaceAll("<","&lt;")
.replaceAll(">","&gt;")
.replaceAll('"',"&quot;")
.replaceAll("'","&#039;");
}

function renderPaymentButtons(){
const box = document.getElementById("paymentOptions");
if(!box) return;

box.innerHTML = payments.map(function(p){
return '<button class="' + p.type + '-btn" onclick="openQR(\'' + p.id + '\')">' + escapeHTML(p.label) + '</button>';
}).join("");
}

function togglePayments() {
const options = document.getElementById("paymentOptions");
if(options){
options.style.display = (options.style.display === "flex") ? "none" : "flex";
}
}

function openQR(id) {
const p = payments.find(function(item){
return item.id === id;
});

if(!p) return;

closeAll();

document.getElementById("qrImage").src = p.image;
document.getElementById("qrTitle").innerText = p.title;
document.getElementById("payName").innerText = p.name;
document.getElementById("payNumber").innerText = p.number;

currentCopyNumber = p.copy;

document.getElementById("qrModal").style.display = "flex";
}

function openContact() {
closeAll();
document.getElementById("contactModal").style.display = "flex";
}

function closeAll() {
document.getElementById("qrModal").style.display = "none";
document.getElementById("contactModal").style.display = "none";
}

function fallbackCopy(text) {
const textarea = document.createElement("textarea");
textarea.value = text;
textarea.style.position = "fixed";
textarea.style.opacity = "0";
document.body.appendChild(textarea);
textarea.focus();
textarea.select();

try {
document.execCommand("copy");
} catch (err) {
alert("Copy failed. Please copy manually.");
}

document.body.removeChild(textarea);
}

function copyQRNumber(button) {
const number = currentCopyNumber || document.getElementById("payNumber").innerText.replace(/[^0-9]/g, "");

if (navigator.clipboard && window.isSecureContext) {
navigator.clipboard.writeText(number);
} else {
fallbackCopy(number);
}

button.innerText = "✓ COPIED";
setTimeout(() => button.innerText = "COPY NUMBER", 1500);
}

function copyContactNumber(button) {
const number = "09123456789";

if (navigator.clipboard && window.isSecureContext) {
navigator.clipboard.writeText(number);
} else {
fallbackCopy(number);
}

button.innerText = "✓ COPIED";
setTimeout(() => button.innerText = "📋 Copy Number", 1500);
}

renderPaymentButtons();

document.addEventListener("click", function(){
let music = document.getElementById("bgMusic");
if(music){
music.play().catch(() => {});
}
}, { once:true });
</script>

<audio id="bgMusic" autoplay loop>
<source src="Audio1.mp3">
</audio>

</body>
</html>
