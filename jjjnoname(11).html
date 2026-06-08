<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RentCar - অনলাইন গাড়ি বুকিং</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f4f4f9; padding: 20px; }
        .container { background: white; max-width: 500px; margin: 0 auto; padding: 25px; border-radius: 8px; box-shadow: 0 0 15px rgba(0,0,0,0.1); }
        h2, h3 { text-align: center; color: #333; }
        .tab-box { display: flex; justify-content: space-around; margin-bottom: 20px; border-bottom: 2px solid #ddd; }
        .tab-btn { padding: 10px; cursor: pointer; font-weight: bold; color: #666; transition: 0.3s; }
        .tab-btn.active { color: #28a745; border-bottom: 3px solid #28a745; }
        .form-section { display: none; }
        .form-section.active { display: block; }
        input, select, button { width: 100%; padding: 12px; margin: 10px 0; box-sizing: border-box; border: 1px solid #ccc; border-radius: 4px; font-size: 15px; }
        button { background-color: #25D366; color: white; font-size: 16px; cursor: pointer; border: none; font-weight: bold; display: flex; align-items: center; justify-content: center; gap: 8px; }
        button:hover { background-color: #128C7E; }
        .owner-btn { background-color: #007bff; }
        .owner-btn:hover { background-color: #0056b3; }
        .referral-text { background: #e9ecef; padding: 10px; border-radius: 4px; text-align: center; font-weight: bold; margin-top: 15px; color: #495057; }
        .info-label { font-size: 14px; color: #555; margin-bottom: -5px; display: block; font-weight: bold; }
    </style>
</head>
<body>

<div class="container">
    <h2>RentCar - অনলাইন গাড়ি বুকিং</h2>
    
    <div class="tab-box">
        <span class="tab-btn active" id="tab1" onclick="switchForm('booking')">গাড়ি বুকিং (কাস্টমার)</span>
        <span class="tab-btn" id="tab2" onclick="switchForm('owner')">মালিকদের আইডি (পেইড)</span>
    </div>

    <!-- ১. কাস্টমার কার বুকিং ফর্ম (এখানে কাস্টমার নিজে সব টাইপ করবে) -->
    <div id="booking-section" class="form-section active">
        <h3>কোথায় যাবেন বুক করুন</h3>
        <form onsubmit="sendBookingToWhatsApp(event)">
            <input type="text" id="custName" placeholder="আপনার নাম" required>
            <input type="tel" id="custPhone" placeholder="মোবাইল নম্বর" required>
            
            <!-- পিকআপ লোকেশন (কোথা থেকে) -->
            <label class="info-label">কোথা থেকে (পিকআপ লোকেশন):</label>
            <input type="text" id="pickupAddress" placeholder="যেমন: মালদা, ইংরেজবাজার বা আপনার গ্রামের নাম" required>

            <!-- ড্রপ লোকেশন (কোথায় যাবে) -->
            <label class="info-label">কোথায় যাবেন (গন্তব্য):</label>
            <input type="text" id="dropAddress" placeholder="যে জায়গায় যাবেন সেই ঠিকানার নাম লিখুন" required>

            <input type="text" id="custRef" placeholder="রেফার কোড দিন (যদি থাকে)">
            <button type="submit">🟢 হোয়াটসঅ্যাপে বুকিং পাঠান</button>
        </form>
        <div class="referral-text">
            বন্ধুদের রেফার করে আয় করুন! আপনার রেফার কোড: <span style="color: #28a745;">SAMIR50</span>
        </div>
    </div>

    <!-- ২. গাড়ির মালিকদের রেজিস্ট্রেশন ফর্ম -->
    <div id="owner-section" class="form-section">
        <h3>মালিকদের অ্যাকাউন্ট (প্রিমিয়াম আইডি)</h3>
        <p style="text-align: center; color: #666; font-size: 13px;">১০০০ টাকা ফি দিয়ে আইডি সচল করুন।</p>
        <form onsubmit="sendOwnerToWhatsApp(event)">
            <input type="text" id="ownerName" placeholder="মালিক বা কোম্পানির নাম" required>
            <input type="tel" id="ownerPhone" placeholder="মোবাইল নম্বর" required>
            <input type="text" id="carDetails" placeholder="গাড়ির মডেল ও নাম্বার" required>
            <select id="payMethod" required>
                <option value="">টাকা পাঠানোর মাধ্যম বেছে নিন</option>
                <option value="PhonePe">PhonePe / Google Pay</option>
                <option value="Paytm">Paytm</option>
                <option value="বিকাশ/নগদ">bKash / Nagad</option>
            </select>
            <input type="text" id="trxId" placeholder="Transaction ID বা UTR নম্বর লিখুন" required>
            <button type="submit" class="owner-btn">🔵 হোয়াটসঅ্যাপে পেমেন্ট তথ্য পাঠান</button>
        </form>
    </div>
</div>

<script>
    // আপনার হোয়াটসঅ্যাপ নম্বর এখানে দিন (যেমন: 91XXXXXXXXXX অথবা 880XXXXXXXXXX)
    const myWhatsAppNumber = 91 9091594834 ,91 9733085455 

    function switchForm(type) {
        document.getElementById('booking-section').classList.remove('active');
        document.getElementById('owner-section').classList.remove('active');
        document.getElementById('tab1').classList.remove('active');
        document.getElementById('tab2').classList.remove('active');
        
        if (type === 'booking') {
            document.getElementById('booking-section').classList.add('active');
            document.getElementById('tab1').classList.add('active');
        } else {
            document.getElementById('owner-section').classList.add('active');
            document.getElementById('tab2').classList.add('active');
        }
    }

    function sendBookingToWhatsApp(e) {
        e.preventDefault();
        
        let name = document.getElementById('custName').value;
        let phone = document.getElementById('custPhone').value;
        let pAddress = document.getElementById('pickupAddress').value;
        let dAddress = document.getElementById('dropAddress').value;
        let ref = document.getElementById('custRef').value || "নাই";

        let message = `*নতুন গাড়ি বুকিং রিকোয়েস্ট!*\n\n` +
                      `👤 নাম: ${name}\n` +
                      `📞 মোবাইল: ${phone}\n` +
                      `📍 কোথা থেকে (পিকআপ): ${pAddress}\n` +
                      `🏁 কোথায় যাবে (ড্রপ): ${dAddress}\n` +
                      `🎁 রেফার কোড: ${ref}`;

        let whatsappUrl = `https://wa.me/${myWhatsAppNumber}?text=${encodeURIComponent(message)}`;
        window.open(whatsappUrl, '_blank');
    }

    function sendOwnerToWhatsApp(e) {
        e.preventDefault();
        
        let oName = document.getElementById('ownerName').value;
        let oPhone = document.getElementById('ownerPhone').value;
        let car = document.getElementById('carDetails').value;
        let method = document.getElementById('payMethod').value;
        let trx = document.getElementById('trxId').value;

        let message = `*নতুন গাড়ির মালিকের রেজিস্ট্রেশন ও পেমেন্ট!*\n\n` +
                      `👤 মালিকের নাম: ${oName}\n` +
                      `📞 মোবাইল: ${oPhone}\n` +
                      `🚗 গাড়ির বিবরণ: ${car}\n` +
                      `💳 পেমেন্ট মাধ্যম: ${method}\n` +
                      `🆔 Transaction/UTR ID: ${trx}`;

        let whatsappUrl = `https://wa.me/${myWhatsAppNumber}?text=${encodeURIComponent(message)}`;
        window.open(whatsappUrl, '_blank');
    }
</script>

</body>
</html>
