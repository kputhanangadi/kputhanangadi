<div align="center">
  <a href="#">
    <img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=ffffff20&height=65&section=header"/>
  </a>
</div>
<h1 align="center"> Nice to meet you, I'm Kevin!</h1>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=18&center=true&vCenter=true&width=485&lines=Electrical+and+Computer+Eningeering+@+UBC;Software+Development+Engineering+Intern+@+EPSON;Looking+Foward+to+Connecting+with+You!" alt="Electrical and Computer Eningeering @ UBC" />
</p>

<!--
**kputhanangadi/kputhanangadi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```python
class GitHubBio:
    def __init__(kevin):
        kevin.name = "Kevin Puthanangadi"
        kevin.location = "Vancouver, BC"
        kevin.internship_experience = [
            {
                "company":  "EPSON",
                "position": "Software Development Intern",
                "duration": "Summer 2023"
            },
            {
                "company":  "ROBOKIDS",
                "position": "Software Engineering Intern",
                "duration": "Summer 2022"
            }
        ]
        kevin.education = [
            {
                "university": "The University of British Columbia",
                "major":      "Electrical and Computer Engineering",
                "graduation": "May 2025"
            }
        ]
        kevin.fields_of_interests = [
            "Software Development",
            "Machine Learning",
            "Automonus Vehicles",
            "Space Exploration",
            "Game Development"
        ]
        kevin.technical_skills = [
            "Python",
            "MATLAB",
            "C/C++",
            "Java",
            "JavaScript",
            "HTML",
            "CSS",
            "Git"
        ]
        kevin.currently_learning = ["Tensorflow"]
        kevin.currently_working_on = ["Personal Website"]
        kevin.goals_2023 = ["Create projects and learn at least 5 new technologies."]
        kevin.hobbies = ["Hackathons", "Video Games", "Movies", "Stocks/Trading"]
        
    def display_bio(kevin):
        bio_dict = kevin.__dict__
        for key, value in bio_dict.items():
            if isinstance(value, list):
                print(key + ":")
                [print(f"- {item}") for item in value]
            elif isinstance(value, dict):
                print(key + ":")
                [print(f"- {k}: {v}") for k, v in value.items()]
            else:
                print(f"{key}: {value}")

if __name__ == '__main__':
    GitHubBio_instance = GitHubBio()
    GitHubBio_instance.display_bio()
```

## My Stats
<p align="center">
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=kputhanangadi&show_icons=true&theme=chartreuse-dark&layout=compact&hide_border=true" alt="kputhanangadi" /> 
<img width="56%" src="https://github-readme-streak-stats.herokuapp.com/?user=kputhanangadi&theme=highcontrast&hide_border=true" alt="kputhanangadi" />
</p>

## 📈 &nbsp;My GitHub History!</h2>
![Snake animation](https://github.com/kputhanangadi/kputhanangadi/blob/output/github-contribution-grid-snake.svg)

<div align="center">
  <a href="#">
    <img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=ffffff20&height=65&section=footer"/>
  </a>
</div>


