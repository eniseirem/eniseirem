# Hi, That's me!
- > [Linkedin](https://www.linkedin.com/in/eniseirem/) [Medium](https://medium.com/@eniseirem) [Website](https://eniseirem.github.io/)

>"Talk is cheap. Show me the code."
> — I took it personally.

> Welcome to my GitHub. Here’s a playful look at me, via some pseudo-Python:
 

```python
import pandas as pd
import projects
import publications
import sklearn
import matplotlib.pyplot as plt

class EniseIremColak:
    name = "Enise İrem Çolak"
    title = "Data Scientist in progress"
    base = ["Istanbul", "Berlin"]
    interests = ["Explainable AI", "Genomics", "Data Visualization", "Pythonic workflows"]
    
    # 🎓 Education
    def education(self):
     return {
        "M.Sc. Data Science": {
            "university": "Freie Universität Berlin",
            "location": "Berlin, Germany",
            "years": "2024–2026",
            "status": "In Progress"
        },
        "M.Sc. Big Data": {
            "university": "Bahçeşehir University",
            "location": "Istanbul, Turkey",
            "years": "2020–2023",
            "status": "Completed"
        },
        "B.Sc. Software Engineering": {
            "university": "Bahçeşehir University",
            "location": "Istanbul, Turkey",
            "years": "2015–2019",
            "status": "Completed"
        }
    }

    # 💼 Experience
    def experience(self):
        return pd.DataFrame([
            {"role": "IT Assistant Specialist", "company": "Vakıfbank", "focus": "Machine Learning / Python", "duration": "2022–..."},
        ])

    # 🛠️ Tech Stack
    def tech_stack(self):
        return {
            "Languages": ["Python", "R", "PHP", "Julia"],
            "Frameworks": {
                        "Python": ["Pandas", "NumPy", "Scikit-learn", "Django"],
                        "PHP": ["Laravel"] },
            "Tools": ["Linux", "MySQL", "Weka"],
            "Currently Exploring": ["xAI for Genomics", "Interpretable ML", "Data ethics"]
        }

   # 🌍 Spoken Languages
    def languages_spoken(self):
        return {
            "Turkish": "Native",
            "English": "Professional",
            "Italian": "A1 - Espresso and greetings ☕️",
            "German": "A1 - In progress 🥨"
      }



```
*Disclaimer: This code won't compile — but my curiosity does.
inspiration : [ashbakernz](https://github.com/ashbakernz)*
