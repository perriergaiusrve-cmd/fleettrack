<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Plan de Maintenance</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 20px;
    background: #f4f4f4;
}

h1 {
    text-align: center;
}

.container {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

th, td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

th {
    background: #2c3e50;
    color: white;
}

tr:nth-child(even) {
    background: #f2f2f2;
}

.urgent {
    background: #ffb3b3 !important;
}

.warning {
    background: #ffe0a3 !important;
}

.ok {
    background: #c6f7c6 !important;
}

input {
    padding: 8px;
    width: 300px;
}
</style>
</head>
<body>

<div class="container">
    <h1>Plan de Maintenance Annuel</h1>

    <input type="text" id="search" placeholder="Recherche équipement...">

    <table id="maintenanceTable">
        <thead>
            <tr>
                <th>Équipement</th>
                <th>Intervention</th>
                <th>Fréquence (h)</th>
                <th>Temps arrêt</th>
                <th>Pièces concernées</th>
                <th>Statut</th>
            </tr>
        </thead>
</html>
