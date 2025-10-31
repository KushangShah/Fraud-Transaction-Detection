<!-- ============================= -->
<!-- 🏢 Company Header -->
<!-- ============================= -->
<div align="left" style="margin-bottom: 30px;">
  <img height="40px" src="images/UM_Logo.png" alt="Unified Mentor Private Limited" style="vertical-align:middle;">
  <span style="font-size:18px; margin-left:10px; font-weight:bold; color:#333;">Unified Mentor Private Limited</span>
</div>
<br>

<!-- ============================= -->
<!-- 🎯 Project Banner -->
<!-- ============================= -->
<div align="center" style="margin-bottom: 20px;">
  <img src="images/banner.png" alt="Project Banner" width="450" height="250" style="border-radius: 16px; box-shadow: 0px 4px 10px rgba(0,0,0,0.2);">
</div>

<!-- ============================= -->
<!-- 🧠 Project Title -->
<!-- ============================= -->
<h1 align='center' style="margin-bottom: 0;">
  <img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&weight=500&size=28&duration=5500&pause=1000&color=00FFFF&center=true&random=false&width=700&lines=Fraud+Transaction+Detection" alt="Fraud Transaction Detection" />
</h1>

<h3 align='center' style="margin-top: 0; font-weight: normal;">
  <img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&weight=100&size=16&duration=5500&pause=1000&color=00FFFF&center=true&random=false&width=600&lines=Machine+Learning+Project" alt="Machine Learning Project" />
</h3>

<hr style="border: 1px solid #00FFFF; width: 60%; margin: auto;">
<br>

<!-- ============================= -->
<!-- 📋 Table of Contents -->
<!-- ============================= -->
<h2 style="text-align:center;">📑 Table of Contents</h2>
<ul style="font-size:15px; line-height:1.8;">
  <li>About This Project</li>
  <li>Problem Statement</li>
  <li>What the Dataset Contains</li>
  <li>Main Libraries Used</li>
  <li>Visualizations & Charts</li>
  <li>Conclusion</li>
  <li>Acknowledgments</li>
</ul>
<br>
<hr>

<!-- ============================= -->
<!-- 📘 About This Project -->
<!-- ============================= -->
<h2>📘 About This Project</h2>
<p style="font-size:15px; line-height:1.7; text-align:justify;">
The goal of this project is to <b>develop a system that can classify transactions as fraudulent or legitimate</b>.  
The dataset used is a simulated collection of transaction data designed to mimic real-world scenarios of online financial fraud.
</p>

<p style="font-size:15px; line-height:1.7; text-align:justify;">
The simulated frauds are based on the following conditions:
</p>

<ol style="font-size:15px; line-height:1.7;">
  <li><b>High Transaction Amounts:</b> Any transaction where <code>TX_AMOUNT &gt; 220</code> is marked as fraud.  
  This pattern helps validate basic fraud detection behavior.</li><br>
  <li><b>Compromised Terminals:</b> Two terminals are randomly selected daily, and all transactions processed through them for the next 28 days are labeled as fraud — simulating terminal-based fraud scenarios.</li><br>
  <li><b>Compromised Customers:</b> Three customers are randomly chosen each day; one-third of their transactions are multiplied by 5 in value and marked as fraudulent — simulating stolen-card or “card-not-present” fraud.</li>
</ol>

<p style="font-size:15px; line-height:1.7;">
This project was developed as part of the <b>Machine Learning Internship</b> at <b>Unified Mentor Private Limited</b>.
</p>

<hr><br>

<!-- ============================= -->
<!-- ❓ Problem Statement -->
<!-- ============================= -->
<h2>❓ Problem Statement</h2>
<p style="font-size:15px; line-height:1.8; text-align:justify;">
Financial fraud is one of the fastest-growing threats in today’s digital economy. Every second, hundreds of online transactions occur — but how can we determine which are genuine and which are fraudulent?
</p>

<ul style="font-size:15px; line-height:1.8;">
  <li>🤔 Can machines learn to identify fraudulent transactions within milliseconds?</li>
  <li>💳 Which data patterns can expose hidden fraud activities?</li>
  <li>📊 How do features like transaction amount, terminal ID, or spending behavior distinguish legitimate from fraudulent activity?</li>
  <li>🚨 Can models detect frauds that even humans might overlook?</li>
  <li>🧠 Can a system evolve over time as fraudsters change their tactics?</li>
</ul>

<hr><br>

<!-- ============================= -->
<!-- 🧾 Dataset Description -->
<!-- ============================= -->
<details open>
  <summary style="font-size: 20px; text-align:center; font-weight:bold;">📊 What the Dataset Contains</summary>
  <br>
  <p style="font-size:15px; line-height:1.7; text-align:left;">
    <b>1.</b> <code>TRANSACTION_ID</code> – Unique identifier for each transaction.<br><br>
    <b>2.</b> <code>TX_DATETIME</code> – Date and time of the transaction.<br><br>
    <b>3.</b> <code>CUSTOMER_ID</code> – Unique identifier for each customer.<br><br>
    <b>4.</b> <code>TERMINAL_ID</code> – Unique identifier for each merchant terminal.<br><br>
    <b>5.</b> <code>TX_AMOUNT</code> – The monetary value of the transaction.<br><br>
    <b>6.</b> <code>TX_FRAUD</code> – Binary label: <code>1</code> for fraudulent, <code>0</code> for legitimate.<br>
  </p>
</details>

<hr><br>

<!-- ============================= -->
<!-- 🧩 Libraries Used -->
<!-- ============================= -->
<details open> 
  <summary style="font-size: 20px; text-align:center; font-weight:bold;">🧩 Main Libraries Used</summary> 
  <br> 
  <p style="font-size:15px; line-height:1.7;">
  🔢 <b>NumPy</b> – For fast numerical computations and array manipulation.<br>
  📊 <b>Pandas</b> – For efficient data loading, cleaning, and analysis.<br>
  📈 <b>Matplotlib & Seaborn</b> – For creating insightful visualizations.<br>
  🧪 <b>SciPy</b> – For statistical testing and outlier analysis.<br>
  ⚙️ <b>scikit-learn</b> – For preprocessing, model training, evaluation, and resampling.<br>
  🚀 <b>XGBoost & LightGBM</b> – For optimized gradient boosting and ensemble learning.<br>
  💾 <b>pickle & joblib</b> – For model saving and reusability.<br>
  🧱 <b>sys, os</b> – For system-level operations.<br>
  ⏱️ <b>datetime & deque</b> – For handling time-based features and data structures.<br>
  🔄 <b>tqdm</b> – For progress tracking during model training.<br>
  🚫 <b>Warnings</b> – For clean and uncluttered notebook output.<br>
  </p>
</details>

<hr><br>

<!-- ============================= -->
<!-- 📉 Visualizations Section -->
<!-- ============================= -->
<details open>
  <summary style="font-size: 20px; text-align:center; font-weight:bold;">📉 Visualizations & Charts</summary>
  <br>
  <p align="center">
    <img src="images/chart_5.png" alt="Chart 1" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/chart_3.png" alt="Chart 2" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/chart_13.png" alt="Chart 3" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/chart_14.png" alt="Chart 4" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/missing_value.png" alt="Chart 5" width="400" height="160" style="border-radius: 20px; margin: 10px;">
    <img src="images/ML_model.png" alt="Chart 6" width="400" style="border-radius: 20px; margin: 10px;">
  </p>
</details>

<hr><br>

<!-- ============================= -->
<!-- 🧾 Conclusion Section -->
<!-- ============================= -->
<details open>
  <summary style="font-size: 22px; text-align:center; font-weight:bold;">📘 Conclusion</summary>
  <br>
  <!-- (Insert the previously enhanced Conclusion section here — no need to repeat) -->
</details>

<hr><br>

<!-- ============================= -->
<!-- 🙏 Acknowledgment -->
<!-- ============================= -->
<h3>🙏 Acknowledgments</h3>
<p style="font-size:14px; line-height:1.6; text-align:justify;">
This project applies machine learning techniques to understand and predict fraudulent transactions.  
Sincere thanks to <b>Unified Mentor Private Limited</b> for the opportunity to work on this research-oriented project.  
Special appreciation to the open-source community for creating the tools and libraries that make such innovations possible.
</p>

<p align="right" style="font-size:13px;">Created with 🧠 by 
  <a href="https://github.com/KushangShah" target="_blank">Kushang Shah</a>
</p>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=kushang&label=Profile%20views&color=00FFFF&style=flat-square" alt="Profile views"/>
</p>
