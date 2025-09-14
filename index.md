---
layout: home
title: "Turning Data into Stories"
author_profile: true
---

# About Me

Hi, I'm **Devika 👋**  
I analyze data with SQL, Excel, Power BI, and Python to find clear, actionable insights.  
I enjoy transforming raw numbers into visual stories that help businesses make better decisions.

---

# Projects

<div class="tab-container">

  <!-- Tabs -->
  <div class="tabs">
    <button class="tablink" onclick="openTab(event, 'powerbi')">Power BI</button>
    <button class="tablink" onclick="openTab(event, 'sql')">SQL</button>
    <button class="tablink" onclick="openTab(event, 'excel')">Excel</button>
  </div>

  <!-- Tab content -->
  <div id="powerbi" class="tabcontent">
    <h3>Power BI Projects</h3>
    <p>📊 Sales Dashboard</p>
    <p>📊 Customer Retention Analysis</p>
  </div>

  <div id="sql" class="tabcontent" style="display:none">
    <h3>SQL Projects</h3>
    <p>🗂 Danny’s Diner Case Study</p>
    <p>🗂 E-commerce Analysis</p>
  </div>

  <div id="excel" class="tabcontent" style="display:none">
    <h3>Excel Projects</h3>
    <p>📑 Financial Modeling</p>
    <p>📑 Survey Data Analysis</p>
  </div>

</div>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>

<style>
.tab-container { margin-top: 1em; }
.tabs { display: flex; justify-content: space-around; margin-bottom: 1em; }
.tablink {
  flex: 1;
  text-align: center;
  background: #eee;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 12px 20px;
  font-size: 16px;
  transition: 0.3s;
}
.tablink:hover { background: #ddd; }
.tablink.active { background: #ccc; }
.tabcontent { padding: 1em; border-top: 1px solid #ccc; }
</style>

---

# Contact

📧 [Email me](mailto:devikapassi19@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/devika-passi/)  
💻 [GitHub](https://github.com/devika-pss)
