<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RP Fehler (FRP) Lösungen</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="button-container">
        <button class="btn red" onclick="showSolution('frpSituation')">FRP Situation</button>
        <button class="btn blue" onclick="showSolution('rpSituation1')">RP Situation 1</button>
        <button class="btn green" onclick="showSolution('rpSituation2')">RP Situation 2</button>
        <button class="btn yellow" onclick="showSolution('rpSituation3')">RP Situation 3</button>
        <button class="btn purple" onclick="showSolution('rpSituation4')">RP Situation 4</button>
    </div>

    <!-- Pop-up Modal -->
    <div id="solutionPopup" class="popup">
        <div class="popup-content">
            <span class="close-btn" onclick="closePopup()">&times;</span>
            <div id="popup-text">Lösung wird hier angezeigt...</div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
