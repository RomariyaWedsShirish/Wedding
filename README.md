<!DOCTYPE html>
<html>
  <head>
    <title>Our Wedding</title>
  </head>
  <body>
    <header>
      <h1>Emily & John's Wedding</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#details">Details</a></li>
          <li><a href="#rsvp">RSVP</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About Us</h2>
        <p>We are thrilled to announce our wedding on June 20, 2022! Join us as we start our journey together.</p>
      </section>
      <section id="details">
        <h2>Wedding Details</h2>
        <ul>
          <li>Date: June 20, 2022</li>
          <li>Time: 5:00 PM</li>
          <li>Location: Grand Ballroom, Downtown Hilton</li>
        </ul>
      </section>
      <section id="rsvp">
        <h2>RSVP</h2>
        <p>Please RSVP by May 20, 2022.</p>
        <form action="submit_rsvp.php" method="post">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name"><br><br>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email"><br><br>
          <label for="attending">Will you be attending?</label>
          <input type="radio" id="attending_yes" name="attending" value="yes">
          <label for="attending_yes">Yes</label>
          <input type="radio" id="attending_no" name="attending" value="no">
          <label for="attending_no">No</label><br><br>
          <input type="submit" value="Submit RSVP">
        </form>
      </section>
    </main>
    <footer>
      <p>Copyright &copy; 2022 Emily & John</p>
    </footer>
  </body>
</html>
