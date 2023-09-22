# monisha5458.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <a href="sendemail.html">Click here</a>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }

        h1 {
            font-size: 24px;
        }

        label {
            font-weight: bold;
        }

        input[type="text"],
        input[type="date"],
        input[type="number"],
        input[type="tel"],
        select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
        }

        input[type="checkbox"] {
            margin-right: 5px;
        }

        .submit-button {
            background-color: #007BFF;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Web Page Form</h1>
        <form action="#" method="post">
            <label for="cws_description">CWS Description:</label>
            <input type="text" id="cws_description" name="cws_description" required>

            <label for="hsi_date_revision_date">HSI Date Revision Date:</label>
            <input type="date" id="hsi_date_revision_date" name="hsi_date_revision_date" required>

            <label for="msds_date_revision_date">MSDS Date Revision Date:</label>
            <input type="date" id="msds_date_revision_date" name="msds_date_revision_date" required>

            <label for="f13">F13:</label>
            <input type="text" id="f13" name="f13" required>

            <label for="classification">Classification:</label>
            <input type="text" id="classification" name="classification" required>

            <label for="symbols">Symbols:</label>
            <input type="text" id="symbols" name="symbols" required>

            <label for="used_in">Used In:</label>
            <input type="text" id="used_in" name="used_in" required>

            <label for="approved_quantity">Approved Quantity:</label>
            <input type="number" id="approved_quantity" name="approved_quantity" required>

            <label for="register_number">Register Number:</label>
            <input type="text" id="register_number" name="register_number" required>

            <label for="responsible">Responsible:</label>
            <input type="text" id="responsible" name="responsible" required>

            <label for="ph_no">PH.No:</label>
            <input type="tel" id="ph_no" name="ph_no" required>

            <label for="send_reminder">Send Reminder:</label>
            <input type="checkbox" id="send_reminder" name="send_reminder">

            <input type="submit" class="submit-button" value="Submit">
        </form>
        <a href="we1.html">Click here</a>
    </div>
</body>
</html>
