# Welcome-Survey
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to the Party!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f8ff;
            padding: 20px;
        }
        h1 {
            color: #006600;
        }
        .survey-form {
            background-color: #fff;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            max-width: 600px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .survey-form input, .survey-form select, .survey-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            padding: 10px 20px;
            background-color: #006600;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Welcome to Rissa's Birthday!</h1>
    <p>We're so glad you're here. Please take a moment to fill out this quick survey:</p>

    <div class="survey-form">
        <form action="https://formspree.io/f/{your-form-id}" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="location">Where are you coming from?</label>
            <input type="text" id="location" name="location" required>

            <label for="drive">How was the drive?</label>
            <textarea id="drive" name="drive" rows="3"></textarea>

            <label for="guests">How many guests are with you?</label>
            <input type="number" id="guests" name="guests" required>

            <label for="arrival">What time did you arrive?</label>
            <input type="time" id="arrival" name="arrival" required>

            <label for="food">Have you tried Chamorro/Filipino food before?</label>
            <select id="food" name="food" required>
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>

            <label for="party">Are you excited to party?</label>
            <select id="party" name="party" required>
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>

            <label for="drink">Do you drink?</label>
            <select id="drink" name="drink" required>
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>

            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
