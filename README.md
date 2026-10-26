<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CJTF Rivers State Command Registration</title>
<style>
body{font-family:Arial,sans-serif;background:#f0f4f0;margin:0;color:#17251b}
header{background:#123d25;color:white;text-align:center;padding:25px 12px}
main{max-width:600px;margin:20px auto;background:white;padding:20px;border-radius:10px;box-shadow:0 2px 8px #ccc}
h2{color:#123d25}
label{display:block;margin-top:14px;font-weight:bold}
input,select,textarea{width:100%;box-sizing:border-box;padding:12px;margin-top:6px;border:1px solid #aaa;border-radius:5px;font-size:16px}
button{margin-top:20px;width:100%;padding:14px;background:#176638;color:white;border:0;border-radius:5px;font-size:17px}
.notice{background:#fff3cd;padding:12px;border-radius:5px;line-height:1.5}
footer{text-align:center;padding:20px;font-size:13px}
</style>
</head>
<body>
<header>
<h1>CJTF RIVERS STATE COMMAND</h1>
<p>Peace and Justice</p>
<h2 style="color:white">Membership Registration</h2>
</header>
<main>
<p>Welcome to the Civilian Joint Task Force (CJTF), Rivers State Command online registration page.</p>
<div class="notice"><strong>Important:</strong> Submitting this form does not confirm membership. All applications require approval by the State Commander.</div>
<form id="registrationForm">
<label>Full Name</label>
<input name="fullname" required placeholder="Enter your full name">
<label>Phone Number</label>
<input name="phone" type="tel" required placeholder="Enter your phone number">
<label>Email Address (if available)</label>
<input name="email" type="email" placeholder="Enter your email">
<label>State of Residence</label>
<input name="state" required placeholder="Enter your state">
<label>Local Government Area</label>
<input name="lga" required placeholder="Enter your LGA">
<label>Age</label>
<input name="age" type="number" min="18" required>
<label>Previous Security Experience</label>
<select name="experience" required>
<option value="">Select one</option>
<option>Yes</option>
<option>No</option>
</select>
<label>Why do you want to join CJTF?</label>
<textarea name="reason" rows="4" required></textarea>
<button type="submit">Submit Application</button>
</form>
<p id="message"></p>
</main>
<footer>© CJTF Rivers State Command</footer>
<script>
document.getElementById('registrationForm').addEventListener('submit',function(e){
e.preventDefault();
document.getElementById('message').textContent='This is a demonstration form. Your application has NOT been sent or saved. Secure application storage and administrator approval must be configured before real registration.';
});
</script>
</body>
</html>
