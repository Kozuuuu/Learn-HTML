<template>
  <div>
    <h1>Hi Everyone! Welcome to my Profile Page!</h1>
    <h2>I'm Val Jayson Balagulan.</h2>

    <hr>
    <nav>
      <ul>
        <li>
          <a href="#aboutMe">Home</a>
        </li>
        <li>
          <a href="#experiences">Experiences</a>
        </li>
        <li>
          <a href="#hobbies">My Hobbies</a>
        </li>
        <li>
          <a href="#contact">My Contact Info</a>
        </li>
      </ul>
    </nav>


    <hr>

    <section Id = "aboutMe">
      <h3><strong>About Me:</strong></h3>
      <p>I'm 22 years old.</p>
      <p>I'm a Software Developer</p>
      <p>I'm from the Philippines.</p>
      <p>Graduated from <abbr title="University of Science and Technology of Southern Philippines"><a href="https://www.ustp.edu.ph/cdeo/">USTP</a></abbr></p>
      <p>I'm a degree holder of <em>Computer Engineering</em>.</p>
    </section>

    <section Id = "experiences">
      <hr>
      <p><strong>I have experience in:</strong></p>
      <ul>
        <li>Python</li>
        <li>Micro Python</li>
        <li>JavaScript</li>
        <li>Quasar</li>
        <li>Java</li>
        <li>Spring Boot</li>
        <li>Vue</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>C#</li>
        <li>C++</li>
        <li>MySQL</li>
        <li>PostgreSQL</li>
        <li>Assembly Language</li>
      </ul>
    </section>
    <hr>

    <section Id = "hobbies">
      <dl>
        <dt><strong>My Hobbies:</strong></dt>
        <dd>Watching Anime</dd>
        <dd>Watching Movies</dd>
        <dd>Reading Novels</dd>
        <dd>Reading Manga and Manhwa</dd>
        <dd>Playing video games</dd>
        <dd>Outdoor activities</dd>
      </dl>
    </section>

    <section Id = "contact">
      <hr>
      <h3>My Contact Info:</h3>
      <p><strong>Email:</strong> 06jaysang2002@gmail.com</p>
      <p><strong>Facebook:</strong> <abbr title="Facebook Link"><a href="https://www.facebook.com/valjaysonb">Val Jayson B.</a></abbr></p>
      <p><strong>Phone:</strong> +63 905 480 7610</p>
      <p><strong>Address:</strong></p>
      <address>
        Philippines
        <br>Misamis Oriental
        <br>Gingoog City
        <br>Brgy. 23, Purok 3
        <br>Cueto Street
        <br>ZipCode: 9014
      </address>
    </section>

    <hr>

    &lt;&lt;&lt; &copy; <a href="me.html">2024 Val Jayson B.</a> &gt;&gt;&gt;
  </div>
</template>

<script>
export default {
  name: 'Profile'
}
</script>

<style scoped>
/* Add component-specific styles here */
</style>
