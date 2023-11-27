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
|Sprint 4                 | Complete movement of data related to inputs and stock, receipt of notifications regarding low quantity of products in stock. | System developed with complete functionalities regarding data related to inputs and stock, as well as receiving notifications regarding low quantity of a product in stock. |

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

| Rank           | Priority    | User Story         | Estimate | Sprint |
| ---------------| ----------------| -------------------| -----------| -------|
| 1 | High | As a system administrator, I want to have access to a real-time control panel to monitor system performance and quickly identify potential issues. | 1 | 1 |
| 2 | High | As a company manager, I wish for an executive dashboard summarizing key system activities to facilitate analysis and monitoring. | 1 | 1 |
| 3 | High | As a company manager, I want the ability to view sales performance for a specific period for analysis and decision-making. | 1 | 1 |
| 4 | Medium | As the head of the finance department, I want an automated billing system and transaction processing to streamline the process and ensure accuracy. | 1 | 1 |
| 5 | Medium | As a business-interested user, I want access to analyses and trends on customer preferences to identify business opportunities. | 3 | 1 |
| 6 | High | As a company manager, I want customized reports on essential metrics to make strategic decisions based on data. | 2 | 2 |
| 7 | High | As a system administrator, I want the ability to add and manage planned vendor information to facilitate communication and agreements. | 3 | 2 |
| 8 | Medium | As a member of the finance department, I desire detailed reports for in-depth analysis of the company's finances. | 2 | 2 |
| 9 | Medium | As a company manager, I want reports on the stock delivery history to better meet demands and avoid shortages or excess of products. | 4 | 3 |
| 10 | Medium | As a company employee, I want an alert system to inform about items with low stock to expedite orders to suppliers. | 3 | 3|
| 11 | Medium | As a business user, I want a quick summary of current promotions and their impact on sales to identify business strategies. | 2 | 3 |
| 12 | High | As a system administrator, I want enhanced security features to protect sales and transaction-related information. | 4 | 4 |

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Sprint Backlog

<img src = "./Documentacao/Backlog/imgBacklog_Sprint_4.png" width=80%>

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

## DER Database

### Logical Model (James Martin's Notation)

<img src = "./Documentacao/DER/DBLogicalModel_4.png">

<!--### Data Warehouse

#### Star Model

<img src = "./Documentacao/DER/DW_StarModel_3.png">

<p align="right">(<a href="#top">Scroll to top</a>)</p>-->

## Burndown

<img src = "./Documentacao/Burndown/Burndown_Sprint_4.jpg">

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Data Dictionary

[Click here to accesses the Data Dictionary of the Database.](https://github.com/Fluffy-Fatec/Projeto-Integrador-Oracle/blob/develop/Documentacao/Dictionary/Database_Data_Dictionary_Sprint_4.pdf)

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## DevOps Documentation

[Click here to accesses the DevOps Documentation.](https://fluffyfatec.atlassian.net/l/cp/RDTC3CTw)

<p align="right">(<a href="#top">Scroll to top</a>)</p>

## Team

| Avatar            							| Student         | Function           		| GitHub                                                      | LinkedIn                                              |
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
