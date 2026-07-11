// ===== Car Data =====
const cars = [
 {
 id: 1, name: "488 GTB", brand: "ferrari", brandFa: "فراری", fuel: "benzin", fuelFa: "بنزین",
 price: 3500000000, priceLabel: "۳.۵ میلیارد", year: 2022, km: 15000, power: 670, topSpeed: 330, color: "قرمز",
 image: "https://images.unsplash.com/photo-1592198084033-aade902d1aae?w=800",
 desc: "فراری ۴۸۸ GTB یکی از شاهکارهای ایتالیایی با موتور V8 توربوی ۳.۹ لیتری. شتاب ۰ تا ۱۰۰ در تنها ۳ ثانیه.",
 badge: "داغ"
 },
 {
 id: 2, name: "Huracan EVO", brand: "lamborghini", brandFa: "لامبورگینی", fuel: "benzin", fuelFa: "بنزین",
 price: 4200000000, priceLabel: "۴.۲ میلیارد", year: 2023, km: 8000, power: 640, topSpeed: 325, color: "زرد",
 image: "https://images.unsplash.com/photo-1621135802920-133df287f89c?w=800",
 desc: "لامبورگینی هوراکان EVO با طراحی خشن و موتور V10. صدای موتور بی‌نظیر این ماشین حس تهاجمی خاصی داره.",
 badge: "ویژه"
 },
 {
 id: 3, name: "911 Turbo S", brand: "porsche", brandFa: "پورشه", fuel: "benzin", fuelFa: "بنزین",
 price: 2800000000, priceLabel: "۲.۸ میلیارد", year: 2023, km: 12000, power: 650, topSpeed: 330, color: "نقره‌ای",
 image: "https://images.unsplash.com/photo-1611821064430-0d40291d0f0b?w=800",
 desc: "پورشه 911 Turbo S ترکیبی از لوکس و عملکرد. شتاب ۰ تا ۱۰۰ در ۲.۷ ثانیه با سیستم چهارچرخ محرک.",
 badge: ""
 },
 {
 id: 4, name: "M4 Competition", brand: "bmw", brandFa: "بی‌ام‌و", fuel: "hybrid", fuelFa: "هایبرید",
 price: 1800000000, priceLabel: "۱.۸ میلیارد", year: 2022, km: 20000, power: 510, topSpeed: 290, color: "آبی",
 image: "https://images.unsplash.com/photo-1555215695-3004980ad54e?w=800",
 desc: "بی‌ام‌و M4 کامپتیشن با موتور ۶ سیلندر توربو، تعلیق اسپرت و طراحی تهاجمی. انتخابی عالی برای عاشقان سرعت.",
 badge: "جدید"
 },
 {
 id: 5, name: "AMG GT 63 S", brand: "mercedes", brandFa: "مرسدس", fuel: "benzin", fuelFa: "بنزین",
 price: 3200000000, priceLabel: "۳.۲ میلیارد", year: 2023, km: 10000, power: 630, topSpeed: 315, color: "مشکی",
 image: "https://images.unsplash.com/photo-1605559424843-9e4c228bf1c2?w=800",
 desc: "مرسدس AMG GT 63 S با موتور V8 توربو و طراحی فوق‌لوکس. ترکیب بی‌نقصی از قدرت و ظرافت آلمانی.",
 badge: ""
 },
 {
 id: 6, name: "R8 V10", brand: "audi", brandFa: "آئودی", fuel: "benzin", fuelFa: "بنزین",
 price: 3000000000, priceLabel: "۳ میلیارد", year: 2022, km: 18000, power: 620, topSpeed: 331, color: "سبز",
 image: "https://images.unsplash.com/photo-1606664515524-ed2f786a0bd6?w=800",
 desc: "آئودی R8 V10 با موتور وسط و چهارچرخ محرک Quattro. یکی از آخرین سوپراسپرت‌های با موتور تنفسی طبیعی.",
 badge: ""
 },
 {
 id: 7, name: "SF90 Stradale", brand: "ferrari", brandFa: "فراری", fuel: "hybrid", fuelFa: "هایبرید",
 price: 5500000000, priceLabel: "۵.۵ میلیارد", year: 2023, km: 5000, power: 986, topSpeed: 340, color: "قرمز",
 image: "https://images.unsplash.com/photo-1583121274602-3e2820c69888?w=800",
 desc: "فراری SF90 اولین ماشین پلاگین هیبرید فراری با ۹۸۶ اسب بخار قدرت. شتاب ۰ تا ۱۰۰ در ۲.۵ ثانیه.",
 badge: "داغ"
 },
 {
 id: 8, name: "Taycan Turbo", brand: "porsche", brandFa: "پورشه", fuel: "electric", fuelFa: "برقی",
 price: 2600000000, priceLabel: "۲.۶ میلیارد", year: 2023, km: 15000, power: 680, topSpeed: 260, color: "سفید",
 image: "https://images.unsplash.com/photo-1617788138017-80ad40651399?w=800",
 desc: "پورشه تایکان توربو اولین ماشین تمام برقی پورشه. شتاب فوق‌العاده و تکنولوژی شارژ سریع ۸۰۰ ولت.",
 badge: "برقی"
 },
 {
 id: 9, name: "RS e-tron GT", brand: "audi", brandFa: "آئودی", fuel: "electric", fuelFa: "برقی",
 price: 2400000000, priceLabel: "۲.۴ میلیارد", year: 2023, km: 12000, power: 637, topSpeed: 250, color: "قرمز",
 image: "https://images.unsplash.com/photo-1617469767053-d3b523a0b982?w=800",
 desc: "آئودی RS e-tron GT اولین ماشین تمام برقی RS آئودی. طراحی فوق‌العاده و عملکرد برقی خیره‌کننده.",
 badge: "برقی"
 },
 {
 id: 10, name: "Aventador SVJ", brand: "lamborghini", brandFa: "لامبورگینی", fuel: "benzin", fuelFa: "بنزین",
 price: 4800000000, priceLabel: "۴.۸ میلیارد", year: 2022, km: 6000, power: 770, topSpeed: 350, color: "نارنجی",
 image: "https://images.unsplash.com/photo-1544636129-1a3f1c6f6e0f?w=800",
 desc: "لامبورگینی آونتادور SVJ با موتور V12 تنفسی طبیعی و آیرودینامیک فعال. رکورد دار نوربرگرینگ.",
 badge: "ویژه"
 },
 {
 id: 11, name: "M5 CS", brand: "bmw", brandFa: "بی‌ام‌و", fuel: "benzin", fuelFa: "بنزین",
 price: 2200000000, priceLabel: "۲.۲ میلیارد", year: 2022, km: 14000, power: 627, topSpeed: 305, color: "سفید",
 image: "https://images.unsplash.com/photo-1556189250-72ba954cfc2b?w=800",
 desc: "بی‌ام‌و M5 CS سبک‌ترین و قدرتمندترین M5 تاریخ. صندلی‌های چهار نفره با عملکرد سوپراسپرت.",
 badge: ""
 },
 {
 id: 12, name: "AMG GTR", brand: "mercedes", brandFa: "مرسدس", fuel: "benzin", fuelFa: "بنزین",
 price: 3600000000, priceLabel: "۳.۶ میلیارد", year: 2022, km: 9000, power: 585, topSpeed: 318, color: "سبز",
 image: "https://images.unsplash.com/photo-1618843479313-40f8afb4b4d8?w=800",
 desc: "مرسدس AMG GT R با آیرودینامیک فعال و تعلیق اسپرت. ماشین مسابقه‌ای مجاز برای خیابان.",
 badge: ""
 }
];

// ===== State =====
let favorites = new Set();
let filteredCars = [...cars];

// ===== Render Cars =====
const carsGrid = document.getElementById('carsGrid');
const noResult = document.getElementById('noResult');

function formatNumber(n) {
 return n.toLocaleString('fa-IR');
}

function renderCars(list) {
 if (list.length === 0) {
 carsGrid.innerHTML = '';
 noResult.style.display = 'block';
 return;
 }
 noResult.style.display = 'none';
 carsGrid.innerHTML = list.map(car => `
 <div class="car-card" data-id="${car.id}">
 <div class="car-image">
 <img src="${car.image}" alt="${car.name}" loading="lazy" onerror="this.src='https://via.placeholder.com/800x400/1a1a24/ff3d00?text=Car'">
 ${car.badge? `<span class="car-badge">${car.badge}</span>`: ''}
 <button class="car-fav ${favorites.has(car.id)? 'active': ''}" data-fav="${car.id}">
 <i class="fa-solid fa-heart"></i>
 </button>
 </div>
 <div class="car-info">
 <h3 class="car-name">${car.name}</h3>
 <p class="car-brand">${car.brandFa}</p>
 <div class="car-specs">
 <span class="car-spec"><i class="fa-solid fa-calendar"></i> ${formatNumber(car.year)}</span>
 <span class="car-spec"><i class="fa-solid fa-road"></i> ${formatNumber(car.km)} km</span>
 <span class="car-spec"><i class="fa-solid fa-bolt"></i> ${formatNumber(car.power)} hp</span>
 </div>
 <div class="car-price">
 <div>
 <div class="price-amount">${car.priceLabel}</div>
 <div class="price-label">تومان</div>
 </div>
 <button class="btn-details" data-detail="${car.id}">جزئیات</button>
 </div>
 </div>
 </div>
 `).join('');

 // Bind events
 document.querySelectorAll('.car-card').forEach(card => {
 card.addEventListener('click', (e) => {
 if (!e.target.closest('.car-fav') &&!e.target.closest('.btn-details')) {
 const id = parseInt(card.dataset.id);
 openModal(id);
 }
 });
 });
 document.querySelectorAll('.car-fav').forEach(btn => {
 btn.addEventListener('click', (e) => {
 e.stopPropagation();
 toggleFav(parseInt(btn.dataset.fav));
 });
 });
 document.querySelectorAll('.btn-details').forEach(btn => {
 btn.addEventListener('click', (e) => {
 e.stopPropagation();
 openModal(parseInt(btn.dataset.detail));
 });
 });
}

// ===== Favorites =====
function toggleFav(id) {
 if (favorites.has(id)) {
 favorites.delete(id);
 } else {
 favorites.add(id);
 }
 updateFavCount();
 renderCars(filteredCars);
}
function updateFavCount() {
 document.getElementById('favCount').textContent = formatNumber(favorites.size);
}

// ===== Filter =====
function applyFilters() {
 const brand = document.getElementById('brandFilter').value;
 const fuel = document.getElementById('fuelFilter').value;
 const price = document.getElementById('priceFilter').value;
 const search = document.getElementById('searchInput').value.toLowerCase();

 filteredCars = cars.filter(car => {
 let match = true;
 if (brand!== 'all' && car.brand!== brand) match = false;
 if (fuel!== 'all' && car.fuel!== fuel) match = false;
 if (price!== 'all' && car.price > parseInt(price) * 10000) match = false;
 if (search &&!car.name.toLowerCase().includes(search) &&!car.brandFa.includes(search)) match = false;
 return match;
 });
 renderCars(filteredCars);
}

document.getElementById('brandFilter').addEventListener('change', applyFilters);
document.getElementById('fuelFilter').addEventListener('change', applyFilters);
document.getElementById('priceFilter').addEventListener('change', applyFilters);
document.getElementById('searchInput').addEventListener('input', applyFilters);
document.getElementById('resetFilter').addEventListener('click', () => {
 document.getElementById('brandFilter').value = 'all';
 document.getElementById('fuelFilter').value = 'all';
 document.getElementById('priceFilter').value = 'all';
 document.getElementById('searchInput').value = '';
 applyFilters();
});

// ===== Modal =====
function openModal(id) {
 const car = cars.find(c => c.id === id);
 if (!car) return;
 document.getElementById('modalBody').innerHTML = `
 <div class="modal-image">
 <img src="${car.image}" alt="${car.name}" onerror="this.src='https://via.placeholder.com/800x400/1a1a24/ff3d00?text=Car'">
 </div>
 <div class="modal-content">
 <h2 class="modal-title">${car.name}</h2>
 <p class="modal-brand">${car.brandFa} • ${formatNumber(car.year)}</p>
 <div class="modal-specs">
 <div class="modal-spec-item">
 <i class="fa-solid fa-bolt"></i>
 <div class="spec-val">${formatNumber(car.power)} hp</div>
 <div class="spec-key">قدرت موتور</div>
 </div>
 <div class="modal-spec-item">
 <i class="fa-solid fa-gauge-high"></i>
 <div class="spec-val">${formatNumber(car.topSpeed)} km/h</div>
 <div class="spec-key">سرعت نهایی</div>
 </div>
 <div class="modal-spec-item">
 <i class="fa-solid fa-road"></i>
 <div class="spec-val">${formatNumber(car.km)} km</div>
 <div class="spec-key">کارکرد</div>
 </div>
 <div class="modal-spec-item">
 <i class="fa-solid fa-gas-pump"></i>
 <div class="spec-val">${car.fuelFa}</div>
 <div class="spec-key">نوع سوخت</div>
 </div>
 <div class="modal-spec-item">
 <i class="fa-solid fa-palette"></i>
 <div class="spec-val">${car.color}</div>
 <div class="spec-key">رنگ</div>
 </div>
 <div class="modal-spec-item">
 <i class="fa-solid fa-calendar"></i>
 <div class="spec-val">${formatNumber(car.year)}</div>
 <div class="spec-key">سال تولید</div>
 </div>
 </div>
 <p class="modal-desc">${car.desc}</p>
 <div class="modal-footer">
 <div>
 <div class="modal-price">${car.priceLabel}</div>
 <div class="price-label">تومان</div>
 </div>
 <div style="display:flex;gap:10px;">
 <button class="btn-ghost" onclick="toggleFavModal(${car.id})">
 <i class="fa-solid fa-heart"></i> علاقه‌مندی
 </button>
 <button class="btn-primary">
 <i class="fa-solid fa-phone"></i> تماس با فروشنده
 </button>
 </div>
 </div>
 </div>
 `;
 document.getElementById('modalOverlay').classList.add('active');
 document.body.style.overflow = 'hidden';
}

function toggleFavModal(id) {
 toggleFav(id);
 openModal(id);
}

document.getElementById('modalClose').addEventListener('click', closeModal);
document.getElementById('modalOverlay').addEventListener('click', (e) => {
 if (e.target === e.currentTarget) closeModal();
});
function closeModal() {
 document.getElementById('modalOverlay').classList.remove('active');
 document.body.style.overflow = '';
}
document.addEventListener('keydown', (e) => {
 if (e.key === 'Escape') closeModal();
});

// ===== Scroll =====
function scrollToCars() {
 document.getElementById('cars').scrollIntoView({ behavior: 'smooth' });
}

// Navbar scroll effect
window.addEventListener('scroll', () => {
 const nav = document.querySelector('.navbar');
 nav.classList.toggle('scrolled', window.scrollY > 50);
});

// Hamburger
document.getElementById('hamburger').addEventListener('click', () => {
 document.querySelector('.nav-links').classList.toggle('active');
});

// ===== Counter Animation =====
function animateCounter(el) {
 const target = parseInt(el.dataset.target);
 const duration = 2000;
 const step = target / (duration / 16);
 let current = 0;
 const timer = setInterval(() => {
 current += step;
 if (current >= target) {
 current = target;
 clearInterval(timer);
 }
 el.textContent = formatNumber(Math.floor(current));
 }, 16);
}

// Intersection Observer for counters
const counterObserver = new IntersectionObserver((entries) => {
 entries.forEach(entry => {
 if (entry.isIntersecting) {
 animateCounter(entry.target);
 counterObserver.unobserve(entry.target);
 }
 });
}, { threshold: 0.5 });

document.querySelectorAll('.counter').forEach(el => counterObserver.observe(el));

// ===== Init =====
renderCars(filteredCars);
