# Data Engineer Study Roadmap

## Roadmap overview

![Mind map Data Engineer](https://user-images.githubusercontent.com/10213510/90983332-a4486980-e543-11ea-81e3-a41d05fd1c18.png)

## Online courses, bootcamps and articles

| Title | Content |Plataform| Language | Link |
|-------|---------|:-------:|:--------:|:----:|
|The Ultimate Hands-On Hadoop - Tame your Big Data!| General | Udemy | en_US | [Go to Course](https://www.udemy.com/course/the-ultimate-hands-on-hadoop-tame-your-big-data/)

# Capstone project
## Processing profitability of investment portfolios 

You have just be hired for startup to work as Principal Data Engineer. The business of this startup is to provide an investment platform where their customers have at their dispossal an infinity of financial products that can be cosidered in their investiment strategies, like so:

- Bonds
- CDs (Certificate of Deposit)
- Stocks
- Investment Funds
- Retirement
- REITs
- Etc.

Besides of the quantity and range of products available, and the user experience created for these clients, is the which of this startup to provide a daily information about the performance for each customer investiment porftolio and in the future provide personalized recommendations to improve their investment performance.

You challenge as Principal Data Engineer is to architect, design and implement a data architecture for an **on premise infrastrcuture** a brand new data architecture for this startup in order to provide to your custermers data about their investments performance. 


### User stories

- [ ] As **investor**, I want to receive a month overview from my portfolio, with the percentual allocation and  profitability by portfolio, asset class and asset, so I can have a better understanding of the evolution of my portfolio;
- [ ] As **investor**, I want to see a daily overview of my portfolio, with the percentual allocation and  profitability by portfolio, asset class and asset, so I can follow-up its evolution and may decide to rebalancing it;
- [ ] As **broker**, I want to see which clients are facing a low performance comapred with an index, so I can offer to them a consulting, menthorship or traning, in order to help them perform better;
 
### Challenges

- [ ] Configure whole infrastructure (cluster) for data ingestion and data processing using hadoop ecosystem from ground up; 
- [ ] Architect, design and implement a transition from **on premise** to **cloud computing** using **Amazon Web Service** or **Google Cloud** Big Data solutions;

### DATA FEEDS

#### CLIENT DATA FEED

This file brings the active clients information. This includes information about its ID, Address and etc. 

| Column | Datatype | Length | Description |
|--------|----------|--------|-------------|
|Fristname| TEXT| 15|The client's first name|
|Lastname| TEXT | 15|The client's last name|
|Middlename| TEXT | 20 | The clients's middle name |
|Document number| TEXT | 20 | The clients's document number |
|Document type | TEXT | 10 | The clients's document type | 
|Street Address 1 | TEXT | 60 | The client's street address line 1 |
|Street Address 2 | TEXT | 60 | The client's street address line 2 |
|City | TEXT | 20 | The client's city |
|County | TEXT | 20 | The client's county |
|State  | TEXT | 20 | The client's state |
|Zipcode | NUMBER | 09 | The client's zipcode |
|Country | TEXT | 10 | The client's country |
|Contract number| NUMBER | 10 | The client's contract number. Left padding with zeros |
|Investor profile| NUMBER | 10 | The client's investor profile. Could be: CONSERVATIVE, MODERATE, BALANCED, GROWTH |





