<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telecom Customer Churn Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-image: url('https://raw.githubusercontent.com/Deepanshu-analyst/Telecom-Chrun-Analysis/main/R.jpeg'); /* Raw image URL */
            background-size: cover; /* Ensure the image covers the entire background */
            background-repeat: no-repeat; /* Prevent the image from repeating */
            background-position: center; /* Center the image */
            color: #fff; /* Change text color for better readability on a background image */
        }
        h1, h2 {
            color: #ffffff; /* White color for headings */
            text-align: center;
        }
        h3 {
            color: #d65f0e; /* Orange color for subheadings */
        }
        ul {
            list-style-type: none; /* Remove default bullets */
            padding: 0; /* Remove default padding */
        }
        li {
            background: rgba(226, 226, 226, 0.8); /* Light gray background with some transparency */
            margin: 10px 0; /* Space between items */
            padding: 10px; /* Padding inside items */
            border-radius: 5px; /* Rounded corners */
            transition: background 0.3s; /* Smooth transition */
        }
        li:hover {
            background: rgba(217, 217, 217, 0.9); /* Darker gray on hover */
        }
        iframe {
            display: block;
            margin: 20px auto; /* Center the iframe */
            border: 2px solid #ffffff; /* Border for the iframe */
            border-radius: 5px; /* Rounded corners */
        }
        .recommendations {
            background-color: rgba(208, 240, 192, 0.9); /* Light green background for recommendations */
            padding: 15px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>📊 Telecom Customer Churn Analysis</h1>
    <p>This repository contains an <strong>Exploratory Data Analysis (EDA)</strong> of a telecom company's <strong>customer churn</strong> data. 🚀 Churn refers to customers discontinuing their services, a phenomenon that can hurt a company's bottom line. In this report, we'll dive deep into the factors driving churn and explore possible strategies for retention. Ready? Let’s go!</p>

    <h2>📋 Dataset Overview:</h2>
    <ul>
        <li><strong>Customer Demographics:</strong> Gender, SeniorCitizen, Partner, Dependents, etc.</li>
        <li><strong>Service Subscriptions:</strong> From PhoneService to OnlineSecurity.</li>
        <li><strong>Churn Status:</strong> The target variable indicating whether a customer left.</li>
    </ul>

    <h2>🔄 Data Preprocessing:</h2>
    <ul>
        <li>Dealt with missing values. ✅</li>
        <li>Converted categorical data into numbers for better analysis. 🔢</li>
    </ul>

    <h2>📈 Key Insights:</h2>
    <ul>
        <li><strong>Senior Citizens and Short-Tenure Customers are at Risk:</strong> Senior citizens and customers with a tenure of less than a year tend to churn the most. 🎯</li>
        <li><strong>Service Features Matter:</strong> Customers lacking services like Online Security or Tech Support are more likely to churn. This is a golden opportunity to promote or bundle these features. 📦</li>
        <li><strong>Price Sensitivity:</strong> Customers with higher monthly charges tend to churn more often. This points to dissatisfaction with pricing or perceived value. 💸</li>
    </ul>

    <div class="recommendations">
        <h2>💡 Recommendations:</h2>
        <ul>
            <li><strong>Supercharge Your Service Offerings:</strong> Bundle and promote value-added services like Online Security and Tech Support to keep customers hooked. 🛡️</li>
            <li><strong>Personalized Retention for Senior Citizens and New Customers:</strong> Launch loyalty programs or personalized retention strategies for these vulnerable groups. 🎁</li>
            <li><strong>Reassess Pricing Strategy:</strong> To curb churn among high-paying customers, consider offering loyalty discounts or more flexible pricing models. 💡</li>
        </ul>
    </div>

    <h2>📊 The Full Report Awaits:</h2>
    <p>For the detailed analysis and all the juicy insights, head over to the full report:</p>
    <iframe src="https://deepanshu-analyst.github.io/Telecom-Chrun-Analysis/Final%20Report%20on%20Telecom%20Churn%20Analysis.html" width="100%" height="600px"></iframe>
    
    <p>👉 <strong><a href="https://github.com/Deepanshu-analyst/Telecom-Chrun-Analysis">Click here to access the final report 📈</a></strong></p>

</body>
</html>
