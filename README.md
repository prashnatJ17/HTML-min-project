# HTML-min-project
<!DOCTYPE html>
<html>
<head>
<title>Restaurant Menu & Reservation</title>
<style>
body {
    font-family: Arial, sans-serif;
    background: #f4f4f4;
    margin: 0;
    padding: 20px;
}

/* Heading */
h1 {
    text-align: center;
    color: #333;
}

/* Menu Section */
.menu {
    background: white;
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 30px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

.menu h2 {
    color: #e74c3c;
}

/* Menu Lists */
.menu ul {
    list-style-type: square;
    font-size: 18px;
}

.menu ol {
    font-size: 18px;
}

/* Table Section */
.table-section {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

/* Reservation Table */
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
}

th {
    background: #2c3e50;
    color: white;
    padding: 12px;
}

td {
    padding: 10px;
    text-align: center;
    border: 1px solid #ddd;
}

/* Row Highlight */
tr:nth-child(even) {
    background: #f9f9f9;
}

tr:hover {
    background: #ffeaa7;
    cursor: pointer;
}

/* Responsive Table */
@media (max-width: 600px) {
    table, th, td {
        font-size: 12px;
    }
}
</style>
</head>
<body>

<h1>🍽️ Restaurant Menu & Reservation</h1>

<!-- MENU SECTION -->
<div class="menu">
    <h2>Restaurant Menu</h2>

    <h3>🥗 Starters (Unordered List)</h3>
    <ul>
        <li>Veg Soup</li>
        <li>Paneer Tikka</li>
        <li>French Fries</li>
    </ul>

    <h3>🍛 Main Course (Ordered List)</h3>
    <ol>
        <li>Butter Chicken</li>
        <li>Paneer Butter Masala</li>
        <li>Veg Biryani</li>
    </ol>
</div>

<!-- RESERVATION TABLE -->
<div class="table-section">
    <h2>Table Reservations</h2>

    <table>
        <tr>
            <th>Table No</th>
            <th>Customer Name</th>
            <th>Guests</th>
            <th>Date</th>
            <th>Status</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Rahul</td>
            <td>4</td>
            <td>10-02-2026</td>
            <td>Booked</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Priya</td>
            <td>2</td>
            <td>10-02-2026</td>
            <td>Available</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Amit</td>
            <td>6</td>
            <td>11-02-2026</td>
            <td>Booked</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Neha</td>
            <td>3</td>
            <td>11-02-2026</td>
            <td>Available</td>
        </tr>
    </table>
</div>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<style>
table {
  width: 70%;
  border-collapse: collapse;
  text-align: center;
  font-family: Arial;
}
th {
  background: red;
  color: white;
  padding: 10px;
  border: 2px solid yellow;
}
td {
  background: yellowgreen;
  padding: 10px;
  border: 2px solid yellow;
}
caption {
  font-size: 22px;
  font-weight: bold;
  background: yellow;
  padding: 10px;
}
</style>
</head>
<body>

<table>
  <caption>Make HTML Table</caption>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
    <th>Position</th>
    <th>Salary</th>
  </tr>
  <tr>
    <td>James</td>
    <td>Jeo</td>
    <td>CEO</td>
    <td>$1300</td>
  </tr>
  <tr>
    <td>Kate</td>
    <td>Harns</td>
    <td>Designer</td>
    <td>$1000</td>
  </tr>
  <tr>
    <td>Bryan</td>
    <td>Brian</td>
    <td>Team Leader</td>
    <td>$700</td>
  </tr>
  <tr>
    <td>Lesely</td>
    <td>Prcnic</td>
    <td>Author</td>
    <td>$500</td>
  </tr>
</table>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Nested List</title>
</head>
<body>

<h2>Some of my favorite links</h2>

<ul>
    <li>Social Networking
        <ul>
            <li>Facebook</li>
            <li>Instagram</li>
            <li>Twitter</li>
        </ul>
    </li>

    <li>Reference
        <ul>
            <li>Google</li>
            <li>Wikipedia</li>
            <li>Dictionary</li>
        </ul>
    </li>

    <li>Web Development
        <ul>
            <li>HTML/CSS
                <ul>
                    <li>W3Schools</li>
                    <li>MDN Web Docs</li>
                </ul>
            </li>
            <li>Programming
                <ul>
                    <li>JavaScript</li>
                    <li>PHP</li>
                    <li>MySQL</li>
                </ul>
            </li>
        </ul>
    </li>
</ul>

</body>
</html>
