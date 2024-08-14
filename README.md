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
[pmusachio.add_skill(skill)    for skill in ["Analytics", "Problem Solving", "Structured Thinking"]]
[pmusachio.add_tool(tool)      for tool in ["SQL", "SAS", "Spark", "Python", "Hadoop", "Statistics", "AWS (S3, Glue, Athena, Redshift, Quicksight and SageMaker)"]]
[pmusachio.add_exp(experience) for experience in ["Data Analyst @ITAÚ BBA - Credit",
                                                  "Business Analyst @NUBANK - Lending",
                                                  "Production Engineer @TOYOTA - Assembly Shop",
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
  - Analytics
  - Problem Solving
  - Structured Thinking

  Toolset:
  - SQL
  - SAS
  - Spark
  - Python
  - Hadoop
  - Statistics
  - AWS (S3, Glue, Athena, Redshift, Quicksight and SageMaker)

  Profissional Experience:
  - Data Analyst @ITAÚ BBA - Credit
  - Business Analyst @NUBANK - Lending
  - Production Engineer @TOYOTA - Assembly Shop
  - Exploring Data and Solving Problems in Industry for +10 years

</details>
