# landry ndizeye
# 20206370
<!DOCTYPE html>
<html>
  <head>
    <title>HTML cheat sheet</title>
    <link rel="icon" href="icon.jpg" type="image/png">
    
  </head>
  <body>
    <a href="Blog.html">go to blog</a>
    <!-- headings -->
    <h1>Heading one</h1>
    <h2>Heading two</h2>
    <h3>Heading three</h3>
    <h4>Heading four</h4>
    <h5>Heading five</h5>
    <h6>Heading six</h6>
    <p>
      <!--paragraph-->
      Lorem ipsum dolor <strong> amet consectetur, adipisicing elit. Rerum, </strong> fugit numquam! Maxime modi, reiciendis eveniet neque <em>quas autem, cumque similique quam optio libero laborum </em> atque voluptas deserunt laboriosam! Ullam, obcaecati?
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, esse?
      </p>

      <p>
      Lorem ipsum dolor sit amet <a href="http://google.com" target="_blank">consectetur, adipisicing elit.</a> Rerum, fugit numquam! Maxime modi, reiciendis eveniet neque quas autem, cumque similique quam optio libero laborum atque voluptas deserunt laboriosam! Ullam, obcaecati?
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, esse?
    </p>
    <ul>
      <li>List item 1</li>
      <li>List item 2</li>
      <li>List item 3</li>
    </ul>

    <ol>
      <li>List item 1</li>
      <li>List item 2</li>
      <li>List item 3</li>
    </ol>
    <!--table-->
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Email</th>
          <th>Age</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>King ruta</td>
          <td>kingruta@gmail.com</td>
          <td>24</td>
        </tr>
        <tr>
          <td>Eric habi</td>
          <td>erichabi@gmail.com</td>
          <td>34</td>
        </tr>
        <tr>
          <td>Arsen jow</td>
          <td>arsenjow.com</td>
          <td>27</td>
        </tr>       
      </tbody>
    </table>

    <br>
    <hr>
    <br>

    <!--forms-->

    <form action="process.php" method="POST">
      <div>
        <label>First name</label>
        <input type="text" name="FirstName" placeholder="enter firstname">
      </div>
      <br>
      <div>
        <label>Last name</label>
        <input type="text" name="LastName" value="enter lastname">
      </div>
      <br>
      <div>
        <label>Email</label>
        <input type="email">
      </div>
      <br>
      <div>
        <label>Message</label>
        <textarea name="message"></textarea>
      </div>
      <br>
      <div>
        <label>Gender</label>
        <select name="gender" >
          <option value="Male">Male</option>
          <option value="female">Female</option>
          <option value="Other">other</option>

        </select>
      </div>
      <br>
      <div>
        <label >Age</label>
        <input type="number" name="age" placeholder="30">
      </div>
      <br>
      <div>
        <label >Birthday</label>
        <input type="date" name="Birthday" >
      </div>
      <br>
      <input type="submit" name="submit" value="submit">
    </form>
    <br>
    <button>Click me</button>
    <br>
    <!--image-->
    <a href="images/sample.jpg" target="_blank">
      <img src="images/sample.jpg" alt="My sample images" width="320px" height="320px">
    </a>
    <br>
    <!--quotation-->
    <blockquote cite="http://landryndizeye.com">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur neque saepe, aut enim praesentium, sapiente omnis minus officia ut eligendi at reprehenderit sequi optio id eius, ipsa eveniet ad dolore.
    </blockquote>
    <br>
    <p>The <abbr title="world wide web"> WWW </abbr> is awesome</p>
    <br>
    <p> <cite> Html crash course </cite> by landry ndizeye</p>
    <div style="margin-top:500px"></div>
  </body>
</html>
