# excel-dashboards
Company landing site 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Excel Insights & Interactive Dashboards</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f0fdf4; /* Soft Excel green tint */
            color: #1e293b;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 40px 20px;
        }
        .container {
            text-align: center;
            background: #ffffff;
            padding: 45px 35px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(16, 185, 129, 0.12);
            max-width: 520px;
            width: 100%;
            border: 2px solid #10b981; /* Excel green accent border */
        }
        .badge {
            display: inline-block;
            background-color: #d1fae5;
            color: #065f46;
            font-size: 13px;
            font-weight: 700;
            padding: 6px 16px;
            border-radius: 50px;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        h1 {
            font-size: 28px;
            font-weight: 800;
            margin-bottom: 12px;
            color: #0f172a;
            line-height: 1.2;
        }
        .tagline {
            font-size: 16px;
            color: #475569;
            margin-bottom: 25px;
            line-height: 1.5;
        }
        
        /* Dashboard Visual Placeholder */
        .dashboard-preview {
            background: #f8fafc;
            border: 1px dashed #cbd5e1;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 25px;
        }
        .preview-title {
            font-size: 13px;
            font-weight: 700;
            color: #64748b;
            text-transform: uppercase;
            margin-bottom: 12px;
            letter-spacing: 0.5px;
        }
        .mock-dashboard {
            display: flex;
            flex-direction: column;
            gap: 10px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 6px;
            padding: 15px;
        }
        .mock-row {
            display: flex;
            gap: 10px;
        }
        .mock-kpi {
            flex: 1;
            height: 40px;
            background: #e2e8f0;
            border-radius: 4px;
        }
        .mock-kpi.green { background: #a7f3d0; }
        .mock-chart {
            height: 100px;
            background: #f1f5f9;
            border-radius: 4px;
            width: 100%;
            position: relative;
            overflow: hidden;
            display: flex;
            align-items: flex-end;
            justify-content: space-around;
            padding: 10px;
        }
        .mock-bar {
            width: 18%;
            background: #34d399;
            border-radius: 3px 3px 0 0;
        }
        
        .services-list {
            text-align: left;
            background: #f8fafc;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 25px;
            border: 1px solid #e2e8f0;
        }
        .services-list h3 {
            font-size: 14px;
            color: #64748b;
            text-transform: uppercase;
            margin-bottom: 12px;
            letter-spacing: 0.5px;
        }
        .service-item {
            display: flex;
            align-items: center;
            font-size: 15px;
            color: #334155;
            margin-bottom: 8px;
            font-weight: 500;
        }
        .service-item:last-child {
            margin-bottom: 0;
        }
        .service-item::before {
            content: "✓";
            color: #10b981;
            font-weight: bold;
            margin-right: 10px;
            font-size: 16px;
        }
        
        /* Undercut Guarantee Details */
        .guarantee-box {
            font-size: 14px;
            color: #475569;
            background-color: #fef3c7; /* Soft amber */
            border: 1px solid #fde68a;
            padding: 12px;
            border-radius: 8px;
            margin-bottom: 30px;
            font-weight: 500;
        }

        /* Dressed Up Button Style */
        .form-button {
            display: block;
            background: linear-gradient(135deg, #10b981 0%, #059669 100%);
            color: #ffffff;
            text-decoration: none;
            padding: 18px 36px;
            font-size: 17px;
            font-weight: 700;
            border-radius: 8px;
            width: 100%;
            transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 4px 15px rgba(5, 150, 105, 0.3);
            letter-spacing: 0.2px;
        }
        .form-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 22px rgba(5, 150, 105, 0.4);
            filter: brightness(1.05);
        }
        .form-button:active {
            transform: translateY(0);
            box-shadow: 0 4px 10px rgba(5, 150, 105, 0.3);
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Value Proposition Banner -->
        <div class="badge">💰 5% Price Match Undercut</div>
        
        <h1>Turn Raw Data Into Interactive Dashboards</h1>
        <p class="tagline">Stop staring at messy spreadsheets. Get professional visual data insights that let you make better choices, legacy-free.</p>
        
        <!-- Live Dashboard Finished Concept View -->
        <div class="dashboard-preview">
            <div class="preview-title">Interactive Dashboard Example</div>
            <div class="mock-dashboard">
                <div class="mock-row">
                    <div class="mock-kpi green"></div>
                    <div class="mock-kpi"></div>
                    <div class="mock-kpi"></div>
                </div>
                <div class="mock-chart">
                    <div class="mock-bar" style="height: 40%;"></div>
                    <div class="mock-bar" style="height: 65%;"></div>
                    <div class="mock-bar" style="height: 50%;"></div>
                    <div class="mock-bar" style="height: 85%;"></div>
                    <div class="mock-bar" style="height: 95%;"></div>
                </div>
            </div>
        </div>

        <!-- Core Excel Services Offered -->
        <div class="services-list">
            <h3>Our Premium Data Services</h3>
            <div class="service-item">Interactive Excel & PowerBI Dashboards</div>
            <div class="service-item">Automated Reporting & Dynamic Charts</div>
            <div class="service-item">Data Cleaning & Spreadsheet Repair</div>
            <div class="service-item">Custom Formula & Macro Development</div>
        </div>
        
        <!-- Explaining how the 5% off works -->
        <div class="guarantee-box">
            💡 <strong>How to save:</strong> Present any competitor's quote inside the intake form, and we will instantly deduct 5% off their price.
        </div>
        
        <!-- REPLACE THE URL BELOW WITH YOUR GOOGLE FORM LINK -->
        <a href="https://google.com" target="_blank" class="form-button">Claim Your 5% Discount Quote</a>
    </div>

</body>
</html>