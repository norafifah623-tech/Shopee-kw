<!DOCTYPE html><html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Toko Online Mirip Shopee</title>
<style>
body { font-family: Arial; margin:0; background:#f5f5f5; }
header { background:#ff5722; color:white; padding:15px; display:flex; justify-content:space-between; align-items:center; }
.cart { background:yellow; padding:10px; border-radius:50%; cursor:pointer; }
.container { padding:20px; display:grid; grid-template-columns:repeat(auto-fill,minmax(200px,1fr)); gap:15px; }
.card { background:white; padding:10px; border-radius:10px; box-shadow:0 2px 5px rgba(0,0,0,0.1); }
.card img { width:100%; border-radius:10px; }
select, input { width:100%; margin-top:5px; padding:5px; }
button { margin-top:10px; width:100%; background:#ff5722; color:white; border:none; padding:10px; cursor:pointer; }
#cartModal { position:fixed; top:0; right:-400px; width:300px; height:100%; background:white; box-shadow:-2px 0 5px rgba(0,0,0,0.3); padding:20px; transition:0.3s; overflow:auto; }
#cartModal.active { right:0; }
</style>
</head>
<body><header>
<h2>Toko Saya</h2>
<div class="cart" onclick="toggleCart()">🛒 (<span id="cartCount">0</span>)</div>
</header><div class="container" id="products"></div><div id="cartModal">
<h3>Keranjang</h3>
<div id="cartItems"></div>
<h4>Total: Rp <span id="total">0</span></h4>
</div><script>
const products = [
 {name:"Baju Kaos Polos", price:50000, img:"https://via.placeholder.com/200"},
 {name:"Hoodie Premium", price:120000, img:"https://via.placeholder.com/200"},
 {name:"Kemeja Formal", price:90000, img:"https://via.placeholder.com/200"}
];

let cart = [];

function renderProducts(){
 const container = document.getElementById('products');
 products.forEach((p,i)=>{
 container.innerHTML += `
 <div class="card">
   <img src="${p.img}">
   <h4>${p.name}</h4>
   <p>Rp ${p.price}</p>
   <label>Ukuran:</label>
   <select id="size${i}">
     <option>S</option>
     <option>M</option>
     <option>L</option>
     <option>XL</option>
   </select>
   <label>Jumlah (pcs):</label>
   <input type="number" id="qty${i}" value="1" min="1">
   <button onclick="addToCart(${i})">Masukkan Keranjang</button>
 </div>`;
 });
}

function addToCart(i){
 const size = document.getElementById(`size${i}`).value;
 const qty = parseInt(document.getElementById(`qty${i}`).value);
 const product = products[i];
 cart.push({...product, size, qty});
 updateCart();
}

function updateCart(){
 document.getElementById('cartCount').innerText = cart.length;
 let items = '';
 let total = 0;
