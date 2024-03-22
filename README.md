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

<h1>Main Projects</h1>

<br>

<!-- project06 -->
<h2 align="center"> renovacao de seguros </h2>

<a href="https://github.com/pmusachio/renovacao_seguros" >
<img width="199" align="left" src="https://github.com/pmusachio/private/blob/main/img/cover_06b.jpeg" ></a>

A SeguraAí é uma fintech de venda de seguros para pessoas físicas. Empresas de Seguros, assim como qualquer outra, dependem da recorrência de gastos dos seus clientes. Neste projeto de dados vamos entender quais fatores de risco estão associados com a NÃO renovação de seguros além de criar possíveis planos de ação para a empresa de seguros diminuir esse problema.

<br><br><br>

<!-- project05 -->
<h2 align="center"> controle da inadimplencia em operacoes de credito </h2>

<a href="https://github.com/pmusachio/controle_inadimplencia_emprestimos" >
<img width="199" align="left" src="https://github.com/pmusachio/private/blob/main/img/cover_05b.jpeg" ></a>

Neste projeto de dados, vamos ajudar uma fintech de Crédito que iniciou sua operação de concessão de empréstimo pessoal e pediu para a área de Análise de Dados verificar quais os fatores de risco dos clientes de forma a conseguir aprovar mais contratos com a menor inadimplência possível.

<br><br><br>

<!-- project04 -->
<h2 align="center"> calculo do VaR de uma carteira de investimentos </h2>

<a href="https://github.com/pmusachio/previsao_perdas_investimentos" >
<img width="199" align="left" src="https://github.com/pmusachio/private/blob/main/img/cover_04b.jpeg" ></a>

Neste projeto de dados vamos avaliar o risco de uma carteira de investimentos utilizando as técnicas de probabilidades. Com isso, esperamos responder a pergunta de negócios: O VaR pode ser utilizado como um modelo estatístico para prever as perdas futuras de ativos de uma carteira de investimentos?

<br><br><br>
