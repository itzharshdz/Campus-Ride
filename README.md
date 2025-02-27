<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campus Ride</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eafbea;
            text-align: center;
        }
        
        .container {
            background: #dff5df;
            width: 90%;
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            color: green;
        }
        
        label {
            font-weight: bold;
            display: block;
            margin-top: 10px;
            text-align: left;
        }
        
        input,
        select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        
        .radio-group {
            text-align: left;
            margin-top: 5px;
        }
        
        .radio-group input {
            margin-right: 5px;
        }
        
        button {
            background-color: green;
            color: white;
            padding: 10px;
            width: 100%;
            border: none;
            margin-top: 15px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }
        
        button:hover {
            background-color: darkgreen;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>🚲 Campus Ride</h1>
        <p>Book a bicycle for your campus commute</p>

        <form>
            <label for="enrollment">Enrollment Number</label>
            <input type="text" id="enrollment" placeholder="Enter your enrollment number" required>

            <label for="course">Course and Semester</label>
            <input type="text" id="course" placeholder="e.g. BTech CSE - 4th Semester" required>

            <label for="destination">Destination</label>
            <select id="destination">
            <option value="Anviksha">Anviksha</option>
            <option value="SOS">SOS</option>
            <option value="Culture Center">Culture Center</option>
            
        </select>

            <label>Reason for Travel</label>
            <div class="radio-group">
                <input type="radio" name="reason" value="Lecture" checked> Lecture
                <input type="radio" name="reason" value="Meeting"> Meeting
                <input type="radio" name="reason" value="Library"> Library
                <input type="radio" name="reason" value="Other"> Other
            </div>

            <label for="cycleNumber">Cycle Number</label>
            <input type="text" id="cycleNumber" placeholder="Enter Cycle Number" required>

            <label for="date">Date of Ride</label>
            <input type="date" id="date" required>
            <label for="time"> how much you take a time </label>
            <input type="time" id="time" required>

            <button type="submit">Book Ride</button>
        </form>
    </div>

</body>

</html>
