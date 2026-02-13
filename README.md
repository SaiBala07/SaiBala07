<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=36BCF7&background=00000000&center=true&vCenter=true&width=435&lines=Class+DataScientist(Human):;def+init(self):;self.name+%3D+'Bala+Sai+Krishna';self.passion+%3D+'Turning+Data+into+Insights'" alt="Typing SVG" />
  
  <p align="center">
    <a href="https://github.com/SaiBala07">
      <img src="https://komarev.com/ghpvc/?username=SaiBala07&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
    </a>
    <a href="https://linkedin.com/in/YOUR-LINKEDIN-ID">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:sai.velavarthipati@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

---

### 👨‍💻 `user_profile.py`

```python
class DataScientist:
    def __init__(self):
        self.name = "Bala Sai Krishna Velavarthipati"
        self.location = "Plano, TX"
        self.role = "Data Scientist @ U.S. Bank"
        self.education = "M.S. in Data Science & AI"
        
    def get_skills(self):
        return {
            "Languages": ["Python", "SQL", "R", "Scala"],
            "Big_Data": ["Spark", "Hadoop", "Kafka", "Databricks"],
            "Cloud": ["AWS", "Azure", "GCP", "Snowflake"],
            "Deep_Learning": ["TensorFlow", "PyTorch", "Transformers"]
        }

    def current_focus(self):
        return "Building scalable Fraud Detection systems & NLP pipelines"

me = DataScientist()
print(me.current_focus())
