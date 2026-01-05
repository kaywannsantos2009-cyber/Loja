<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NeoDrop | Futuristic Store</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --blue: #00e5ff;
      --dark: #050b14;
      --dark-2: #0b1627;
      --glass: rgba(0, 229, 255, 0.08);
    }* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  font-family: 'Inter', sans-serif;
  background: radial-gradient(circle at top, #0b1d33, var(--dark));
  color: #eaf6ff;
  overflow-x: hidden;
}

header {
  padding: 24px 48px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: linear-gradient(180deg, rgba(0,0,0,0.6), transparent);
  backdrop-filter: blur(6px);
}

.logo {
  font-family: 'Orbitron', sans-serif;
  font-size: 24px;
  font-weight: 800;
  color: var(--blue);
  letter-spacing: 2px;
}

nav a {
  margin-left: 28px;
  text-decoration: none;
  color: #cfefff;
  font-weight: 500;
  transition: 0.3s;
}

nav a:hover { color: var(--blue); }

.hero {
  min-height: 90vh;
  display: grid;
  place-items: center;
  text-align: center;
  padding: 40px;
}

.hero h1 {
  font-family: 'Orbitron', sans-serif;
  font-size: 56px;
  background: linear-gradient(90deg, #ffffff, var(--blue));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  margin-bottom: 20px;
}

.hero p {
  max-width: 640px;
  font-size: 18px;
  opacity: 0.9;
  margin-bottom: 32px;
}

.btn {
  padding: 14px 36px;
  border-radius: 40px;
  border: 1px solid var(--blue);
  background: linear-gradient(135deg
