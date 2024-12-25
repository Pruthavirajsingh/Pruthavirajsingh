## Hey there! 🤗 I'm Pruthavirajsingh D, a passionate wanna-be developer 😆

“Code is like humour. When you have to explain it, it’s bad.” – Cory House

🛠️ Tech Stack
Here’s what’s in my toolkit:

🌐 Languages: JavaScript, Python, Java, C, HTML & CSS
⚙️ Frameworks & Libraries: React, Node.js, Django
🛢️ Databases: SQL, MongoDB
🛠️ Tools: Git, VS Code
☁️ Cloud: AWS, Azure

✉️ Reach me at mathsxpruthaviraj@gmail.com 

[![GitHub Streak](https://streak-stats.demolab.com?user=Pruthavirajsingh&locale=hi&hide_total_contributions=true&hide_longest_streak=true)](https://git.io/streak-stats)

<hr>
<h2 align="center">🔥 Languages & Frameworks & Tools & Abilities 🔥</h2>
<br>
<p align="center">
  <code><img title="C" height="25" src="images/c.svg"></code>
  <code><img title="C++" height="25" src="images/cpp.svg"></code>
  <code><img title="C#" height="25" src="images/cSharp.svg"></code>
  <code><img title="Python" height="25" src="images/python-original.svg"></code>
  <code><img title="Django" height="25" src="images/django.png"></code>
  <code><img title="Javascript" height="25" src="images/javascript.svg"></code>
  <code><img title="Problem Solving" height="25" src="images/problemSolving.png"></code>
  <code><img title="HTML5" height="25" src="images/html5.svg"></code>
  <code><img title="CSS" height="25" src="images/css.svg"></code>
  <code><img title="SASS" height="25" src="images/sass.svg"></code>
  <code><img title="Gulp" height="25" src="images/gulp.svg"></code>
  <code><img title="React" height="25" src="images/react-original.svg"></code>
  <code><img title="Redux" height="25" src="images/redux.svg"></code>
  <code><img title="AngularJS" height="25" src="images/angularjs.png"></code>
  <code><img title="Git" height="25" src="images/git-original.svg"></code>
  <code><img title=".NetCore" height="25" src="images/dotnetcore.svg"></code>
  <code><img title="PostgreSQL" height="25" src="images/postgresql.svg"></code>
  <code><img title="Visual Studio Code" height="25" src="images/vscode.png"></code>
  <code><img title="Microsoft Visual Studio" height="25" src="images/visualstudio.png"></code>
  <code><img title="JQuery" height="25" src="images/jquery-original.svg"></code>
  <code><img title="Java" height="25" src="images/java-original.svg"></code>
  <code><img title="JSON" height="25" src="images/json.svg"></code>
  <code><img title="Unity" height="25" src="images/unity3d.svg"></code>
  <code><img title="Android" height="25" src="images/android.svg"></code>
  <code><img title="GitHub" height="25" src="images/github.svg"></code>
  <code><img title="MySQL" height="25" src="images/mysql.svg"></code>
  <code><img title="npm" height="25" src="images/npm.svg"></code>
  <code><img title="PHP" height="25" src="images/php.svg"></code>
  <code><img title="Flask" height="25" src="images/flask.png"></code>
</p>
<hr>

# Data for the table
data = [
    ["1,000", "10,000", "₹150,000", "₹4.5M", "₹54M"],
    ["10,000", "100,000", "₹1.5M", "₹45M", "₹540M"],
    ["100,000", "1,000,000", "₹15M", "₹450M", "₹5.4B"],
    ["1 Million", "10,000,000", "₹150M", "₹4.5B", "₹54B"],
    ["10 Million", "150,000,000", "₹1.5B", "₹45B", "₹540B"]
]

# Headers for the table
headers = ["Volume", "Transactions/Day", "Daily Margin", "Monthly Revenue", "Yearly Revenue"]

# Markdown file path
file_path = "profitability_table.md"

# Generate the markdown table
with open(file_path, "w") as md_file:
    # Write the headers
    md_file.write("| " + " | ".join(headers) + " |\n")
    md_file.write("|" + " --- |" * len(headers) + "\n")

    # Write the rows
    for row in data:
        md_file.write("| " + " | ".join(row) + " |\n")

print(f"Markdown table has been saved to {file_path}")

