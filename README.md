<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="exp3.css">
    
  </head>
  <body>
    <div class="container">
      <script type="text/javascript" src="ex3.js"></script>
      <form id="form" class="form">
        <h2>Registration Form</h2>
        <div class="form-control">
          <label for="username">Username</label>
          <input type="text" id="username" placeholder="Enter username" />
          <small>Error message</small>
        </div>
        <div class="form-control">
          <label for="email">Email</label>
          <input type="text" id="email" placeholder="Enter email" />
          <small>Error message</small>
        </div>
        <div class="form-control">
          <label for="password">Password</label>
          <input type="password" id="password" placeholder="Enter password" />
          <small>Error message</small>
        </div>
        <div class="form-control">
          <label for="password2">Confirm password</label>
          <input
            type="password"
            id="password2"
            placeholder="Renter your password"
          />
          <br><br>
                D.O.B<br><input type="date" name="bday"><br><br>
  <!--Gender:
  <br>
  <input type="radio" name="gender">Male <input type="radio" name="gender">Female-->
        Gender:
        <select id="selection">
          <option>Gender</option>
          <option>Male</option>
          <option>Female</option>
        </select>
        <br><br>
        

          <small>Error message</small>
        </div>
        <button type="submit">Submit</button>
      </form>
    </div>

  </body>
</html>

