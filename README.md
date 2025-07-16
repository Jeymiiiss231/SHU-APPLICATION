<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apply to the University of Sheffield</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        header {
            text-align: center;
            padding: 20px 0;
            border-bottom: 2px solid #d50032;
        }
        .logo {
            max-width: 200px;
            margin-bottom: 10px;
        }
        h1 {
            color: #d50032;
            margin: 10px 0;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
        }
        button {
            background: #d50032;
            color: #fff;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 4px;
            width: 100%;
        }
        button:hover {
            background: #b30028;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid #ddd;
            font-size: 14px;
        }
        .contact-info {
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="https://www.sheffield.ac.uk/brand/sites/site1/themes/uos_brand/images/logo.svg" alt="University of Sheffield Logo" class="logo">
            <h1>Apply to the University of Sheffield</h1>
            <p>Start your journey at a world-class university!</p>
        </header>

        <form id="applicationForm">
            <div class="form-group">
                <label for="fullName">Full Name</label>
                <input type="text" id="fullName" name="fullName" required>
            </div>

            <div class="form-group">
                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div class="form-group">
                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" required>
            </div>

            <div class="form-group">
                <label for="program">Choose Your Program</label>
                <select id="program" name="program" required>
                    <option value="">-- Select a Program --</option>
                    <option value="engineering">Engineering</option>
                    <option value="business">Business & Economics</option>
                    <option value="medicine">Medicine & Health Sciences</option>
                    <option value="arts">Arts & Humanities</option>
                    <option value="computer-science">Computer Science & AI</option>
                    <option value="social-sciences">Social Sciences</option>
                </select>
            </div>

            <div class="form-group">
                <label for="qualifications">Previous Qualifications</label>
                <textarea id="qualifications" name="qualifications" rows="4" required></textarea>
            </div>

            <div class="form-group">
                <label for="personalStatement">Personal Statement</label>
                <textarea id="personalStatement" name="personalStatement" rows="6" required></textarea>
            </div>

            <div class="form-group">
                <label for="documents">Upload Documents (CV, Certificates, etc.)</label>
                <input type="file" id="documents" name="documents" multiple>
            </div>

            <button type="submit">Submit Application</button>
        </form>

        <footer>
            <p>Need help with your application? Contact us:</p>
            <div class="contact-info">
                <p>📧 <a href="mailto:Shefielduni@proton.me">Shefielduni@proton.me</a></p>
                <p>📱 WhatsApp: <a href="https://wa.me/447832714017">+44 7832 714017</a></p>
            </div>
            <p>&copy; 2024 University of Sheffield</p>
        </footer>
    </div>

    <script>
        document.getElementById('applicationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your application! We will contact you soon.');
            this.reset();
        });
    </script>
</body>
</html>
