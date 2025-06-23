<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Procurement Terms and Conditions</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background: #f8f9fa;
            color: #222;
        }
        .container {
            max-width: 700px;
            background: #fff;
            padding: 30px 40px;
            margin: 0 auto;
            box-shadow: 0 2px 12px rgba(0,0,0,0.07);
            border-radius: 8px;
        }
        h1 {
            text-align: center;
            color: #215187;
        }
        .terms-box {
            border: 1px solid #d1d5da;
            background: #f4f8fc;
            padding: 20px;
            margin: 20px 0;
            height: 250px;
            overflow-y: auto;
            border-radius: 5px;
        }
        .accept-section {
            display: flex;
            align-items: center;
            margin-top: 20px;
            justify-content: space-between;
        }
        button {
            padding: 10px 30px;
            background: #2a7ae2;
            color: #fff;
            border: none;
            border-radius: 3px;
            font-size: 1em;
            cursor: pointer;
            transition: background 0.2s;
        }
        button:disabled {
            background: #b2c5e3;
            cursor: not-allowed;
        }
        label {
            font-size: 1em;
            margin-left: 10px;
            cursor: pointer;
        }
        .accepted-message {
            color: #0a8635;
            font-weight: bold;
            text-align: center;
            margin-top: 20px;
            font-size: 1.15em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Procurement Terms and Conditions</h1>
        <div class="terms-box" id="termsBox">
            <h3>1. Acceptance of Terms</h3>
            <p>
                By participating in the procurement process, you agree to comply with and be bound by the following terms and conditions. Please review them carefully.
            </p>
            <h3>2. Eligibility</h3>
            <p>
                Only eligible vendors with valid registration may participate. All participants must provide accurate and complete information.
            </p>
            <h3>3. Submission of Offers</h3>
            <p>
                Offers must be submitted before the deadline. Late submissions will not be considered. All offers are binding once submitted.
            </p>
            <h3>4. Confidentiality</h3>
            <p>
                All information exchanged during the procurement process must be treated as confidential and not disclosed to third parties.
            </p>
            <h3>5. Governing Law</h3>
            <p>
                These terms are governed by the laws of the applicable jurisdiction.
            </p>
            <h3>6. Amendments</h3>
            <p>
                The organization reserves the right to amend these terms and conditions at any time without prior notice.
            </p>
            <p>
                For detailed terms, please contact the procurement office.
            </p>
        </div>
        <form id="acceptForm">
            <div class="accept-section">
                <span>
                    <input type="checkbox" id="acceptCheckbox" />
                    <label for="acceptCheckbox">I have read and accept the Procurement Terms and Conditions.</label>
                </span>
                <button id="acceptBtn" type="submit" disabled>Accept</button>
            </div>
        </form>
        <div class="accepted-message" id="acceptedMessage" style="display: none;">
            Thank you! You have accepted the Procurement Terms and Conditions.
        </div>
    </div>
    
</body>
</html>
