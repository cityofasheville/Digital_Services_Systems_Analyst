# City of Asheville Digital Services Systems Analyst; Development Services & Permitting Skills Task
A skills assessment for a Digital Services Systems Analyst position.

The Digital Services Systems Analyst position is a cross-functional position between the Information Technology Services (ITS) Department and the Development Services Department (DSD).  Being such, it is important that the candidate have technical expertise to support various systems in place as well as have the capacity to understand real world business problems that arise in the development community.

## The Problem

At the City of Asheville, we provide citizens and city employees with access to data in several ways. One of our goals at the city is to be as transparent as possible and to provide a rich, seamless, and engaging experience for citizens that will allow them to answer questions on their own with minimum city staff involvement. To this end, one of the most significant deficiencies in the city’s data offerings is a lack of summary statistics (or dashboards) for the datasets we provide. We’ve had an increasing number of requests from our internal customers (city employees) for dashboards on various datasets used by the city, and we think that a similar need exists in the citizen community as well. 

## The Task 

Construct a SQL database using the data provided and creatively express any fun and useful information that you may discover. 

Some questions that you may consider for developing visualizations might include the following (but feel free to come up with your own):

  * How many permits are opened online using the City's website vs opened in-house, over time? If B1PERMIT.B1_CREATED_BY is like 'PUBLICUSER', then the permit was created using the website... else it was in-house. 

  * How is the City doing on our Service Level Agreement (SLA) with Customers in the plan review process?  Each permit might have an 'Addressing', 'Building Review', 'Fire Review','Routing', or 'Zoning Review' task - and the SLA Achievement for each task should be treated separately.  (Note: To analyze the SLA Achievement, you should only need to utilize one view which has been exported as 'FirstPlanReview_SLA_Achievement.csv')

  * Are there certain record types that are consistently failing to meet the SLA? Does it depend on another attribute? 

  * We have exported the major Accela transactional tables and made them available to you on this repo.  Our citizens and internal management would like to know what's going on with permits in the City.  

There's a ton of great info here for you to consume.  We've included address and parcel table exports in case you'd like to create a map.  It's all up to you!

The intention is not to have you spend a prohibitive amount of time on this submission.  It's to give you an idea of some of the things that you might actually be working on if you were to accept this position; and to give us an idea of how you work.  Be as creative as you'd like, show-off, be snarky... whatever floats.

## Data & File Definitions

1. Accela Reporting Basics - SQL Server.pdf - overview on the Accela reporting basics.
2. FirstPlanReview_SLA_Achievement.csv - view export - simplified view of Service Level Achievement data for first plan reviews.
3. Accela_data_dictionary.csv - table export - data dictionary for the Accela tables.
4. Accela table exports (referenced in 'Accela Reporting Basics - SQL Server.pdf')
    * B1PERMIT.csv
    * B3ADDRES.csv (inside B3ADDRES.zip)
    * B3PARCEL.csv (inside B3PARCEL.zip)
    * BPERMIT_DETAIL.csv
    * BWORKDES.csv
    * F4FEEITEM.csv
    * F4PAYMENT.csv

## Rules

  * Keep it simple. We are not looking for a finished product but want to learn a little more about your skills and how you approach problems. Think of your delivery as something “minimal” that is on the road to awesome.
  * Move the data into a MSSQL Server Database. You can download SQL Server Express from Microsoft for free. If you’d rather approach this differently, let us know why.
  * Use any reporting tool you like or any other visualization tools/techniques.
  * You may use, borrow anything you want (reference where appropriate), but the work should be done by you.
  * You may email us with any questions. tpace@ashevillenc.gov or, preferably, use this repo’s issues.

## Deliverables
1. A web site accessible somewhere on the web showing your analysis/insights/visualizations 
2. Write up which includes the following:
    * Link to your code or a pull request if you fork this repo
    * Detach and send us the database (e.g. Google Drive, host on your site, etc.).
    * Description of your approach to this problem. Briefly explain your approach and why you decided on that approach.
    * Additional Materials: SQL Queries, design files

Have fun!
