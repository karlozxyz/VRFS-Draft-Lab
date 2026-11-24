
<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#09090d">
<title>VRFS Draft Lab | Maintenance</title>

<style>
:root {
  --bg: #09090d;
  --panel: #121219;
  --line: #292932;
  --text: #f4f4f7;
  --muted: #a5a5b2;
  --red: #ed343c;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
  padding: 24px;
  background:
    radial-gradient(ellipse at 50% 0%, #381116 0, transparent 48%),
    var(--bg);
  color: var(--text);
  font-family: Arial, sans-serif;
}

main {
  width: min(100%, 620px);
  text-align: center;
  padding: clamp(28px, 6vw, 54px);
  border: 1px solid var(--line);
  border-radius: 26px;
  background: linear-gradient(160deg, #17171f, #101015);
  box-shadow: 0 24px 80px #0009;
}

.logo {
  width: 112px;
  height: 112px;
  object-fit: contain;
  margin-bottom: 22px;
  filter: drop-shadow(0 0 24px #ed343c55);
}

.brand {
  font-size: 13px;
  font-weight: 800;
  letter-spacing: .2em;
  color: #d5d5dc;
  text-transform: uppercase;
}

.status {
  display: inline-flex;
  align-items: center;
  gap: 9px;
  margin: 28px 0 14px;
  padding: 8px 13px;
  border: 1px solid #743037;
  background: #31171b;
  border-radius: 999px;
  color: #ff9ca1;
  font-size: 12px;
  font-weight: 800;
  text-transform: uppercase;
}

.dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: #ff555d;
  box-shadow: 0 0 12px #ff555d;
}

h1 {
  font-size: clamp(30px, 6vw, 46px);
  margin: 0 0 16px;
}

p {
  color: var(--muted);
  line-height: 1.7;
  max-width: 450px;
  margin: auto;
  font-size: 15px;
}

.actions {
  display: flex;
  justify-content: center;
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 30px;
}

a, button {
  font: inherit;
  font-size: 14px;
  font-weight: 750;
  text-decoration: none;
  border-radius: 12px;
  padding: 13px 19px;
  cursor: pointer;
  transition: .18s;
}

.primary {
  color: white;
  background: linear-gradient(135deg, #f0444b, #a91e27);
  border: 1px solid #ff656b;
}

.secondary {
  color: #eee;
  background: #202029;
  border: 1px solid #393943;
}

a:hover, button:hover {
  transform: translateY(-2px);
  filter: brightness(1.12);
}

.note {
  margin-top: 30px;
  padding-top: 18px;
  border-top: 1px solid var(--line);
  font-size: 12px;
  color: #777783;
}
</style>
</head>

<body>
<main>

  <img class="logo" src="./logo.png" alt="VRFS Draft Lab Logo">

  <div class="brand">VRFS Draft Lab</div>

  <div class="status">
    <span class="dot"></span>
    Temporarily unavailable
  </div>

  <h1>We’ll be back soon.</h1>

  <p>
    VRFS Draft Lab is currently offline for maintenance
    or a server issue. Your drafts and progress are not
    being changed by this page. Please check back in a
    little while.
  </p>

  <div class="actions">
    <button class="primary" onclick="location.reload()">
      Try again
    </button>

    <a class="secondary" href="./index.html">
      Return to Draft Lab
    </a>
  </div>

  <div class="note">
    Thank you for your patience · VRFS Draft Lab
  </div>

</main>
</body>
</html>
