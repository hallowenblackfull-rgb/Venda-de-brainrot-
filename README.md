<!DOCTYPE html><html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Brainrot Store</title>
<style>
body{font-family:Arial;margin:0;background:#0f172a;color:white}
header{background:#111827;padding:20px;text-align:center}
.logo{font-size:32px;font-weight:bold;color:#ef4444}
.sub{font-size:14px;color:#cbd5f5}
.container{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;padding:30px}
.card{background:#1f2937;border-radius:12px;padding:20px;text-align:center}
.card img{width:100%;border-radius:10px}
.price{font-size:22px;color:#22c55e;margin:10px 0}
button{background:#ef4444;border:none;padding:10px 15px;border-radius:8px;color:white;font-size:16px;cursor:pointer}
.pay{background:#111827;padding:30px;text-align:center}
.pix, .cardpay{margin:10px 0;padding:10px;background:#1f2937;border-radius:8px}
footer{text-align:center;padding:20px;background:#020617;color:#94a3b8}
</style>
</head>
<body><header>
<div class="logo">BRAINROT STORE</div>
<div class="sub">Itens e Gamepasses Roblox</div>
</header><section class="container"><div class="card">
<img src="https://tr.rbxcdn.com/180DAY-9b4b7d5cfe7d9c1d9c9c5b5b/420/420/Image/Png/noFilter">
<h3>Brainrot Básico</h3>
<div class="price">R$10</div>
<button onclick="comprar('Brainrot Básico')">Comprar</button>
</div><div class="card">
<img src="https://tr.rbxcdn.com/180DAY-9b4b7d5cfe7d9c1d9c9c5b5b/420/420/Image/Png/noFilter">
<h3>Brainrot Pro</h3>
<div class="price">R$25</div>
<button onclick="comprar('Brainrot Pro')">Comprar</button>
</div><div class="card">
<img src="https://tr.rbxcdn.com/180DAY-9b4b7d5cfe7d9c1d9c9c5b5b/420/420/Image/Png/noFilter">
<h3>Brainrot Ultra</h3>
<div class="price">R$50</div>
<button onclick="comprar('Brainrot Ultra')">Comprar</button>
</div></section><section class="pay">
<h2>Pagamento</h2><div class="pix">
<h3>PIX</h3>
<p>Chave Pix: sua-chave-pix-aqui</p>
</div><div class="cardpay">
<h3>Cartão</h3>
<p>Aceitamos Visa, Mastercard e Elo.</p>
<p>Após clicar em comprar, você receberá o link de pagamento.</p>
</div></section><footer>
<p>© 2026 Brainrot Store - Roblox Itens</p>
</footer><script>
function comprar(produto){
let numero = "5599999999999";
let msg = "Olá, quero comprar: " + produto;
let url = "https://wa.me/
