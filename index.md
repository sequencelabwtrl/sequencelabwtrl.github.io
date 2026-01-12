<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ICMR Grants Call 2026 - Lab Portal</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            color: white;
            margin-bottom: 40px;
            padding: 20px;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }
        
        header p {
            font-size: 1.2em;
            opacity: 0.95;
        }
        
        .grants-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .grant-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .grant-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        }
        
        .grant-header {
            margin-bottom: 25px;
        }
        
        .grant-number {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
            margin-bottom: 15px;
        }
        
        .grant-title {
            font-size: 1.5em;
            color: #2d3748;
            margin-bottom: 10px;
            line-height: 1.4;
        }
        
        .deadline {
            background: #fed7d7;
            color: #c53030;
            padding: 10px 15px;
            border-radius: 8px;
            font-weight: bold;
            display: inline-block;
            margin-top: 10px;
        }
        
        .deadline-icon {
            margin-right: 5px;
        }
        
        .grant-details {
            margin-top: 20px;
        }
        
        .detail-section {
            margin-bottom: 20px;
        }
        
        .detail-section h3 {
            color: #4a5568;
            font-size: 1.1em;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        
        .detail-section h3::before {
            content: "▶";
            margin-right: 8px;
            color: #667eea;
        }
        
        .budget-info, .duration-info {
            background: #f7fafc;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #667eea;
            margin-bottom: 15px;
        }
        
        .budget-info strong, .duration-info strong {
            color: #2d3748;
        }
        
        .research-types {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .research-tag {
            background: #e6fffa;
            color: #234e52;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            border: 1px solid #81e6d9;
        }
        
        .apply-button {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            margin-top: 10px;
        }
        
        .apply-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }
        
        footer {
            text-align: center;
            color: white;
            padding: 20px;
            margin-top: 40px;
            opacity: 0.9;
        }
        
        @media (max-width: 768px) {
            .grants-container {
                grid-template-columns: 1fr;
            }
            
            header h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🔬 ICMR Grants Call 2026</h1>
            <p>Laboratory Research Funding Opportunities</p>
        </header>

        <div class="grants-container">
            
            <!-- ==================== GRANT 1 - START ==================== -->
            <div class="grant-card">
                <div class="grant-header">
                    <span class="grant-number">Grant Call #1</span>
                    <h2 class="grant-title">ICMR SMALL Extramural Grants<br>("ICMR ANVESHAN Extramural Grants")</h2>
                    <div class="deadline">
                        <span class="deadline-icon">⏰</span>
                        Deadline: March 16, 2026 at 5:00 PM IST
                    </div>
                </div>
                
                <div class="grant-details">
                    <div class="detail-section">
                        <h3>Duration & Funding</h3>
                        <div class="budget-info">
                            <strong>Budget Range:</strong> ₹10 Lakhs to less than ₹2 Crores
                        </div>
                        <div class="duration-info">
                            <strong>Project Duration:</strong> Maximum 3 years
                        </div>
                    </div>
                    
                    <div class="detail-section">
                        <h3>Supported Research Types</h3>
                        <div class="research-types">
                            <span class="research-tag">Discovery Research</span>
                            <span class="research-tag">Development Research</span>
                            <span class="research-tag">Delivery Research</span>
                            <span class="research-tag">Descriptive Research</span>
                        </div>
                    </div>
                    
                    <div class="detail-section">
                        <a href="https://www.icmr.gov.in/icmrobject/uploads/Call/1767267794_calladvtsmallanveshangrants202601jan20256.pdf" target="_blank" class="apply-button">
                            📄 View Full Announcement
                        </a>
                    </div>
                </div>
            </div>
            <!-- ==================== GRANT 1 - END ==================== -->

            <!-- ==================== GRANT 2 - START ==================== -->
            <div class="grant-card">
                <div class="grant-header">
                    <span class="grant-number">Grant Call #2</span>
                    <h2 class="grant-title">ICMR Intermediate Extramural Grants<br>("ICMR NISCHAYAK ANVESHAN Extramural Grants")</h2>
                    <div class="deadline">
                        <span class="deadline-icon">⏰</span>
                        Deadline: March 20, 2026 at 5:00 PM IST
                    </div>
                </div>
                
                <div class="grant-details">
                    <div class="detail-section">
                        <h3>Duration & Funding</h3>
                        <div class="budget-info">
                            <strong>Budget Range:</strong> ₹2 Crores to less than ₹8 Crores
                        </div>
                        <div class="duration-info">
                            <strong>Project Duration:</strong> Maximum 4 years
                        </div>
                    </div>
                    
                    <div class="detail-section">
                        <h3>Supported Research Types</h3>
                        <div class="research-types">
                            <span class="research-tag">Discovery Research</span>
                            <span class="research-tag">Development Research</span>
                            <span class="research-tag">Delivery Research</span>
                            <span class="research-tag">Descriptive Research</span>
                        </div>
                    </div>
                <div class="detail-section">
                        <a href="https://www.icmr.gov.in/icmrobject/uploads/Call/1767267845_calladvtintermediatenischayakanveshangrants202601jan2026.pdf" target="_blank" class="apply-button">
                            📄 View Full Announcement
                        </a>
                    </div>
                </div>
            </div>
            <!-- ==================== GRANT 2 - END ==================== -->

            <!-- ==================== ADD MORE GRANTS BELOW ==================== -->
            <!-- Copy the grant-card structure above and paste here for new grants -->
            
        </div>

        <footer>
            <p>For more information, visit the official ICMR website</p>
            <p style="margin-top: 10px; font-size: 0.9em;">Last Updated: January 2026</p>
        </footer>
    </div>
</body>
</html>
