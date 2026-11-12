
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

### Hard Skills Trabalhadas
- Figma: Tive minha primeira experiencia com design/UX e wireframes, precisei planejar todas as telas e fluxo que o usuário possui ao acessar e utilizar nossa aplicação, tudo isso mantendo em mente deixar a pagina limpa e aceitável para visualização do usuário.

- Grafana e Prometheus: Foi necessário entender o conceito de monitoramento de aplicações, implementar o prometheus na nossa aplicação, depois conectar ele com o grafana e disponibilizar dados úteis para o monitoramento de saúde e escalabilidade da aplicação. 


### Tecnologias Utilizadas:

[![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)](https://www.atlassian.com/software/jira)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario) 
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://slack.com/) 
[![Figma](https://img.shields.io/badge/Figma-0ACF83?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/) 
[![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black)](https://prettier.io/)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://github.com/eslint/eslint)
[![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)](https://grafana.com/)
[![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)](https://prometheus.io/)
[![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)](https://www.sonarsource.com/products/sonarqube/)

### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
[![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)](https://docs.pytest.org)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
[![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/) 
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/) 
[![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org/)
[![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)](https://gunicorn.org/)


### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MaterialUI](https://img.shields.io/badge/Material%20UI-%23FFFFFF?style=for-the-badge&logo=MUI&logoColor=#007FFF)
