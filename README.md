# Liliastradingfacility
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0d0d0d;
  color: #f5f5f5;
}

header {
  background: #111;
  text-align: center;
  padding: 60px 20px;
}

header h1 {
  font-size: 3em;
  color: gold;
}

header p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.btn {
  background: gold;
  color: #111;
  padding: 12px 24px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.services, .plans {
  padding: 40px 20px;
  text-align: center;
}

.services ul {
  list-style: none;
  padding: 0;
}

.services li {
  font-size: 1.1em;
  margin: 10px 0;
}

.plan-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.plan {
  background: #1a1a1a;
  padding: 20px;
  border: 1px solid gold;
  border-radius: 10px;
}

.btc {
  margin-top: 30px;
  color: gold;
}

footer {
  text-align: center;
  padding: 20px;
  background: #111;
  color: #aaa;
}

.signup-container {
  max-width: 400px;
  margin: 100px auto;
  background: #1a1a1a;
  padding: 30px;
  border: 1px solid gold;
  border-radius: 10px;
}

.signup-container h2 {
  text-align: center;
  margin-bottom: 20px;
}

.signup-container input, .signup-container button {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  border-radius: 5px;
  border: none;
}

.signup-container input {
  background: #f5f5f5;
}

.signup-container button {
  background: gold;
  color: #111;
  font-weight: bold;
}
