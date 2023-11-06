# Projeto-Integrador-Oracle

<img src = "./Documentacao/Team/imgOracleFatec_1.jpg">
<br>

<p align="center"> 
      <a>
            <img src="https://img.shields.io/badge/Backend Language%3A-SPRING BOOT-red"/>
      </a>
      <a>
            <img src="https://img.shields.io/badge/Frontend Language%3A-VUE.JS-yellow"/>
      </a>
      <a>
            <img src="https://img.shields.io/badge/Client%3A-ORACLE-blue"/>
      </a>
      <a>
            <img src="https://img.shields.io/badge/Institution%3A-FATEC-orange"/>
      </a>
</p>

<p align="center">
      <a href="#challenge">About the project</a> •
      <a href="#schedule">Schedule</a> •
      <a href="#team">Team</a> •
      <a href="#utilized-tecnologies">Utilized Tecnologies</a>
</p>

## Challenge

In this challenge, you will have the opportunity to create an online platform that will allow restaurant owners to manage their operations in an efficient and intuitive way. The objective is to create a comprehensive system that offers resources such as control panels, graphs, reports and functionalities for managing personnel, suppliers and inputs.

<p align="right">(<a href="#top">Scroll to top</a>)</p>

<li>Functional Requirements</li>
<ul>
      <li>Develop an organizational panel of personnel and suppliers and inputs;</li>
      <li>Develop an employee flow dashboard, people flow, inventory, best selling dishes;</li>
      <li>Develop a comparator of customers x staff x stock, another comparator of predictability of inputs for preparing dishes;</li>
      <li>In the comparator, check the inputs and present what needs to be purchased, in the personnel comparator, consider the flow of customers.</li>
</ul>

<li>Non-Functional Requirements</li>
<ul>
      <li>The website's response time must be below 1000ms in 99.99% of the requests;</li>
      <li>The application's logging mechanism must generate the trails in JSON format (optional);</li>
      <li>The system must contain metrics that help to observe its behavior: Quantity of requests, response time, quantity and percentage of failures when obtaining data from Golden Sources.</li>
</ul>

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Solution

The Fluffy team will develop a web system that will allow the management of inputs and employees, as well as providing visualization of processed data so that the business owner can manage their sales, stocks, work team and project their future actions.

Aiming to solve the project, the system will be delivered in four sprints:


| Sprint                  | Need      | Product         |
| ------------------------| -------------|-------------|
|Sprint 1                 | Visualization of the establishment's Sales data | System developed with functionalities for inserting data related to sales via .csv files and viewing them through various graphs and dynamic filters. |
|Sprint 2                 | Visualization and management of the establishment's Suppliers data, visualization of reports for future decision making. | System developed with functionalities for inserting data related to suppliers and viewing them through various graphs and dynamic filters. The payment part and reports for data comparisons were also developed. |
|Sprint 3                 | Visualization and management of the establishment's Inputs and Stock data, visualization of comparators for predictability. | System developed with functionalities for inserting data related to inputs and stock, as well as viewing them through various graphs and dynamic filters. It was also implemented the input predictability comparator. |
|Sprint 4                 | Visualization and management of the establishment's Employees data, comparison of customers x employees x stock, access level. | System will be developed with functionalities for inserting data related to employees and also visualizing them through various graphs and dynamic filters. A comparator of customers x employees x stock, and system access levels will also be implemented. |



<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Schedule

| Event                   | Date         |
| ------------------------| -------------|
|Kick-off                 |08/21 to 08/28|
|Sprint 1                 |09/04 to 09/24|
|Sprint 2                 |09/25 to 10/15|
|Sprint 3                 |10/16 to 11/05|
|Sprint 4                 |11/06 to 11/26|
|Feira de Soluções        |12/12         |

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Product Backlog

| Rank           | Prioridade      | User Story         | Estimativa | Sprint |
| ---------------| ----------------| -------------------| -----------| -------|
| 1 | Alta | Como administrador do sistema, quero ter acesso a um painel de controle em tempo real para monitorar o desempenho do sistema e identificar possíveis problemas rapidamente. | 1 | 1 |
| 2 | Alta | Como gerente da empresa, desejo um painel executivo que resuma as principais atividades do sistema para facilitar a análise e o acompanhamento. | 1 | 1 |
| 3 | Alta | Como gerente da empresa, desejo ter a capacidade de visualizar o desempenho de vendas por período específico para análise e tomada de decisões. | 1 | 1 |
| 4 | Média | Como responsável pelo setor financeiro, quero um sistema de faturamento automatizado e rastreamento de transações para agilizar o processo e garantir precisão. | 1 | 1 |
| 5 | Média | Como usuário interessado no negócio, desejo acesso a análises e tendências sobre as preferências dos clientes para identificar oportunidades de negócio. | 3 | 1 |
| 6 | Alta | Como gerente da empresa, quero relatórios personalizados sobre métricas essenciais para tomar decisões estratégicas baseadas em dados. | 2 | 2 |
| 7 | Alta | Como administrador do sistema, quero a capacidade de adicionar e gerenciar informações detalhadas dos fornecedores para facilitar a comunicação e acordos. | 3 | 2 |
| 8 | Média | Como membro do departamento financeiro, desejo relatórios detalhados para uma análise aprofundada das finanças da empresa. | 2 | 2 |
| 9 | Média | Como gerente da empresa, desejo relatórios sobre o histórico de movimentação de estoque para entender melhor as demandas e evitar falta ou excesso de produtos. | 4 | 3 |
| 10 | Média | Como colaborador da empresa, quero um sistema de alertas para informar sobre itens com baixo estoque para agilizar pedidos aos fornecedores. | 3 | 3|
| 11 | Média | Como usuário de negócios, quero um resumo rápido das promoções atuais e seu impacto nas vendas para identificar estratégias de negócios. | 2 | 3 |
| 12 | Alta | Como administrador do sistema, desejo funcionalidades de segurança aprimoradas para proteger informações confidenciais de vendas e transações. | 4 | 4 |
| 13 | Média | Como colaborador da empresa, desejo receber notificações automáticas sobre novos produtos ou atualizações de fornecedores para manter o estoque atualizado. | 2 | 4 |
| 14 | Baixa | Como colaborador da empresa, gostaria de melhorias na interface do usuário para realizar minhas tarefas diárias com mais facilidade e eficiência. | 4 | 4 |
| 15 | Baixa | Como colaborador da empresa, desejo um calendario que possa de maneira interna verificar escalas. | 4 | 4 |
| 16 | Baixa | Como colaborador da empresa, quero um painel para gerenciar minhas próprias informações pessoais e escalas de trabalho de forma mais intuitiva. | 2 | 4 |
| 17 | Alta | Como administrador do sistema, desejo ter a capacidade de gerenciar permissões de usuários de forma avançada para garantir a segurança e o controle adequado do sistema. | 4 | ? |
| 18 | Baixa | Como usuário interessado no negócio, quero funcionalidades de feedback para os clientes a fim de melhorar a experiência e fidelizar clientes. | ? | ? |

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Sprint Backlog

<img src = "./Documentacao/Backlog/imgBacklog_Sprint_2.png" width=80%>

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Mockup

### Dashboard Screen
<img src = "./Documentacao/Mockup/Mockup_1_Sprint_3.png">

### Upload Sales Data Screen
<img src = "./Documentacao/Mockup/Mockup_2_Sprint_3.png">

### Suppliers Screen
<img src = "./Documentacao/Mockup/Mockup_3_Sprint_3.png">

### Stock Screen
<img src = "./Documentacao/Mockup/Mockup_4_Sprint_3.png">

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## DER

### Database

<!-- #### Physical Model (James Martin's Notation)

<img src = "./Documentacao/DER/DBConceptualModel_2.png"> -->

#### Logical Model (James Martin's Notation)

<img src = "./Documentacao/DER/DBLogicalModel_3.png">

### Data Warehouse

#### Star Model

<img src = "./Documentacao/DER/DW_StarModel_3.png">

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Burndown

<img src = "./Documentacao/Burndown/Burndown_Sprint_3.jpg">

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Data Dictionary

[Click here to accesses the Data Dictionary of the Database and Data Warehouse.](https://github.com/Fluffy-Fatec/Projeto-Integrador-Oracle/blob/development/Documentacao/Dictionary)

<p align="right">(<a href="#top">Scroll to top</a>)</p>

<!--## DevOps Documentation

[Click here to accesses the DevOps Documentation.]()

<p align="right">(<a href="#top">Scroll to top</a>)</p>-->

## Team

| Avatar            							| Aluno         | Função           		| GitHub                                                      | LinkedIn                                              |
| -------------------------------------------- | ---------------- | ---------------- | -------------------------------------------------------------- | ----------------------------------------------------- |
| <img src = "./Documentacao/Team/imgMichael.jpg" width="60" >|__Michael Felipe__| *Product Owner*| [![](https://bit.ly/3f9Xo0P)](https://github.com/Michaelfss/Michaelfss) | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/michael-felipe-573b64167) |
| <img src = "./Documentacao/Team/imgTiago.jpg" width="60" >|__Tiago Camillo__| *Scrum Master*| [![](https://bit.ly/3f9Xo0P)](https://github.com/tiagocamillo) | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/tiago-camillo-277257192/) |
| <img src = "./Documentacao/Team/imgAldrik.jpg" width="60" >|__Aldrik Álvaro__| *Developer Team*| [![](https://bit.ly/3f9Xo0P)](https://github.com/Aldrik-Alvaro) | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/aldrik-alvaro-0bb952180/) |
| <img src = "./Documentacao/Team/imgAna.jpg" width="60" >|__Ana Clara Leal__| *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/heyanaleal)      | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/ana-clara-oliveira-leal-723169220/) |
| <img src = "./Documentacao/Team/imgEmanuele.jpg" width="60" >|__Emanuele Diniz__| *Developer Team*| [![](https://bit.ly/3f9Xo0P)](https://github.com/ecampos14) | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/emanuele-diniz-campos-b14699181) |
| <img src = "./Documentacao/Team/imgLuiz.jpg" width="60" >|__Luiz Felipe Borges__ | *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/luizborges17)   | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/luizborges17/) |
| <img src = "./Documentacao/Team/imgVictor.jpg" width="60" >|__Victor Fernandes__  | *Developer Team*  | [![](https://bit.ly/3f9Xo0P)](https://github.com/victornaca)| [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/victor-fernandes-1a61a917b/) |


<p align="right">(<a href="#top">Scroll to top</a>)</p>


## Utilized Tecnologies
<details>
<summary>Front-End</summary>

* [vue](https://vuejs.org/)
* [HTML](https://www.w3schools.com/css/)
* [CSS](https://www.w3schools.com/css/)

</details>

<details>
<summary>Back-End</summary>

* [Java](https://www.java.com/pt-BR/?msclkid=7faa842eb8f811ecab39772d4c1ae90b)

* [Spring boot](https://spring.io/projects/spring-boot)

</details>

<details>
<summary>Database</summary>

* [Oracle Autonomous Database](https://www.oracle.com/autonomous-database/)
</details>

<details>
<summary>Meetings and Communication</summary>

* [Discord](https://discord.com/?msclkid=b4f5af84b8f811ecbd81c127a0ae68a7)

* [Whatsapp](https://www.whatsapp.com/)

* [Slack](https://slack.com/intl/pt-br/?msclkid=c00e628eb8f811ecaef374bb86d7f056)
</details>

<p align="right">(<a href="#top">Scroll to top</a>)</p>

<br>
<img src = "./Documentacao/Team/imgOracleFatec_2.jpg">
<br>

---

> GitHub [@fluffyfatec](https://github.com/fluffyfatec) &nbsp;&middot;&nbsp;
> Gmail [fluffyfatec@gmail.com](fluffyapi@gmail)
