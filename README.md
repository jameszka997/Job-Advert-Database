# 📊 Job advert database from HiringCafe 

**The following repository aims to document the workflow developed to import job search results from 'HiringCafe' job advert aggregation website, by cleaning & processing the data into a structured and formatted database.**



## 🎯 Overview

This project aimed to develop a workflow to filter for specific jobs of interest from 'HiringCafe', manually copy & pasting the job adverts from the website into an Excel database, where pipeline was developed to clean-up & process the messy data structure from the initial data into a clean and structured database.

The primary purpose of this project was to catalogue jobs of interest to me, primarily in the data and analytics workspace within Hungary/Europe in order to aid long-term job hunting, identifying key companies of interest, or skills which are sought to develop them for better future prospects.



## 🛠️ Workflow

```mermaid
flowchart LR;
A(["Set Search Filter on HiringCafe"]) --> B;
B(["Select & Copy all the search results from '*Nr.* Jobs'"]) --> |Ctrl + Shift + V| C;
C(["Input data into Excel as simple text"]) --> D;
D(["Set-up Data Cleaning Columns for the data"]) --> E;
E(["Clean-up messy or incorrectly aligned data"]) --> |Utilize the look-up function for transfer| F;
F(["Input cleaned data into structured data format sheet"]) --> G;
G(["Add date added and type of search information"]) --> |Cross-check function against database sheet| H;
H(["Verify no duplicates are added"]) --> I;
I(["Add new job ad entries into finalized database"])
```


## 🚧 Problem & Challenges

- Messy initial datastructure when inputting results into Excel
- Developing quality checks & cleaning methods to reliably process the data.
- Identifying key information snippets and developing supporting column structures for reliable long-term database management




##💡 Future Aims

- Developing partial- or full automated workflow to lessen the manual work required for new data input
- Making SQL database of finished and cleaned data for security and storage
- Potentially identifying the areas of interest for the data from the HTML code  to quicken data scraping.
- Identifying key trends, skills of interest, companies, etc. as the database develops and more data is accrued




## Database Structure

| Column | Description |
| -- | -- |
| **Posted Time** | Time at which the original job advert was posted on the website |
| **Role** | Name of the advertised role |
| **Area** | Area for which the job is advertised |
| **Work Type** | Type of work for the advertised role (*Hybrid, Onsite, Remote*) |
| **Contract Type** | Type of work contract (*Full Time, Part Time, Contract, Internship, etc.*) |
| **Company** | Name of the company |
| **Company & Description** | Name and short description of the company |
| **Requirements Summary** | Summary aggregated from the large original job advert to show experience, education, tools required for the role |
| **Technical Tools mentioned** | Lists any technical tools which were mentioned within the job advert (may not include any) |
| **Job Posting** | Quality check utilized for data cleaning & checks from the source data |
| **Added Date** | Date when information was added |
| **Type of Search** | Search filter which was utilized for data gathering |



### ⭐ Impact

This project has significantly contributed to my understand to the design of reliable databases, and the difficulties which come with database design and proper processing pipelines for data entry.

The current database has allowed me to more efficiently gather information about potential jobs and job areas of interest for the future as my career progresses.

By utilizing the really well-designed HiringCafe job aggregator website, I can more reliably identify skills, companies of interest which are applicable to my location.

It has contributed to my understanding to the principles which need to be involved when thinking about database design, Excel workflows, as well as additional improvements and features I can utilize in the future.


## 🎯 Key Skills Demonstrated

- Developing database to construct a long-term database to track jobs of interest and identify jobs, skills, companies and roles of interest for the future
- Understanding data integration pipeline development
- Data cleaning, processing, restructuring and quality check development
- Trend analysis & finding company industry which are most likely to contain relevant information of interest


## 🛠️ Tools & Technologies

### Primary Tools

| Tool | Task |
| -- | -- |
| **Source Website** | HiringCafe source website which performs job advert aggregation and filtering for key skills & summary of the job advert text|
| **Excel** | Data aggregation, database management & analysis |
| **VS Code** | Managing scripts & documentation writing |
| **Markdown** | Documentation and README files |





### Questions or Feedback?
I'm always interested in discussing data analytics, data science and business intelligence solutions. Feel free to reach out if you have questions about this project or would like to collaborate!

---

⭐ **If you found this project helpful, please consider giving it a star!**

*This project demonstrates practical application of business intelligence tools to solve real-world project management challenges. It showcases end-to-end development from problem identification to solution delivery.*



License
The project utilizes the more reliable & clean job search board functions of the [HiringCafe](https://hiring.cafe/about) website. Such precise and reliable piece of work could not have been done without the amazing work the HiringCafe have one with their website.
