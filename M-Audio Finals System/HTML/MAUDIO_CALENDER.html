<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Bookings</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            display: flex;
            height: 100vh; /* Full height of viewport */
        }

        .sidebar {
            width: 250px; /* Fixed width for sidebar */
            background: linear-gradient(to left, #1a1919, rgba(26, 25, 25, 0.8)); /* Faded dark shade */
            color: #424141; /* Updated to gray text color */
            display: flex;
            flex-direction: column; /* Stack items vertically */
            align-items: center; /* Center items horizontally */
            padding-top: 20px; /* Add spacing at the top */
            font-family: 'Courier New', Courier, monospace; /* Updated font for sidebar */
        }

        .logo {
            width: 150px; /* Circular logo size */
            height: 150px;
            border-radius: 50%; /* Makes it circular */
            object-fit: cover; /* Ensures logo fits within its container */
            margin-bottom: 20px; /* Adds spacing below logo */
            box-shadow: 0 0 15px rgba(19, 19, 19, 0.5), 
                        -5px -5px 10px rgba(0, 0, 0, 0.7),
                        5px 5px 10px rgba(0, 0, 0, 0.7); /* Shadow on all sides */
        }

        .nav {
            list-style: none; /* Removes bullet points */
            width: 75%; /* Centers navigation links */
            text-align: center;
        }

        .nav-item {
                margin-bottom: 10px; /* Adds spacing between navigation buttons */
        }

        .nav-link {
            display: block;
            padding: 15px;
            font-size: 18px;
            color: white;
            text-decoration: none;
            border: 1px solid white;
            width: 100%;
            border-radius: 10px; /* Curved corners */
            transition: box-shadow 0.3s ease, background-color 0.3s ease;
        }

        .nav-link:hover {
            background-color: #444; /* Slightly lighter gray on hover */
            box-shadow: 3px 3px 3px rgba(252, 252, 252, 0.849); /* Subtle shadow effect on hover */
        }

        .main-content {
            flex-grow: 1;
            display: flex;
            justify-content: center; /* Center horizontally */
            align-items: center; /* Center vertically */
            background: linear-gradient(to right, #5e5e5e, #cfcfcf);
            padding: 20px;
        }

        .calendar {
            width: 90%;
            max-width: 900px;
            height: auto; /* Remove fixed height */
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
        }

        .calendar-header {
            display: flex;
            justify-content: flex-start;
            align-items: center;
            gap: 10px;
            margin-bottom: 15px;
        }

        .calendar-header select {
            padding: 12px 20px;
            font-size: 20px;
            border-radius: 6px;
            border: 2px solid #2c3e50;
            background: white;
            font-weight: bold;
        }

        .calendar-days {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            grid-template-rows: repeat(6, 1fr);
            gap: 10px;
            flex-grow: 1;
        }

        .day {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 15px;
            border-radius: 8px;
            background: #ecf0f1;
            cursor: pointer;
            transition: 0.3s;
            font-size: 18px;
            font-weight: bold;
        }

        .day:hover {
            background: #bdc3c7;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <img src="436264411_950515963748200_1965576046051139400_n (1).jpg" alt="Logo" class="logo">
        <ul class="nav">
            <li class="nav-item"><a href="#" class="nav-link">OVERVIEW</a></li>
            <li class="nav-item"><a href="#" class="nav-link">BOOKINGS</a></li>
            <li class="nav-item"><a href="#" class="nav-link">SALES</a></li>
            <li class="nav-item"><a href="#" class="nav-link">CONTROL</a></li>
            <li class="nav-item"><a href="#" class="nav-link">LOG OUT</a></li>
        </ul>
    </div>
    <div class="main-content">
        <div class="calendar">
            <div class="calendar-header">
                <select id="month-select"></select>
                <select id="year-select"></select>
            </div>
            <div class="calendar-days" id="calendar-days"></div>
        </div>
    </div>
    <?php
// Get current date or from GET parameters (for month/year selection)
$month = isset($_GET['month']) ? intval($_GET['month']) : date('n') - 1; // zero-based month index
$year = isset($_GET['year']) ? intval($_GET['year']) : date('Y');

// Month names array
$monthNames = [
    "January", "February", "March", "April", "May", "June",
    "July", "August", "September", "October", "November", "December"
];

// Calculate first day of the month (0=Sunday, 6=Saturday)
$firstDayOfMonth = date('w', strtotime("$year-" . ($month + 1) . "-01"));

// Calculate number of days in the month
$daysInMonth = cal_days_in_month(CAL_GREGORIAN, $month + 1, $year);
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>PHP Calendar - Audio Pro Sound</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(90deg, #222 0%, #888 100%);
            margin: 0;
            padding: 40px;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
        }
        .calendar-container {
            background: #fff;
            border-radius: 18px;
            padding: 30px 40px;
            box-shadow: 0 4px 18px rgba(0,0,0,0.1);
            min-width: 700px;
        }
        form {
            margin-bottom: 20px;
            display: flex;
            gap: 12px;
        }
        select {
            padding: 10px 16px;
            font-size: 1.1em;
            border-radius: 6px;
            border: 2px solid #222;
            font-weight: bold;
            cursor: pointer;
            outline: none;
        }
        .calendar-grid {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 12px 14px;
        }
        .calendar-day {
            background: #edf1f2;
            border-radius: 8px;
            padding: 14px 0;
            text-align: center;
            font-weight: 600;
            font-size: 1.2em;
            color: #444;
            user-select: none;
        }
        .calendar-day.empty {
            background: transparent;
            box-shadow: none;
            cursor: default;
        }
    </style>
</head>
<body>
    <div class="calendar-container">
        <form method="get" id="calendar-form">
            <select name="month" id="month-select" onchange="document.getElementById('calendar-form').submit()">
                <?php foreach ($monthNames as $index => $name): ?>
                    <option value="<?= $index ?>" <?= ($index === $month) ? 'selected' : '' ?>><?= htmlspecialchars($name) ?></option>
                <?php endforeach; ?>
            </select>
            <select name="year" id="year-select" onchange="document.getElementById('calendar-form').submit()">
                <?php
                $currentYear = date('Y');
                for ($y = $currentYear - 10; $y <= $currentYear + 10; $y++): ?>
                    <option value="<?= $y ?>" <?= ($y == $year) ? 'selected' : '' ?>><?= $y ?></option>
                <?php endfor; ?>
            </select>
        </form>

        <div class="calendar-grid">
            <?php
            // Print empty slots for days before the first day of the month
            for ($i = 0; $i < $firstDayOfMonth; $i++) {
                echo '<div class="calendar-day empty"></div>';
            }

            // Print days of the month
            for ($day = 1; $day <= $daysInMonth; $day++) {
                echo "<div class='calendar-day'>{$day}</div>";
            }
            ?>
        </div>
    </div>
</body>
</html>
