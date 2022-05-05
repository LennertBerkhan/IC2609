# Getting Started
Change test
Welcome to your new project.

Another change from DJ

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
Hi
Hi it's Adi .

## HANA via HANA Database Explorer
- Open Link (https://hana-cockpit-004.cfapps.eu10.hana.ondemand.com/hrtt/sap/hana/cst/catalog/cockpit-index.html)
- Click the + Symbol (Top Left Panel)
- Database Type -> HDI Container
- Select HDI Contrainer -> FinanceApp-db
- Press Ok
- Expand Database -> FinanceApp-db (Team 2609)
- Click on Tables
- Now you should see all tables on the bottom left panel
- To see data of a table -> rightclick table and "Open Data"

## SAP Business Application Studio (SBAS)
- Open Link (https://ic2022.eu10cf.applicationstudio.cloud.sap/index.html)
- Create Dev Space -> Type Full Stack Cloud Application
- When it is running access it
- Click on "Clone from GIT"
- Enter following URL: https://github.com/LennertBerkhan/IC2609.git
- (Press "Open" on the bottom right)

## How to Build and Deploy our App
- To build our app open a Terminal
- Enter command "mbt build"
- Now a new file is created in folder "mta_archives" for example FinanceApp_1.0.0.mtar
- Now we can deploy this to the BTP (you have to be logged into the Cloud Foundry Account)
- Enter command "cf deploy mta_archives/FinanceApp_1.0.0.mtar" (or the new name of the file)

## Login to Cloud Foundry (CF)
- Open Console in SBAS
- Enter command "cf login"
- API Endpoint "https://api.cf.eu10-004.hana.ondemand.com"
- Enter your SAP-Mail-Adress and Password
- Done