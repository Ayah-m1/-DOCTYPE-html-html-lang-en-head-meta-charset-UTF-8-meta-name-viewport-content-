# -DOCTYPE-html-html-lang-en-head-meta-charset-UTF-8-meta-name-viewport-content-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Risk Map</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .risk-map-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }
        .risk-map {
            display: grid;
            grid-template-columns: repeat(6, 100px);
            grid-template-rows: repeat(6, 100px);
            gap: 2px;
        }
        .cell {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            font-size: 14px;
            font-weight: bold;
        }
        .cell:nth-child(1) {
            background-color: white;
        }
        /* Color codes for severity */
        .low { background-color: #b6e7b6; } /* Light Green */
        .medium { background-color: #ffff99; } /* Yellow */
        .high { background-color: #ffc266; } /* Orange */
        .severe { background-color: #ff8080; } /* Red */
    </style>
</head>
<body>
    <h2>Risk Map</h2>
    <div class="risk-map-container">
        <div class="risk-map">
            <!-- First row for labels -->
            <div class="cell"></div>
            <div class="cell">1 (Minimum)</div>
            <div class="cell">2 (Lower)</div>
            <div class="cell">3 (Medium)</div>
            <div class="cell">4 (Critical)</div>
            <div class="cell">5 (Catastrophic)</div>
            
            <!-- Probability labels -->
            <div class="cell">Remote</div>
            <div class="cell low"></div>
            <div class="cell low"></div>
            <div class="cell medium"></div>
            <div class="cell medium"></div>
            <div class="cell severe">Environmental Risk</div>
            
            <div class="cell">Improbable</div>
            <div class="cell low"></div>
            <div class="cell medium"></div>
            <div class="cell medium"></div>
            <div class="cell severe"></div>
            <div class="cell severe">Legal Risk</div>
            
            <div class="cell">Occasional</div>
            <div class="cell low"></div>
            <div class="cell medium"></div>
            <div class="cell high"></div>
            <div class="cell severe"></div>
            <div class="cell severe"></div>
            
            <div class="cell">Probable</div>
            <div class-”>
