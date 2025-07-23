<!DOCTYPE html>
<html lang="ar">
  <head>
    <title>My Beautiful Page</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
    <meta charset="UTF-8" />
    <!-- Font Awesome CSS (gives us the heart icon) -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css"
    />
    <style>
      /* Starting red heart */
      .heart {
        color: red;
        font-size: 200px;
        cursor: pointer;}

        
        /* Starting green frog */
        .frog {
        color: rgb(0, 255, 68);
        font-size: 250px;
        cursor: pointer;}

      /* Gray heart when not active */
      .gray {
        color: gray; }
        /* Blue frog when not active */
      .blue {
        color: blue; }
      
    </style>
  </head>
  <body>
    <!-- The heart icon -->
    <i class="fas fa-heart heart" id="heartIcon"></i>
    <i class="fas fa-frog frog" id="frogIcon"></i>

    <!-- JavaScript to toggle color -->
    <script>
      const heart = document.getElementById("heartIcon"); 
      const frog = document.getElementById("frogIcon");

      heart.addEventListener("click", function () {
        heart.classList.toggle("gray"); 
      });
        frog.addEventListener("click", function () {
            frog.classList.toggle("blue"); 
        });
    </script>
<!--Everything-->
  <header>
    <nav>
      <a href="#Home">Home</a>
      <a href="#About">About</a>
      <a href="#Contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="Home">
      <h1>This is a h1 Heading</h1>
      <h2>This is a h2 Heading</h2>
      <h3>This is a h3 Heading</h3>
      <h4>This is a h4 Heading</h4>
      <h5>This is a h5 Heading</h5>
      <h6>This is a h6 Heading</h6>
    </section>
    <section id="About">
      This is a <b>bold</b> tag test
      This is an <i>italic</i> tag test
      This is a <del>deleted</del> tag test
      <p>My first paragraph</p>
      <p>My second paragraph</p>'
      <h2 title="This is a subheading">Hello, World!</h2>
    </section>
    <section id="Contact">

      <!-- Incorrect img declaration  -->
      <img src="file:///C:/Users/Erslan/Pictures/Screenshots/Screenshot%202025-07-09%20093530.png" alt="A dog"> </img>
      <!-- Correct img declaration  -->
      <img src="file:///C:/Users/Erslan/Pictures/Screenshots/Screenshot%202025-07-09%20092945.png" alt="A dog"> '
      <a href="https://www.twitch.tv/">Take me to Twitch's Website</a>

      <a name="TopOfThePage"> </a>
      <h1>Link Up Top</h1>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iure in ducimus,
        tenetur facere repellendus ipsa beatae minus est laudantium nobis tempora
        suscipit sunt tempore reprehenderit nulla necessitatibus! Eius sed
        provident iusto dicta corrupti itaque, ducimus quo illo cupiditate,
        quaerat blanditiis, quod accusamus doloremque.

        Neque unde nostrum dignissimos ad quam ratione.
      </p>
    </section>
    <img src="Gomycode.png" alt="Gomycode" />
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit.


      Quia, consequuntur!
    </p>
    <img src="Track.jpg" alt="Gomycode">
    <a href="#TopOfThePage"> Let's go up Top </a>
<audio controls>
  <source src="" type="audio/mpeg">
  Please Check the audio Extension
</audio>
<video width="320" height="240" autoplay>
  <source src="test.mp4" type="video/mp4" />
  Please Check the video extension.
</video>
<iframe width="420" height="315" src="https://www.youtube.com/embed/zcTFG_F0FRs"></iframe>
<h1>Web Languages</h1>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ul>
<h1>Tracks At GoMyCode</h1>

<!-- Disc bullets -->
<ul type="disc">
  <li>AI Track</li>
  <li>Web Track</li>
  <li>Game Track</li>
  <li>Data Science Track</li>
</ul>

<!-- Square bullets -->
<ul type="square">
  <li>AI Track</li>
  <li>Web Track</li>
  <li>Game Track</li>
  <li>Data Science Track</li>
</ul>
<h1>Web Ordered Languages:</h1>
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ol>
<!-- Upper-case Roman Numerals -->
<ol type="I">
  <li>Create a folder named "GoMyCode" on your Desktop</li>
  <li>Create a new folder in GoMyCode folder name it whatever you want.</li>
  <li>Create a new folder inside it and name it "res"</li>
  <li>Create a new folder inside it and name it "css"</li>
</ol>
<p>The House Sigils In GOT:</p>

<dl>
  <dt>House Stark</dt>
  <dd>The Direwolf</dd>

  <dt>House Lannister</dt>
  <dd>The Lion</dd>

  <dt>House Targaryen</dt>
  <dd>The Three-Headed Dragon</dd>

  <dt>House Baratheon</dt>
  <dd>The Stag</dd>
</dl>
<div>
  <h1>This is the first division</h1>
</div>
<div>
  <h1>This is the second division</h1>
</div>
<table border="1">
  <tr>
    <th>HTML</th>
    <th>CSS</th>
    <th>JS</th>
  </tr>
  <tr>
    <td>Paragraphs</td>
    <td>Selectors</td>
    <td>DOM</td>
  </tr>
  <tr>
    <td>Tables</td>
    <td>Styles</td>
    <td>Elements</td>
  </tr>
</table>
<nav>
  <a href="/html/> HTML </a>
<a href=" /css /> CSS </a>
  <a href="/js/> JavaScript </a>
<a href=" /jquery /> jQuery </a>
</nav>
<section>
  <h1> Contact information <h1>
      <p> Go My Code is an EdTech Startup.. </p>
</section>
<article>
  <h1> What is the perks of being a Web Developer? <h1>
      <!-- Article contents -->
</article>
<form>
  <label>Name:</label>
  <input type="text" name="first name" placeholder="Type your name here" />



  <label>Number:</label>
  <input type="number" name="number" value="23123456" />



  <label>Birth Date:</label>
  <input type="date" name="birthday" />



  <label>Password:</label>
  <input type="password" name="password" />



  <input type="submit" value="Submit" />
</form>
<form>
  Search <input type="text" name="search" />
</form>
<select>
  <option value="WebTrack">Web Track</option>
  <option value="AITrack">AI Track</option>
  <option value="GameTrack">Game Track</option>
  <option value="DataScienceTrack">Data Science Track</option>
</select>
<textarea name="message" cols="30" rows="5">
        Welcome to GoMyCode
    </textarea>
<form>
  <label>First Name:</label>
  <input type="text" name="firstName" />


  <label>Last Name:</label>
  <input type="text" name="lastName" id="lastName" />
  </main>
  <footer>
    <!-- This button will submit the form, causing the page to redirect -->
    <button type="submit">Submit Name</button>
  </footer> 
  </form>
  </body>
  </html>
