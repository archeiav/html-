<!DOCTYPE html>
<html lang="en">
  <head>
    <!--Link ng mga fonts and icons----->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Agbalumo&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Agbalumo&family=Quicksand:wght@500;600&display=swap"
      rel="stylesheet"
    />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <title>About Me</title>
    <style>
      body {
        background-color: #fffbf5;
        margin: 0;
        padding: 0;
      }

      .intro {
        background-image: url(https://i.pinimg.com/originals/50/45/b8/5045b8ba1f9a0d8712c91256b64f38ab.jpg);
      }

      header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-family: Agbalumo;
      }

      .name {
        font-size: 30px;
        margin-left: 30px;
      }

      .nav {
        display: flex;
        width: 300px;
        justify-content: space-between;
        font-size: 20px;
        margin-right: 30px;
      }

      .title {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 50px;
        padding-bottom: 150px;
      }

      .title h1 {
        font-size: 80px;
        font-family: Quicksand;
        font-weight: 400;
        margin: 0px 0px;
      }

      .title h1:hover {
        background-image: linear-gradient(
          to right,
          #4f5bd5,
          #962fbf,
          #d62976,
          #fa7e1e,
          #feda75
        );
      }

      .title h2 {
        margin-top: 20px;
        font-weight: 100;
        text-align: center;
        font-size: 30px;
      }

      @keyframes education {
        0% {
          background-color: #d8c277;
        }
        25% {
          background-color: #fffbf5;
        }
        50% {
          background-color: pink;
        }
        75% {
          background-color: rgb(248, 248, 98);
        }
        100% {
          background-color: rgb(241, 157, 241);
        }
      }

      .education {
        display: flex;
        background-color: #d8c277;
        padding: 100px 60px 100px 60px;
        justify-content: space-between;
        border-top: solid white;
        border-bottom: solid white;
        animation-name: education;
        animation-duration: 5s;
        animation-iteration-count: 10;
      }

      .education div {
        display: flex;
        flex-direction: column;
        align-items: center;
      }

      .qcu {
        width: 550px;
        filter: grayscale(20%);
        border-radius: 5px;
        margin-right: 30px;
      }

      .p-1 {
        font-size: 45px;
        font-family: Quicksand;
      }

      .p-2 {
        font-size: 20px;
        text-align: center;
        font-family: Quicksand;
      }

      .hobbies {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 100px 0px 200px 0px;
      }

      .head-hob {
        font-size: 45px;
        font-family: Quicksand;
        margin-bottom: 80px;
      }

      .hobs {
        display: flex;
        justify-content: space-between;
      }

      .hob-1,
      .hob-2,
      .hob-3 {
        display: flex;
        flex-direction: column;
        align-items: center;
      }

      .hob-1 img,
      .hob-2 img,
      .hob-3 img {
        height: 210px;
      }

      .hob-1 img,
      .hob-2 img {
        margin-right: 50px;
      }

      .hob-1 p,
      .hob-2 p,
      .hob-3 p {
        font-family: Quicksand;
        font-size: 20px;
      }

      .fa {
        padding: 15px;
        font-size: 30px;
        width: 30px;
        text-align: center;
        text-decoration: none;
        margin: 5px 2px;
      }

      .fa-facebook {
        background: #3b5998;
        color: white;
      }

      .fa-twitter {
        background: #55acee;
        color: white;
      }

      .fa-instagram {
        background: #125688;
        color: white;
      }

      footer {
        background-color: black;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 50px 20px 50px 20px;
      }

      footer p {
        color: white;
        font-size: 30px;
        font-family: Quicksand;
      }
    </style>
  </head>
  <body>
    <div class="intro">
      <header>
        <p class="name">Angel</p>
        <div class="nav">
          <p class="about">About</p>
          <p class="blog">Blogs</p>
          <p class="contact">Contact</p>
        </div>
      </header>
      <div class="title">
        <h1>Get To Know Me</h1>
        <h2>
          Hi, I am Angel B. Vargas! 18 years old. <br />Have fun knowing me
          through this simple website.
        </h2>
      </div>
    </div>

    <!--Ito yung box that contains education background ko-->
    <div class="education">
      <img
        class="qcu"
        src="https://media.tenor.com/zFYlcnyDzhkAAAAd/student-studying.gif"
      />
      <div>
        <p class="p-1">Education</p>
        <p class="p-2">
          I am currently a freshman at Quezon City University taking a program
          of Bachelor of Science in Information Technology. <br /><br />
          Graphic designing is the beat of my heart. And taking BSIT is one of
          the best ways to get there. It was in junior high school when I got
          curious about the design of different mobile apps.
        </p>
      </div>
    </div>

    <!--This box contains my hobbies/interests-->
    <div class="hobbies">
      <div class="head-hob">Hobbies</div>
      <div class="hobs">
        <div class="hob-1">
          <img
            src="https://anerdyperspective.files.wordpress.com/2018/12/Anime-watching-tv-gif.gif"
          />
          <p>Watching Movies</p>
        </div>
        <div class="hob-2">
          <img
            src="https://media.tenor.com/xVViyqEwNo0AAAAC/game-video-games.gif"
          />
          <p>Playing Online Games</p>
        </div>
        <div class="hob-3">
          <img src="https://media.tenor.com/2JmJoLmAJdQAAAAC/read-anime.gif" />
          <p>Reading Books</p>
        </div>
      </div>
    </div>

    <!--Footer that contains my social media account links-->
    <footer>
      <p>Social Media</p>
      <div>
        <a
          href="https://www.facebook.com/profile.php?id=100091664123851"
          target="_blank"
          class="fa fa-facebook"
        ></a>
        <a
          href="https://twitter.com/angel5087316322"
          target="_blank"
          class="fa fa-twitter"
        ></a>
        <a
          href="https://www.instagram.com/archeiav/"
          target="_blank"
          class="fa fa-instagram"
        ></a>
      </div>
    </footer>
  </body>
</html>
