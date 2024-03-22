```python
class DataAnalyst:
    def __init__(self, name, role):
        self.name, self.role, self.skills, self.tools, self.experience = name, role, [], [], []

    def add_skill(self, skill): self.skills += [skill]
    def add_tool(self, tool): self.tools += [tool]
    def add_exp(self, experience): self.experience += [experience]
    def display_output(self):
        print(f"I'm {self.name}, {self.role}\n\nSkills:\n" + "\n".join(f"- {s}" for s in self.skills)
                                                           + "\n\nToolset:\n"
                                                           + "\n".join(f"- {t}" for t in self.tools)
                                                           + "\n\nProfessional Experience:\n"
                                                           + "\n".join(f"- {e}" for e in self.experience))

pmusachio = DataAnalyst("Paulo Musachio", "and Turn Data into Insights!")
[pmusachio.add_skill(skill)    for skill in ["Problem Solving", "Structured Thinking", "Exploratory Data Analysis", "Storytelling"]]
[pmusachio.add_tool(tool)      for tool in ["Python", "SQL", "Excel", "Statistics", "BI and Dashboard"]]
[pmusachio.add_exp(experience) for experience in ["Business Analyst @NUBANK - credit and risk",
                                                  "Exploring Data and Solving Problems in Industry for +10 years"]]

pmusachio.display_output()
```
 <br/>
  <br/>
  
<details>
  <summary>RUN Code</summary>
  <br/>
  
  I'm Paulo Musachio, and Turn Data into Insights!

  Skills:
  - Problem Solving
  - Structured Thinking
  - Exploratory Data Analysis
  - Storytelling

  Toolset:
  - Python
  - SQL
  - Excel
  - Statistics
  - BI and Dashboard

  Profissional Experience:
  - Business Analyst @NUBANK - credit and risk
  - Exploring Data and Solving Problems in Industry for +10 years

</details>
