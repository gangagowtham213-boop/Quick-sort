<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Quick Sort Performance Analyzer</title>

<style>
body {
    font-family: Arial;
    background: linear-gradient(to right, #36d1dc, #5b86e5);
    text-align: center;
    color: white;
}

.container {
    margin-top: 80px;
    background: rgba(0,0,0,0.3);
    padding: 30px;
    width: 320px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 12px;
}

input {
    padding: 10px;
    width: 80%;
    margin: 10px 0;
    border: none;
    border-radius: 5px;
}

button {
    padding: 10px 20px;
    background: #ff9800;
    border: none;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #e68900;
}

.result {
    margin-top: 20px;
    font-size: 18px;
}
</style>

</head>
<body>

<h1>Quick Sort Performance Analyzer</h1>

<div class="container">
    <input type="number" id="size" placeholder="Enter number of elements">
    <br>
    <button onclick="analyze()">Run Analysis</button>

    <div class="result" id="output">Result will appear here</div>
</div>

<script>
function quickSort(arr) {
    if (arr.length <= 1) return arr;

    let pivot = arr[Math.floor(arr.length / 2)];
    let left = [], right = [], equal = [];

    for (let num of arr) {
        if (num < pivot) left.push(num);
        else if (num > pivot) right.push(num);
        else equal.push(num);
    }

    return [...quickSort(left), ...equal, ...quickSort(right)];
}

function analyze() {
    let size = document.getElementById("size").value;

    if (!size || size <= 0) {
        alert("Please enter a valid number!");
        return;
    }

    let arr = [];
    for (let i = 0; i < size; i++) {
        arr.push(Math.floor(Math.random() * 1000));
    }

    let start = performance.now();
    quickSort(arr);
    let end = performance.now();

    let time = (end - start).toFixed(4);

    document.getElementById("output").innerHTML =
        "Sorted " + size + " elements in <b>" + time + " ms</b>";
}
</script>

</body>
</html>
