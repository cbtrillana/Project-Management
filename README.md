# Project-Management
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Project Management Dashboard</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Project Management Dashboard</h1>

    <section>
      <h2>Project Details</h2>
      <table>
        <tr><td>Project Title:</td><td><input type="text" /></td></tr>
        <tr><td>Proponent:</td><td><input type="text" /></td></tr>
        <tr><td>Agency:</td><td><input type="text" /></td></tr>
        <tr><td>Duration:</td><td><input type="text" /></td></tr>
        <tr><td>Project Status:</td><td><input type="text" /></td></tr>
      </table>
    </section>

    <section>
      <h2>Dates to Remember</h2>
      <table>
        <tr><td>Deadline of Renewal Request:</td><td><input type="date" /></td></tr>
        <tr><td>Deadline of Reprogramming:</td><td><input type="date" /></td></tr>
        <tr><td>Deadline of Extension Request:</td><td><input type="date" /></td></tr>
      </table>
    </section>

    <section>
      <h2>Documentary Requirements</h2>
      <table class="wide">
        <thead>
          <tr>
            <th>Requirement</th><th>Status</th><th>Date Submitted</th><th>Schedule</th><th>Remarks</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Form 11</td><td><input type="text" /></td><td><input type="date" /></td><td><input type="date" /></td><td><input type="text" /></td></tr>
          <tr><td>Inception Report</td><td><input type="text" /></td><td><input type="date" /></td><td><input type="date" /></td><td><input type="text" /></td></tr>
          <!-- Add more rows as needed -->
        </tbody>
      </table>
    </section>

    <section>
      <h2>Progress Review and M&E Activities</h2>
      <table class="wide">
        <thead>
          <tr><th>Activity</th><th>Schedule</th><th>Status</th><th>Actual</th><th>Remarks</th></tr>
        </thead>
        <tbody>
          <tr><td>Inception Review</td><td><input type="date" /></td><td><input type="text" /></td><td><input type="date" /></td><td><input type="text" /></td></tr>
          <!-- Add more rows -->
        </tbody>
      </table>
    </section>

    <section>
      <h2>Requests</h2>
      <table>
        <thead><tr><th>Request</th><th>Date of Request</th><th>Status</th><th>Remarks</th></tr></thead>
        <tbody>
          <tr><td><input type="text" /></td><td><input type="date" /></td><td><input type="text" /></td><td><input type="text" /></td></tr>
        </tbody>
      </table>
    </section>

    <section>
      <h2>Closing Documents</h2>
      <table class="wide">
        <thead>
          <tr><th>Requirement</th><th>Status</th><th>Date Submitted</th><th>Remarks</th></tr>
        </thead>
        <tbody>
          <tr><td>Terminal Report</td><td><input type="text" /></td><td><input type="date" /></td><td><input type="text" /></td></tr>
          <!-- Add more rows -->
        </tbody>
      </table>
    </section>
  </div>
</body>
</html>
