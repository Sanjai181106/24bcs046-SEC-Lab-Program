<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Stopwatch</title>
<style> 
#display {
font-size: 2em; 
margin-bottom: 20px;
}
</style>
</head>
<body>
<h2>JavaScript Stopwatch</h2>
<p id="display">00:00</p>
<button onclick="start()">Start</button>
<button onclick="stop()">Stop</button>
<button onclick="reset()">Reset</button>
<script>
let seconds = 0; // Total time in seconds
let intervalId = null; // Stores the timer reference
// Formats and updates the display 
function updateDisplay() {
const mins = String(Math.floor(seconds / 60)).padStart(2, '0'); 
const secs = String(seconds % 60).padStart(2, '0');
document.getElementById("display").textContent = `${mins}:${secs}`;
}
// Start function 
function start() {
if (!intervalId) { // Only start if not already running 
intervalId = setInterval(() =>seconds++; 
updateDisplay();
}, 1000);
}
}
// Stop function 
function stop() {
clearInterval(intervalId); 
intervalId = null;
}
// Reset function 
function reset() {
stop(); // Stop the timer 
seconds = 0; // Reset the counter 
updateDisplay(); // Refresh display
}
</script>
</body>
</html>
