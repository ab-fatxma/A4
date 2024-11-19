<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>CE Course Evaluation Form</title>
</head>
<body>
    <header>
        <a href="https://www.centennialcollege.ca/">
            <img src="https://tukuz.com/wp-content/uploads/2020/10/centennial-college-logo-vector.png" alt="College Logo" id="logo">
        </a>
        <h1>CE Course Evaluation Form</h1>
    </header>

    <div class="form-container">
        <form action="submit_form.php" method="post">
            <h2>Course Information</h2>
            <label for="course-name">Course Name:</label>
            <input type="text" id="course-name" name="course-name" required>

            <label for="instructor-name">Instructor Name:</label>
            <input type="text" id="instructor-name" name="instructor-name" required>

            <h2>Evaluation Questions</h2>
            <label>How would you rate the course overall?</label>
            <div>
                <input type="radio" id="excellent" name="course-rating" value="excellent">
                <label for="excellent">Excellent</label>
                <input type="radio" id="good" name="course-rating" value="good">
                <label for="good">Good</label>
                <input type="radio" id="fair" name="course-rating" value="fair">
                <label for="fair">Fair</label>
                <input type="radio" id="poor" name="course-rating" value="poor">
                <label for="poor">Poor</label>
            </div>

            <label>How likely are you to recommend this course to others?</label>
            <div>
                <input type="radio" id="very-likely" name="recommendation" value="very-likely">
                <label for="very-likely">Very Likely</label>
                <input type="radio" id="likely" name="recommendation" value="likely">
                <label for="likely">Likely</label>
                <input type="radio" id="not-likely" name="recommendation" value="not-likely">
                <label for="not-likely">Not Likely</label>
                <input type="radio" id="never" name="recommendation" value="never">
                <label for="never">Never</label>
            </div>

            <label for="feedback">Additional Comments:</label>
            <textarea id="feedback" name="feedback" rows="4" cols="50" placeholder="Your comments..."></textarea>

            <div class="button-group">
                <button type="submit">Submit Feedback</button>
                <button type="reset">Clear Form</button>
            </div>
        </form>
    </div>

    <footer>
        <p>For inquiries, contact us at <a href="mailto:info@centennialcollege.edu">info@centennialcollege.edu</a></p>
    </footer>
</body>
</html>

<style class="css">body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #b83654;
    color: white;
    text-align: center;
    padding: 20px;
}

#logo {
    width: 100px;
    height: auto;
}

.form-container {
    background-color: white;
    border-radius: 8px;
    padding: 20px;
    margin: 20px auto;
    max-width: 600px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #791d48;
}

label {
    display: block;
    margin: 10px 0 5px;
}

button {
    background-color: #832a4f;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 5px;
    cursor: pointer;
    margin-right: 10px;
}

button:hover {
    background-color: #921236;
}

footer {
    text-align: center;
    margin-top: 20px;
    font-size: 14px;
}</style>
