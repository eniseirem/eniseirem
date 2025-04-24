# Hi, That's me!
- > [Linkedin](https://www.linkedin.com/in/eniseirem/) [Medium](https://medium.com/@eniseirem)
> I've a sticker which says "Talk is cheap show me the code." 
> So here I am, showing you **The Code**.
>"Talk is cheap. Show me the code."
> — I took it personally.

> Welcome to my GitHub. Here’s a playful look at me, via some pseudo-Python:
 

```python
import pandas as pd
import projects
import publications
import sklearn
import matplotlib.pyplot as plt

class enise_irem_colak:
    name = "Enise İrem Çolak"
    title = "Data Scientist in progress"
    base = ["Istanbul", "Berlin"]
    interests = ["Explainable AI", "Genomics", "Data Visualization", "Pythonic workflows"]
    
    def linkedin(self):
        return "https://www.linkedin.com/in/eniseirem/"

    def education(self):
        return pd.DataFrame([
            {"degree": "B.Sc.", "field": "Software Engineering", "institution": "Bahçeşehir University", "years": "2015-2019"},
            {"degree": "M.Sc.", "field": "Big Data", "institution": "Bahçeşehir University", "years": "2020-2023"},
            {"degree": "M.Sc. (in progress)", "field": "Data Science", "institution": "Freie Universität Berlin", "years": "2024-2026"},
        ])

    def experience(self):
        return pd.DataFrame([
            {"role": "IT Assistant Specialist", "company": "Vakıfbank", "focus": "Machine Learning / Python", "duration": "2022–..."},
        ])

    def tech_stack(self):
        return {
            "Languages": ["Python", "R", "PHP", "Java", "C#", "Matlab", "Julia"],
            "Frameworks": {"Python": "Pandas, NumPy, Scikit-learn, Django", "PHP": "Laravel"},
            "Tools": ["Jupyter", "VSCode", "Git", "Linux", "MySQL", "Weka"],
            "Currently Exploring": ["xAI for Genomics", "Interpretable ML", "Data ethics"]
        }

    def languages_spoken(self):
        return {
            "Turkish": "Native",
            "English": "Professional",
            "Italian": "A1 - Espresso and greetings"
        }

    def visualize_life(self):
        plt.plot(["2015", "2019", "2023", "2025"], [1, 2, 3, 4])
        plt.title("Learning Curve")
        plt.xlabel("Year")
        plt.ylabel("Curiosity Level")
        plt.show()


```
*Disclaimer: This code won't compile — but my curiosity does.
inspiration : [ashbakernz](https://github.com/ashbakernz)*
