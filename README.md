# 📊 CodeBook Data Analysis – Pure Python Project

A simple yet powerful data analysis project using **only core Python**.  
Analyze social network data from a fictional platform, **CodeBook**, and implement real-world features like friend recommendations and page suggestions — all without pandas or numpy.

---

## 📂 Dataset Overview

```json
{
  "users": [
    {"id": 1, "name": "Amit", "friends": [2, 3], "liked_pages": [101]},
    {"id": 2, "name": "Priya", "friends": [1, 4], "liked_pages": [102]},
    {"id": 3, "name": "Rahul", "friends": [1], "liked_pages": [101, 103]},
    {"id": 4, "name": "Sara", "friends": [2], "liked_pages": [104]}
  ],
  "pages": [
    {"id": 101, "name": "Python Developers"},
    {"id": 102, "name": "Data Science Enthusiasts"},
    {"id": 103, "name": "AI & ML Community"},
    {"id": 104, "name": "Web Dev Hub"}
  ]
}
```

🧠 Project Features
Load & parse JSON data using the json module
Display user info with names, friends, and liked pages
People You May Know: Suggest friends based on mutual connections
Pages You Might Like: Recommend pages liked by friends but not yet liked by the user

💡 How It Works
Users and pages are loaded into Python dictionaries for quick lookup
Mutual friends are calculated using set intersections
Page recommendations are derived from friend networks
Clean output printed using string formatting and basic loops

📌 Tools Used
Python 3.x
Built-in json module
No external libraries!

👨‍💻 Author
Anuj Saini
sainianuj@1235gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/anuj-saini-12464a24a/?jobid=1234

⭐️ Support This Project
If you found this useful, feel free to:
⭐ Star this repository
🍴 Fork it
🔁 Share with others




