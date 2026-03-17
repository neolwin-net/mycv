<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sequence Screen</title>

<style>
  body {
    margin: 0;
    background: black;
    color: red;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  #container {
    text-align: center;
    font-size: 4vw;
  }

  .line {
    opacity: 0;
    margin: 10px 0;
  }

  .show {
    opacity: 1;
    transition: opacity 0.5s;
  }

  .final {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    font-size: 10vw;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
</head>

<body>

<div id="container">
  <div class="line">F</div>
  <div class="line">Fu</div>
  <div class="line">Fuc</div>
  <div class="line">Fuck</div>
  <div class="line">Fuck You</div>
</div>

<script>
  const lines = document.querySelectorAll('.line');
  let index = 0;

  function showNextLine() {
    if (index < lines.length) {
      lines[index].classList.add('show');
      index++;
      setTimeout(showNextLine, 500);
    } else {
      // Final full screen
      setTimeout(() => {
        document.body.innerHTML = '<div class=\"final\">Fuck You</div>';
      }, 800);
    }
  }

  showNextLine();
</script>

</body>
</html>
