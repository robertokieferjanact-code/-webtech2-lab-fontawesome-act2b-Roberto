<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Information System</title>

  <!-- Bootstrap CDN -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

  <!-- Container and Typography -->
  <div class="container mt-4">
    <h1 class="text-center">Student Information System</h1>
    <p class="lead text-muted text-center">This page demonstrates Bootstrap basics</p>

    <!-- Grid System -->
    <div class="row mt-4">
      <div class="col-md-6 bg-light p-3">Left Column</div>
      <div class="col-md-6 bg-secondary text-white p-3">Right Column</div>
    </div>

    <!-- Table -->
    <h2 class="mt-4">Student List</h2>
    <table class="table table-bordered table-striped">
      <thead>
        <tr>
          <th>Student Number</th>
          <th>Last Name</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>000000001</td>
          <td>Abitago</td>
          <td>Abitago@gmail.com</td>
        </tr>
        <tr>
          <td>000000002</td>
          <td>Santos</td>
          <td>santos@example.com</td>
        </tr>
        <!-- You can add more student rows here -->
      </tbody>
    </table>

    <!-- Form -->
    <h2 class="mt-4">Register New Student</h2>
    <form>
      <div class="mb-3">
        <label class="form-label">Student Number</label>
        <input type="text" class="form-control" placeholder="Enter student number">
      </div>
      <div class="mb-3">
        <label class="form-label">Last Name</label>
        <input type="text" class="form-control" placeholder="Enter last name">
      </div>
      <div class="mb-3">
        <label class="form-label">Email</label>
        <input type="email" class="form-control" placeholder="Enter email">
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>

</body>
</html>
