<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>College Assignment</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            padding: 20px;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #4CAF50;
        }
        img {
            display: block;
            margin: 20px auto;
            width: 300px;
            border-radius: 10px;
        }
        video {
            display: block;
            margin: 20px auto;
            width: 400px;
            border: 2px solid #4CAF50;
            border-radius: 10px;
        }
        table {
            width: 60%;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: #fff;
        }
        table, th, td {
            border: 2px solid #4CAF50;
            padding: 10px;
            text-align: center;
        }
        form {
            text-align: center;
            margin-top: 30px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 25px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
        .radio-group {
            margin: 15px 0;
        }
    </style>
</head>
<body>

    <h1>Welcome to My Assignment</h1>

    <!-- Picture -->
    <img src="IMG_8420.png" alt="UCP Picture">

    <!-- Video -->
    <video controls>
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <!-- Table -->
    <table>
        <thead>
            <tr>
                <th>Subject</th>
                <th>Marks</th>
                <th>Grade</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Math</td>
                <td>90</td>
                <td>A</td>
            </tr>
            <tr>
                <td>Science</td>
                <td>85</td>
                <td>B+</td>
            </tr>
            <tr>
                <td>English</td>
                <td>88</td>
                <td>A-</td>
            </tr>
        </tbody>
    </table>

    <!-- Form with Radio Buttons and Submit Button -->
    <form action="#" method="post">
        <div class="radio-group">
            <label><input type="radio" name="feedback" value="Excellent"> Excellent</label>
            <label><input type="radio" name="feedback" value="Good"> Good</label>
            <label><input type="radio" name="feedback" value="Average"> Average</label>
            <label><input type="radio" name="feedback" value="Poor"> Poor</label>
        </div>
        <input type="submit" value="Submit">
    </form>

</body>
</html>