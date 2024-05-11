### Hi I am Umar, 👋
- 🔭 I’m currently working as Freelancer.
- 🌱 I’m currently Mastering Backend Development.
- 👯 I’m looking to collaborate on Full Stack Role.
- 🤔 I’m looking for help in Data Science.
- 💬 Ask me about Web Developmemt.
- 📫 Reach me out: <a href="https://www.linkedin.com/in/ch-umar-aslam-b84686252">LinkedIn</a>
- ⚡ Fun fact:Passionate about innovation and problem solving and curious to dive into the world of Data Science.
 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      @import url("https://fonts.googleapis.com/css?family=Muli&display=swap");

      * {
        box-sizing: border-box;
      }

      body {
        background-color: #2d3342;
        color: #fff;
        font-family: "Muli", sans-serif;
        flex-direction: column;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        margin: 0;
      }

      h1 {
        font-size: 70px;
        margin: 0;
      }

      p {
        color: rgba(247, 131, 131, 0.8);
        letter-spacing: 2px;
        margin: 0;
      }
    </style>
  </head>

  <body>
    <p>This page was viewed</p>
    <h1 id="count">0</h1>
    <p>times</p>

    <script>
      const countEl = document.getElementById("count");
      countvisits();

      function countvisits() {
        fetch('https://api.countapi.xyz/update/laptop/mouse/?amount=1')
          .then((res) => res.json())
          .then((res) => {
            countEl.innerHTML = res.value;
          });
      }
    </script>
  </body>
</html>



