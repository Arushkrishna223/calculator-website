[script.js](https://github.com/user-attachments/files/30092549/script.js)
[styles.css](https://github.com/user-attachments/files/30092550/styles.css)[index.html](https://github.com/user-attachments/files/30092552/index.html)<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Simple Calculator</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="calculator">
    <input type="text" class="display" id="display" readonly aria-label="Calculator display" />
    <div class="buttons">
      <button class="btn action" data-action="clear">C</button>
      <button class="btn action" data-action="backspace">⌫</button>
      <button class="btn operator" data-value="(">(</button>
      <button class="btn operator" data-value=")">)</button>

      <button class="btn" data-value="7">7</button>
      <button class="btn" data-value="8">8</button>
      <button class="btn" data-value="9">9</button>
      <button class="btn operator" data-value="/">÷</button>

      <button class="btn" data-value="4">4</button>
      <button class="btn" data-value="5">5</button>
      <button class="btn" data-value="6">6</button>
      <button class="btn operator" data-value="*">×</button>

      <button class="btn" data-value="1">1</button>
      <button class="btn" data-value="2">2</button>
      <button class="btn" data-value="3">3</button>
      <button class="btn operator" data-value="-">−</button>

      <button class="btn" data-value="0">0</button>
      <button class="btn" data-value=".">.</button>
      <button class="btn equals" data-action="equals">=</button>
      <button class="btn operator" data-value="+">+</button>
    </div>
  </main>

  <script src="script.js"></script>
</body>
</html>
