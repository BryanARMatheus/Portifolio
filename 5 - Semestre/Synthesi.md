
---

## 1. Descrição do Projeto
No quinto semestre, nosso time desenvolveu o **Synthesi**, uma plataforma de inteligência voltada para a gestão de projetos. O grande desafio apresentado pelo cliente era a ineficiência na análise de dados, que estavam dispersos em diversas planilhas manuais. Nossa missão foi centralizar essas informações utilizando conceitos de *Data Warehouse*, automatizando a geração de indicadores e *dashboards* para que os gestores ganhassem tempo e produtividade na tomada de decisão.

Para isso, construímos uma aplicação *web* hospedada na nuvem (AWS). O sistema contava com rotinas automatizadas de ETL (Extração, Transformação e Carga) que processavam as planilhas do cliente e alimentavam um banco de dados modelado no formato *Snowflake*. Essa arquitetura garantiu agilidade para renderizar *dashboards* complexos sobre acompanhamento de horas, orçamento (horas vs. materiais), controle de estoque e análise de fornecedores.

### Contribuições Pessoais
Neste semestre, tomei uma decisão que me tirou completamente da zona de conforto: assumi o papel de *Product Owner* (PO). Nos projetos anteriores eu já auxiliava na estruturação de tarefas, mas agora o desafio era muito maior: traduzir a dor real do cliente em um produto funcional. No início, foi a fase mais difícil do curso, pois precisei mudar minha mentalidade de desenvolvedor — que costuma seguir tarefas já estruturadas — para a visão estratégica de quem define *o que* precisa ser feito e *por que*.

Minha principal contribuição foi guiar a direção do Synthesi para maximizar a entrega de valor. Conduzi o levantamento de requisitos, validei *wireframes* diretamente com o cliente e desmembrei o problema em histórias de usuário claras, priorizando o *backlog* das *sprints* de forma estratégica. Além da gestão, atuei fortemente na base técnica do produto: modelei a lógica inicial do *Data Warehouse*, defini as fórmulas dos indicadores financeiros e documentei toda a estrutura do repositório principal.

Como o projeto exigia uma aplicação prática de DevOps, também assumi a frente de **Monitoramento e Infraestrutura**. Configurei o Prometheus e o Grafana para monitorar a saúde do banco de dados e conduzi testes de estresse para descobrir os limites da aplicação. A partir dessas métricas, elaborei um plano de escalonamento real, traçando metas de capacidade de usuários e projetando os custos de infraestrutura em nuvem necessários para cada fase de crescimento do sistema.

### Soft Skills Trabalhadas
A atuação como PO transformou minha **Comunicação, Capacidade Analítica e Resolução de Problemas**. Tive que exercitar a escuta ativa para entender a verdadeira dor do cliente e usar a criatividade para transformar essa necessidade em uma solução tecnológica viável.

Além disso, a **Colaboração e a Tomada de Decisão** foram testadas diariamente. Precisei negociar constantemente com o time de desenvolvimento, analisando quais *features* eram possíveis de entregar dentro do prazo, respeitando a capacidade técnica da equipe. Essa experiência foi definitiva para solidificar meu interesse pela área de gestão e governança de projetos, provando que consigo aliar minha base técnica sólida à liderança estratégica.

**Tecnologias Utilizadas:** Python, Django, MySQL, React, TypeScript, TailwindCSS, Docker, AWS, GitHub Actions, Jira, Figma, Prometheus, Grafana, Data Warehouse.
