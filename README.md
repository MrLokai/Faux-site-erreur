<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erreur Critique</title>
    <style>
        body {
            background-color: #f2f2f2;
            text-align: center;
            font-family: Arial, sans-serif;
            padding-top: 20%;
        }
        .error-message {
            color: red;
            font-size: 24px;
            font-weight: bold;
        }
        .instructions {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="error-message">Erreur Critique : Votre ordinateur est infecté !</div>
    <div class="instructions">Veuillez redémarrer votre ordinateur immédiatement.</div>
    <script>
        window.onload = function() {
            setTimeout(function() {
                alert("Erreur Critique : Votre ordinateur est infecté !");
            }, 1000);
        };
    </script>
</body>
</html>
