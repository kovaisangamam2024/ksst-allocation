<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>KSST Parayanam Allocation</title>

<style>
body {
  font-family: "Segoe UI", sans-serif;
  background: linear-gradient(to bottom, #fff8e7, #fceabb);
  text-align: center;
  padding: 20px;
}

h2 {
  color: #8b0000;
}

input, textarea {
  width: 90%;
  max-width: 450px;
  padding: 10px;
  margin: 8px 0;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 14px;
}

textarea {
  height: 140px;
}

button {
  padding: 10px 16px;
  margin: 6px;
  border: none;
  border-radius: 6px;
  font-weight: bold;
  cursor: pointer;
  font-size: 14px;
}

.green { background: #2e8b57; color: white; }
.blue { background: #1e90ff; color: white; }
.orange { background: #ff8c00; color: white; }
.red { background: #b22222; color: white; }

#result {
  margin-top: 20px;
  background: white;
  padding: 15px;
  border-radius: 8px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
  text-align: left;
  box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
}
</style>
</head>

<body>

<h2>🌸 KSST Parayanam Allocation 🌸</h2>

<input type="text" id="batch" placeholder="Batch Number (Optional)">
<input type="text" id="date" placeholder="Satsang Date & Time (Optional)">

<textarea id="names" placeholder="Enter names (one per line)"></textarea>
<br>

<button class="green" onclick="allocateSequential()">Allocate</button>
<button class="blue" onclick="allocateRandom()">Alloc Randomly</button>
<button class="orange" onclick="allocateOnRoll()">Alloc on-Roll</button>
<button class="green" onclick="copyResult()">Copy</button>
<button class="red" onclick="downloadCSV()">Download CSV</button>

<div id="result"></div>

<script>

const sections = [
"Starting Prayer",
"Mahalakshmi Ashtakam",
"Poorvanga 1-22",
"Nyasa",
"Dhyanam 1-8",
"Sloka 1-108",
"Phalashruti 1-33",
"Ending Prayer"
];

function getNames() {
  return document.getElementById("names").value
    .split("\n")
    .map(n => n.trim())
    .filter(n => n !== "");
}

function headerText() {
  let batch = document.getElementById("batch").value;
  let date = document.getElementById("date").value;
  let header = "🌸 KSST Parayanam Allocation 🌸\n\n";
  if (batch) header += "Batch: " + batch + "\n";
  if (date) header += "Date: " + date + "\n";
  header += "\n";
  return header;
}

function allocateSequential() {
  let names = getNames();
  let output = headerText();
  for (let i = 0; i < names.length; i++) {
    output += (i+1) + ". " + names[i] + " – " + sections[i % sections.length] + "\n";
  }
  display(output);
}

function allocateRandom() {
  let names = getNames();
  names.sort(() => Math.random() - 0.5);
  let output = headerText();
  for (let i = 0; i < names.length; i++) {
    output += (i+1) + ". " + names[i] + " – " + sections[i % sections.length] + "\n";
  }
  display(output);
}

function allocateOnRoll() {
  let names = getNames();
  let output = headerText();
  for (let i = 0; i < names.length; i++) {
    output += (i+1) + ". " + names[i] + " – Sloka " + (i+1) + "\n";
  }
  display(output);
}

function display(text) {
  document.getElementById("result").innerText = text;
}

function copyResult() {
  let text = document.getElementById("result").innerText;
  navigator.clipboard.writeText(text);
  alert("Allocation copied successfully 🙏");
}

function downloadCSV() {
  let content = document.getElementById("result").innerText;
  let blob = new Blob([content], { type: 'text/csv' });
  let link = document.createElement("a");
  link.href = URL.createObjectURL(blob);
  link.download = "ksst_allocation.csv";
  link.click();
}

</script>

</body>
</html>
