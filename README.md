### Cenário hipotético

Em uma empresa do ramo agro, alguns modelos de Machine Learning foram implementados dentro do setor de crédito. O desenvolvimento e treinamento desses modelos envolveu o uso de dados sintéticos, visto que a empresa não tinha dados reais em volume e qualidade ideais. 

Pensando em dar manutenção nesses modelos e também viabilizar a implementação de outros algoritmos no futuro, foi solicitada a criação de um Gerador de Dados Sintéticos, software que será responsável por gerar bases de dados artificiais para re-treino dos modelos em produção e também gerar novos conjuntos de dados que irão treinar novos modelos. 

**Stakeholders:** Gerente de Crédito (acompanhará os KPIs de melhoria no processo de concessão de crédito que o gerador sintético viabiliza)

**Usuários:** Cientistas de Dados (cientistas de dados podem consumir o gerador sintético para construir bases artificiais estatisticamente coerentes)

**Clientes:** Produtores rurais (produtores pessoa física e jurídica são os clientes afetados pelo uso do gerador, sendo aprovados ou não no processo de concessão de crédito). 

**Time Scrum:**

- **Product Owner:** conhece bem do negócio e das necessidades dos analistas de crédito e da empresa;
- **Cientista de Dados:** conhece bem os modelos implementados para orientar os requisitos do gerador de dados sintéticos pensando em ciclo de vida;
- **Desenvolvedor:** conhecimentos em back end e front end para auxiliar no desenvolvimento da aplicação;
- **Scrum Master:** mediação e organização do processo.

> *A squad desenvolverá **dois épicos**, registrados no formato de tag dentro da opção categoria: o épico **manutenção** (core da solução, que dá manutenção nos modelos existentes e é definida na feature MVP) e o épico **customização** (incremento da solução, que possibilita a customização da geração de dados e é definida na feature INCREMENTO).*
>