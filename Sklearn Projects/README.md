<div align="center">

<h1>Python Projects with Structured Data</h1>
<p>
    This repository includes projects using datasets of structured data (non-Spark). The projects use Python, NumPy, Pandas, Matplotlib, Seaborn, Sklearn, and Auto-Sklearn.
</p>

<h2>
    Auto-Sklearn
</h2>
<p>
    I saw a post about Auto-Sklearn on LinkedIn and wanted to try it. I have decided to use it as a baseline for comparison with my fine-tuned models of the same models. I am continuing to work through the Scikit-Learn/Sklearn versions of these projects as I have time. I intend to post them as I finish them.
</p>

<h2>
    Overview of Classification Projects in This Directory
</h2>

<table style="border: 3px solid black;">
<tr style="border-bottom: 2.5px solid black;">
    <th style="text-align: center;">
        Model Name
    </th>
    <th style="text-align: center;">
        Classification Type
    </th>
    <th style="text-align: center;">
        Auto-Sklearn?
    </th>
    <th style="text-align: center;">
        Accuracy
    </th>
    <th style="text-align: center;">
        F1
    </th>
    <th style="text-align: center;">
        Precision
    </th>
    <th style="text-align: center;">
        Recall
    </th>
    <th style="text-align: center;">
        Algorithm***
    </th>
</tr>

<tr>
    <td style="text-align: center">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/Airline%20Passenger%20Satisfaction/Airline_Passenger_Satisfaction.ipynb">
            Airline Passenger Satisfaction
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        0.96
    </td>
    <td style="text-align: center;">
        0.96
    </td>
    <td style="text-align: center;">
        0.97
    </td>
    <td style="text-align: center;">
        0.96
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/Promote%20Employee%20or%20Not/Promote%20Employee%20Or%20Not%20Binary%20Classifier%20(Using%20Sklearn%20Interface%20of%20XGBoost).ipynb">
            Promote Employee Or Not**
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        0.9027
    </td>
    <td style="text-align: center;">
        0.6974
    </td>
    <td style="text-align: center;">
        0.6986
    </td>
    <td style="text-align: center;">
        0.6963
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/Credit%20Card%20Fraud%20Detection/Credit_Card_Fraud_Detection.ipynb">
            Credit Card Fraud Detection
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        1.00
    </td>
    <td style="text-align: center;">
        0.92
    </td>
    <td style="text-align: center;">
        0.97
    </td>
    <td style="text-align: center;">
        0.88
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/Diabetes%20Prediction/Diabetes_Prediction_Dataset.ipynb">
            Diabetes Prediction
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        0.97
    </td>
    <td style="text-align: center;">
        0.89
    </td>
    <td style="text-align: center;">
        0.98
    </td>
    <td style="text-align: center;">
        0.84
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/HR%20Analytics%20-%20Job%20Change%20of%20Data%20Scientists/HR_Analytics_Job_Change_of_Data_Scientists_Auto_Sklearn.ipynb">
            HR Analytics - Job Change of Data Scientists
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        0.79
    </td>
    <td style="text-align: center;">
        0.72
    </td>
    <td style="text-align: center;">
        0.72
    </td>
    <td style="text-align: center;">
        0.72
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/Employee%20Turnover/Employee%20Turnover-Churn.ipynb">
            Employee Turnover
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        0.87***
    </td>
    <td style="text-align: center;">
        0.84***
    </td>
    <td style="text-align: center;">
        0.85***
    </td>
    <td style="text-align: center;">
        0.83***
    </td>
    <td style="text-align: center;">
        XGBoost
    </td>
</tr>
<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Binary%20Classification/Employee%20Turnover%20at%20TECHCO/Employee%20Turnover%20at%20TECHCO.ipynb">
            Employee Turnover at TECHCO
        </a>
    </td>
    <td style="text-align: center;">
        Binary
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        0.88
    </td>
    <td style="text-align: center;">
        0.87
    </td>
    <td style="text-align: center;">
        0.90
    </td>
    <td style="text-align: center;">
        0.86
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Multiclass%20Classification/Car%20Acceptability/Sklearn%20Version/Car%20Acceptability%20Classification-Sklearn.ipynb">
            Car Acceptability (Sklearn Version)
        </a>
    </td>
    <td style="text-align: center;">
        Multiclass
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        0.89
    </td>
    <td style="text-align: center;">
        0.82
    </td>
    <td style="text-align: center;">
        0.80
    </td>
    <td style="text-align: center;">
        0.85
    </td>
    <td style="text-align: center;">
        XGBoost
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Multiclass%20Classification/Car%20Acceptability/Auto-Sklearn%20Version/Car_Acceptability_Classification_Dataset_Auto_Sklearn.ipynb">
            Car Acceptability (Auto-Sklearn Version)
        </a>
    </td>
    <td style="text-align: center;">
        Multiclass
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        0.97
    </td>
    <td style="text-align: center;">
        0.90
    </td>
    <td style="text-align: center;">
        0.88
    </td>
    <td style="text-align: center;">
        0.94
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Classification/Multiclass%20Classification/Credit%20Scores/Credit_Score_Classification_Auto_Sklearn.ipynb">
            Credit Scores        
        </a>
    </td>
    <td style="text-align: center;">
        Multiclass
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        0.79
    </td>
    <td style="text-align: center;">
        0.78
    </td>
    <td style="text-align: center;">
        0.77
    </td>
    <td style="text-align: center;">
        0.78
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>
</table>

<p style="text-align: left">Notes:</p>
<ul style="text-align: left">
<li>* = F1, Precison, and Recall values are Macro-Averaged Values</li>
<li>** = Uses Sklearn's Interface of XGBoost</li>
<li>*** = Project was algorithm comparison. Name & metric values shown represent algorithm with best results</li>
</caption>

<br />

<h2>
    Overview of Regression Projects in This Directory
</h2>

<table style="border: 3px solid black;">
<tr style="border-bottom: 2.5px solid black;">
    <th style="text-align: center;">
        Model Name
    </th>
    <th style="text-align: center;">
        Auto-Sklearn?
    </th>
    <th style="text-align: center;">
        Mean Absolute Error
    </th>
    <th style="text-align: center;">
        Median Absolute Error
    </th>
    <th style="text-align: center;">
        Root Mean Squared Error
    </th>
    <th style="text-align: center;">
        Algorithm***
    </th>
</tr>
<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Vehicle%20MSRP%20Predictor/Regression%20Using%20Sklearn's%20Interface%20of%20XGBoost.ipynb">
            Vehicle MSRP Predictor**
        </a>
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        Not Shown
    </td>
    <td style="text-align: center;">
        Not Shown
    </td>
    <td style="text-align: center;">
        Not Shown
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Student%20Exam%20Scores/Math%20Scores%20Edition/Students_Exam_Scores_Math_Scores_Edition.ipynb"> 
            Student Exam Scores - Math Edition
        </a>
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        4.395
    </td>
    <td style="text-align: center;">
        3.697
    </td>
    <td style="text-align: center;">
        5.501
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Student%20Exam%20Scores/Reading%20Scores%20Edition/Students_Exam_Scores_Reading_Scores_Edition.ipynb">
            Student Exam Scores - Reading Edition
        </a>
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        3.309
    </td>
    <td style="text-align: center;">
        2.832
    </td>
    <td style="text-align: center;">
        4.113
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Student%20Exam%20Scores/Writing%20Scores%20Edition/Students_Exam_Scores_Writing_Scores_Edition.ipynb">
            Student Exam Scores - Writing Edition
        </a>
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        2.915
    </td>
    <td style="text-align: center;">
        2.462
    </td>
    <td style="text-align: center;">
        3.665
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/USA%20Real%20Estate%20Price%20Prediction/USA_Real_Estate_Dataset.ipynb">
            USA Real Estate Price Prediction
        </a>
    </td>
    <td style="text-align: center;">
        Yes
    </td>
    <td style="text-align: center;">
        39267.848
    </td>
    <td style="text-align: center;">
        18261.289
    </td>
    <td style="text-align: center;">
        217744.574
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Flight%20Price%20Prediction/Flight%20Price%20Prediction.ipynb">
            Flight Price Prediction
        </a>
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        4856.35
    </td>
    <td style="text-align: center;">
        -
    </td>
    <td style="text-align: center;">
        7122.315
    </td>
    <td style="text-align: center;">
        ElasticNet
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Medical%20Insurance%20Premium%20Prediction/Medical%20Insurance%20Premium%20Prediction.ipynb">
            Medical Insurance Premium Prediction
        </a>
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        2675.173
    </td>
    <td style="text-align: center;">
        -
    </td>
    <td style="text-align: center;">
        3693.946
    </td>
    <td style="text-align: center;">
        Stochastic Gradient Descent
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="https://github.com/DunnBC22/Python_Projects_with_Structured_data/blob/main/Sklearn%20Projects/Regression/Medical%20Insurance%20Payout%20Prediction/Medical%20Insurance%20Payout%20Prediction.ipynb">
            Medical Insurance Payout Prediction
        </a>
    </td>
    <td style="text-align: center;">
        No
    </td>
    <td style="text-align: center;">
        3395.251
    </td>
    <td style="text-align: center;">
        -
    </td>
    <td style="text-align: center;">
        6956.373
    </td>
    <td style="text-align: center;">
        Huber
    </td>
</tr>

</table>
<p>
    Notes:
</p>
<ul style="text-align: left">
    <li>** = Uses Sklearn's Interface of XGBoost</li>
    <li>*** = Project was algorithm comparison. Name & metric values shown represent algorithm with best results</li>
</ul>

</div>