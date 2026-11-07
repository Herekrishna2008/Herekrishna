
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 20px;
  font-family: Arial, sans-serif;
  background: #101827;
  color: white;
}

.app {
  max-width: 500px;
  margin: auto;
}

header {
  text-align: center;
  background: #172b45;
  padding: 20px;
  border-radius: 15px;
  margin-bottom: 20px;
}

header h2 {
  color: #42d6a4;
}

section, .card {
  background: #1d2a3d;
  padding: 18px;
  margin-bottom: 15px;
  border-radius: 12px;
}

input {
  width: 100%;
  padding: 13px;
  margin: 8px 0;
  border: 1px solid #52647a;
  border-radius: 8px;
}

button {
  width: 100%;
  padding: 13px;
  margin-top: 10px;
  background: #16b887;
  color: white;
  border: none;
  border-radius: 8px;
  font-weight: bold;
}

.hidden {
  display: none;
}

.tree {
  text-align: center;
  padding: 15px 0;
}

.root {
  background: #16b887;
  padding: 12px;
  border-radius: 8px;
}

.branches {
  display: flex;
  gap: 10px;
  margin-top: 25px;
}

.node {
  flex: 1;
  padding: 15px 5px;
  background: #304966;
  border-radius: 8px;
  font-size: 13px;
}
