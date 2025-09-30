[style.css](https://github.com/user-attachments/files/22608630/style.css)
body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; color: #333; }
header { background: #28a745; color: white; text-align: center; padding: 2rem; }
h1 { margin: 0; }
section { padding: 2rem; text-align: center; }
.pricing-grid { display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap; }
.card { background: white; padding: 1rem 2rem; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
.gallery { display: flex; justify-content: center; gap: 1rem; margin-top: 1rem; }
.gallery img { width: 300px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
footer { background: #222; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
[script.js](https://github.com/user-attachments/files/22608633/script.js)
// Future interactivity can go here
console.log("Baka Junk Removal website loaded");[index.html](https://github.com/user-attachments/files/22608634/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baka Junk Removal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Baka Junk Removal</h1>
        <p>Fast • Reliable • Affordable</p>
    </header>

    <section id="pricing">
        <h2>Simple, Transparent Pricing</h2>
        <p>Pricing based on our 16ft / 32 cubic yard truck. Final quote depends on volume, weight, and access.</p>
        <div class="pricing-grid">
            <div class="card"><h3>Single Item</h3><p>$95+</p></div>
            <div class="card"><h3>1/4 Truck (8 cu yd)</h3><p>$349–$399</p></div>
            <div class="card"><h3>1/2 Truck (16 cu yd)</h3><p>$499–$649</p></div>
            <div class="card"><h3>3/4 Truck (24 cu yd)</h3><p>$649–$849</p></div>
            <div class="card"><h3>Full Truck (32 cu yd)</h3><p>$899–$1,099</p></div>
        </div>
    </section>

    <section id="gallery">
        <h2>Before & After</h2>
        <div class="gallery">
            <img src="images/before.jpg" alt="Before cleanup">
            <img src="images/after.jpg" alt="After cleanup">
        </div>
    </section>

    <footer>
        <p>Call us today: (747) 240-2903 | bakamoving@gmail.com</p>
    </footer>
</body>
</html>
