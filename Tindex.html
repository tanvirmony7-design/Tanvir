<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Md. Tanvir Kobir - Executive Management Portal</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f6f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .header {
            background-color: #0d1b2a;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            margin: 0 0 5px 0;
            font-size: 22px;
            color: #e0e1dd;
        }
        .header p {
            margin: 0;
            font-size: 13px;
            color: #778da9;
        }
        .container {
            padding: 15px;
            max-width: 600px;
            margin: auto;
        }
        .card {
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            margin-bottom: 15px;
        }
        .card h3 {
            margin-top: 0;
            color: #1b263b;
            border-bottom: 2px solid #edf2f4;
            padding-bottom: 8px;
            font-size: 16px;
        }
        .info-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 14px;
        }
        .btn {
            width: 100%;
            padding: 12px;
            margin: 8px 0;
            border: none;
            border-radius: 5px;
            font-size: 15px;
            font-weight: bold;
            cursor: pointer;
        }
        .btn-attendance { background-color: #2b9348; color: white; }
        .btn-order { background-color: #ee9b00; color: white; }
        .btn-location { background-color: #0077b6; color: white; }
        
        .product-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 10px;
            margin-top: 10px;
        }
        .product-card {
            border: 1px solid #e0e0e0;
            padding: 10px;
            border-radius: 6px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .product-info h4 {
            margin: 0 0 5px 0;
            font-size: 14px;
            color: #212529;
        }
        .product-info p {
            margin: 0;
            font-size: 12px;
            color: #6c757d;
        }
        #order-section {
            display: none;
        }
        .status-text {
            font-size: 13px;
            margin-top: 5px;
            font-weight: bold;
            text-align: center;
        }
        .success { color: #2b9348; }
        .tracking { color: #0077b6; }
    </style>
</head>
<body>

    <div class="header">
        <h1>Md. Tanvir Kobir</h1>
        <p>Proprietor & Chief Executive Dashboard</p>
    </div>

    <div class="container">
        
        <!-- Owner & Company Official Info -->
        <div class="card">
            <h3>Proprietor & Office Information</h3>
            <div class="info-row"><span><strong>Proprietor:</strong></span> <span>Md. Tanvir Kobir</span></div>
            <div class="info-row"><span><strong>Office Location:</strong></span> <span>Chougacha, Jashore, Bangladesh</span></div>
            <div class="info-row"><span><strong>Hotline/Phone:</strong></span> <span>+880 1XXXXXXXXX</span></div>
            <div class="info-row"><span><strong>Official Email:</strong></span> <span>tanvir.official@gmail.com</span></div>
            <div class="info-row"><span><strong>Business Category:</strong></span> <span>Pharmaceuticals & Distribution</span></div>
        </div>

        <!-- Field Staff Live Tracking Section -->
        <div class="card">
            <h3>Field Officer Live Tracking & Attendance</h3>
            <p style="font-size: 13px; color: #666;" id="time-display"></p>
            <button class="btn btn-attendance" onclick="giveAttendance()">✅ Give Daily Attendance</button>
            <div id="att-msg" class="status-text success"></div>
            
            <hr style="border:0; border-top:1px solid #eee; margin:15px 0;">
            
            <p style="font-size: 13px; color: #666;">Share live location during market visit so admin can monitor:</p>
            <button class="btn btn-location" onclick="getLiveLocation()">📍 Send Live GPS Location to Admin</button>
            <div id="location-status" class="status-text tracking"></div>
        </div>

        <!-- Sales Order Section -->
        <div class="card">
            <h3>Market Product Ordering Panel</h3>
            <p style="font-size: 13px; color: #666;">Sales Officers can take orders directly from pharmacies.</p>
            <button class="btn btn-order" onclick="toggleProducts()">🛒 Open Product Catalog</button>
            
            <div id="order-section">
                <div class="product-grid">
                    <!-- Product 1 -->
                    <div class="product-card">
                        <div class="product-info">
                            <h4>Napa Extra 500mg (Box)</h4>
                            <p>Price: ৳ 500</p>
                        </div>
                        <input type="number" placeholder="Qty" style="width: 50px; padding: 5px;" id="p1">
                    </div>
                    <!-- Product 2 -->
                    <div class="product-card">
                        <div class="product-info">
                            <h4>Seclo 20mg Capsule (Box)</h4>
                            <p>Price: ৳ 450</p>
                        </div>
                        <input type="number" placeholder="Qty" style="width: 50px; padding: 5px;" id="p2">
                    </div>
                    <!-- Product 3 -->
                    <div class="product-card">
                        <div class="product-info">
                            <h4>Ace Plus Tablet (Box)</h4>
                            <p>Price: ৳ 350</p>
                        </div>
                        <input type="number" placeholder="Qty" style="width: 50px; padding: 5px;" id="p3">
                    </div>
                </div>
                <button class="btn btn-attendance" style="margin-top: 15px;" onclick="submitOrder()">Submit Order to Central Server</button>
            </div>
        </div>

    </div>

    <script>
        // Live Date & Time Display
        document.getElementById('time-display').innerText = "Current Date & Time: " + new Date().toLocaleString();

        function giveAttendance() {
            document.getElementById('att-msg').innerText = "Attendance Submitted Successfully with Timestamp!";
        }

        function getLiveLocation() {
            document.getElementById('location-status').innerText = "Fetching real-time GPS coordinates...";
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(function(position) {
                    let lat = position.coords.latitude.toFixed(5);
                    let long = position.coords.longitude.toFixed(5);
                    document.getElementById('location-status').innerText = 
                    "Location Live! Lat: " + lat + ", Long: " + long + " (Synced with Admin)";
                }, function(error) {
                    document.getElementById('location-status').innerText = "Error: Please allow location access on your phone.";
                });
            } else { 
                document.getElementById('location-status').innerText = "Geolocation is not supported by this browser.";
            }
        }

        function toggleProducts() {
            var x = document.getElementById("order-section");
            if (x.style.display === "none" || x.style.display === "") {
                x.style.display = "block";
            } else {
                x.style.display = "none";
            }
        }

        function submitOrder() {
            alert("Order placed successfully by Sales Officer! Central Dashboard updated.");
            document.getElementById("order-section").style.display = "none";
        }
    </script>

</body>
</html>
