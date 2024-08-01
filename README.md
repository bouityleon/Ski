<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Échange MTN Mobile Money Congo Brazzaville - Perfect Money</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
        h1 {
            color: #333;
        }
        form {
            background: #f4f4f4;
            padding: 20px;
            border-radius: 5px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"], input[type="number"], select {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
        }
        input[type="submit"] {
            background: #333;
            color: #fff;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Échange MTN Mobile Money Congo Brazzaville - Perfect Money</h1>
        <form id="exchangeForm">
            <label for="direction">Direction de l'échange:</label>
            <select id="direction" name="direction">
                <option value="mtn_to_pm">MTN Mobile Money vers Perfect Money</option>
                <option value="pm_to_mtn">Perfect Money vers MTN Mobile Money</option>
            </select>

            <label for="amount">Montant à échanger:</label>
            <input type="number" id="amount" name="amount" required>

            <label for="mtnNumber">Numéro MTN Mobile Money:</label>
            <input type="text" id="mtnNumber" name="mtnNumber" required>

            <label for="pmAccount">Compte Perfect Money:</label>
            <input type="text" id="pmAccount" name="pmAccount" required>

            <input type="submit" value="Effectuer l'échange">
        </form>
    </div>

    <script>
        document.getElementById('exchangeForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Ici, vous ajouteriez la logique pour traiter l'échange
            // Par exemple, envoyer les données à un serveur backend pour traitement
            
            alert('Demande d'échange soumise. Un opérateur va traiter votre demande.');
        });
    </script>
</body>
</html>
