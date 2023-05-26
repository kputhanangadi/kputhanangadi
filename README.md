<div align="center">
  <a href="#">
    <img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=ffffff20&height=65&section=header"/>
  </a>
</div>
<h1 align="center"> Nice to meet you, I'm Kevin!</h1>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=18&center=true&vCenter=true&width=485&lines=Electrical+and+Computer+Eningeering+@+UBC;Software+Engineering+Intern+@+EPSON;Looking+Foward+to+Connecting+with+You!" alt="Electrical and Computer Eningeering @ UBC" />
</p>

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

## Some of My GitHub Stats
<p align="center">
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=kputhanangadi&show_icons=true&theme=chartreuse-dark&layout=compact&hide_border=true" alt="kputhanangadi" /> 
<img width="56%" src="https://github-readme-streak-stats.herokuapp.com/?user=kputhanangadi&theme=highcontrast&hide_border=true" alt="kputhanangadi" />
</p>

## Where to Find Me
<p align="center">
<img alt="Youtube" src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" /></a><a href="mailto:kputhanangadi@gmail.com" target="_blank"><a href="https://github.com/kputhanangadi" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a><a href="https://www.linkedin.com/in/kputhanangadi" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a><a href="https://youtube.com/@kputhanangadi" target="_blank"><img alt="Email" src="https://img.shields.io/badge/Email-%23EA4335.svg?&style=for-the-badge&logo=gmail&logoColor=white" /></a><a href="https://open.spotify.com/user/n9cckn20twtn2b5a3zhu0bme7" target="_blank"><img alt="Spotify" src="https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white" /></a>
</p>
