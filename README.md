![Uber Clone](https://img.shields.io/badge/Uber%20Clone-Fabric-blueviolet?style=for-the-badge&logo=uber)
 
🚖🚖Real-Time Data Pipeline met Microsoft Fabric🚖🚖

Welkom bij dit project waarin we een end-to-end **real-time data pipeline** hebben gebouwd met behulp van **Microsoft Fabric**. Dit project is uitgevoerd als onderdeel van een data engineering traject, met focus op moderne architectuurprincipes zoals de **Medallion Architecture**.

##  Over het project

Het doel van dit project was om een schaalbare en geïntegreerde gegevensverwerkingspipeline te bouwen, die real-time data kan verwerken van binnenkomst tot visualisatie. Door verschillende componenten binnen Microsoft Fabric slim te combineren, hebben we een systeem opgezet dat volledig binnen één platform draait.

Deze repository bevat een overzicht van de belangrijkste stappen, notebooks en datamodellen die we hebben gebruikt tijdens dit traject.

## ⚙️ Gebruikte Technologieën

- **Microsoft Fabric**
- **Eventstream** – voor real-time data-inname
- **Lakehouse (Bronze & Silver layers)** – voor opslag en ruwe data verwerking
- **PySpark Notebooks** – voor transformaties
- **Dataflow Gen2** – voor het modelleren van een ster-schema
- **Data Warehouse (Gold layer)** – voor geoptimaliseerde rapportage
- **KQL Database** – voor real-time query’s
- **Realtime Dashboard** – voor visualisatie
- **Medallion Architecture** – als leidend structuurprincipe

## 🔄 Pipeline Overzicht

graph TD
    A[Eventstream] --> B[Lakehouse - Bronze]
    B --> C[Lakehouse - Silver]
    C --> D[PySpark Transformaties]
    D --> E[Dataflow Gen2 - Star Schema]
    E --> F[Data Warehouse - Gold Layer]
    F --> G[KQL Database]
    G --> H[Realtime Dashboard]


👥 Team
Dit project is gerealiseerd in samenwerking met:

Zehra Okay

Mehmet Gezer

Sefa Öztürk

Senem Mergenci

Sueda Ekiz

Begeleiding:
🎓 Fatih Demir (docent)
🧑‍💼 A. Özcan Kurşun & Abdullah Mart (mentoren)

💡 Wat ik heb geleerd
Dit project heeft me niet alleen meer inzicht gegeven in het Microsoft Fabric ecosysteem, maar ook in hoe je een data pipeline efficiënt kunt ontwerpen en structureren volgens best practices. Vooral de integratie tussen verschillende services zoals Eventstream, Notebooks en Dashboards was erg waardevol om in de praktijk te ervaren.

📌 Toekomstige uitbreidingen
Integratie met externe API's voor datastromen

Toevoegen van data quality checks in Silver layer

Automatiseren van monitoring en alerting op KQL niveau

Bedankt voor je interesse in dit project! 🌟



<img width="1192" height="670" alt="Schermafbeelding 2025-06-17 002917" src="https://github.com/user-attachments/assets/7d505ca8-06ea-4599-b8e4-569d7a7666cf" />

<img width="1193" height="666" alt="Schermafbeelding 2025-06-17 002959" src="https://github.com/user-attachments/assets/adfc20f4-1449-4c60-b8df-71c79edc917d" />

<img width="1192" height="670" alt="Schermafbeelding 2025-06-17 003019" src="https://github.com/user-attachments/assets/ecda4877-7f73-4e3e-92f4-6085d69c1337" />

<img width="1189" height="667" alt="Schermafbeelding 2025-06-17 003050" src="https://github.com/user-attachments/assets/416db1e1-107b-420e-863d-dc8a127a7cd2" />



<img width="1187" height="665" alt="Schermafbeelding 2025-06-17 003105" src="https://github.com/user-attachments/assets/de92d838-393a-49d3-bcd3-7cd1d8a2ccfc" />


<img width="1191" height="668" alt="Schermafbeelding 2025-06-17 003121" src="https://github.com/user-attachments/assets/d6e636f0-e991-430c-a745-b492850deba6" />



<img width="1190" height="669" alt="Schermafbeelding 2025-06-17 003151" src="https://github.com/user-attachments/assets/9ebee429-4343-49a9-ad5b-d7281b3f3a22" />


<img width="1195" height="669" alt="Schermafbeelding 2025-06-17 003215" src="https://github.com/user-attachments/assets/2791f049-1d52-4f55-a62a-124cd057a266" />


<img width="1186" height="670" alt="Schermafbeelding 2025-06-17 003227" src="https://github.com/user-attachments/assets/af077c53-467c-4a29-b735-f14c6072e106" />




<img width="1190" height="670" alt="Schermafbeelding 2025-06-17 003237" src="https://github.com/user-attachments/assets/45de1b1f-b228-4786-9478-a701df70ab2e" />




<img width="1194" height="665" alt="Schermafbeelding 2025-06-17 003250" src="https://github.com/user-attachments/assets/3ca6029a-aa29-407d-b1be-3eecd72b2ae2" />




<img width="1186" height="667" alt="Schermafbeelding 2025-06-17 003343" src="https://github.com/user-attachments/assets/0f89c143-1357-4c57-b23f-450316033f14" />



<img width="1193" height="669" alt="Schermafbeelding 2025-06-17 003357" src="https://github.com/user-attachments/assets/6fab1d40-3879-4319-8114-bbc77e89734c" />



<img width="1190" height="670" alt="Schermafbeelding 2025-06-17 003408" src="https://github.com/user-attachments/assets/5a6385e2-ee85-4763-b96e-0ca1d15f762a" />




<img width="1194" height="667" alt="Schermafbeelding 2025-06-17 003420" src="https://github.com/user-attachments/assets/834ecf06-0be6-449e-8ce6-9041aa603531" />







