<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #333;
            color: #fff;
        }

        h1, h3 {
            text-align: center;
            color: #007bff;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        p {
            text-align: center;
            line-height: 1.6;
            margin-bottom: 20px;
            font-style: italic;
        }

        .dashboard-images {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }

        .dashboard-container {
            margin-bottom: 40px;
            text-align: center;
        }

        .dashboard-container img {
            max-width: 100%;
            height: auto;
            border: none;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease;
        }

        .dashboard-container img:hover {
            transform: scale(1.05);
        }

        .dashboard-container h4 {
            margin-top: 20px;
            font-size: 18px;
            color: #ffa500;
        }

        .dashboard-container p { font-size: 16px; color: #000;
        }
    </style>
</head>
<body>
    

    <div class="dashboard-container">
        <img src="https://raw.githubusercontent.com/Prabhu-Raj-Samraj/PrabhuRaj-DataPortfolio/main/Dashboard%201.png" alt="Main Dashboard">
        <h4>Main Dashboard</h4>
        <p>This dashboard provides an overview of barrels produced, throughput capacity, and key trends over the years.</p>
    </div>

    <div class="dashboard-container">
        <img src="https://raw.githubusercontent.com/Prabhu-Raj-Samraj/PrabhuRaj-DataPortfolio/main/Dashboard%202.png" alt="Apportionment Dashboard">
        <h4>Apportionment Dashboard</h4>
        <p>This dashboard highlights apportionment percentages, accepted nominations, and pipeline utilization insights.</p>
    </div>

    <div class="dashboard-container">
        <img src="https://raw.githubusercontent.com/Prabhu-Raj-Samraj/PrabhuRaj-DataPortfolio/main/Dashboard%203.png" alt="Export and Import Dashboard">
        <h4>Export and Import Dashboard</h4>
        <p>Focused on trade insights, this dashboard visualizes export and import trends by year, product, and region.</p>
    </div>
</body>
