# MUSA 509 - Geospatial Cloud Computing & Visualization

## Scheduling

### Class

* Lectures: Tuesdays 4:30pm - 6pm US ET via Zoom and recorded
* Labs
  * US times: Thursday 4:30pm - 5:30pm US ET
  * Asia times: TBD, but likely Thursday 6pm - 7pm China CST (6am - 7am ET)

Lectures will be on Tuesdays, and Labs will be on Thursdays. A separate lab at a more convenient time for students in international locations will be scheduled.

### Contact Info

* **Instructor**: Andy Eschbacher, andye@design.upenn.edu
* **TA**: Jingwen Felix Qiang, jingwenq@seas.upenn.edu

### Office Hours

* By appointment

### Course Website

* GitHub: https://github.com/MUSA-509
* Canvas: Internal class information

## Course Description

This course is designed to provide students with the skills to build cloud-based applications that provide answers using spatial data analytics and visualizations. There will be a strong emphasis on open source tools although we will also strongly rely on Google Cloud and Amazon Web Services.

Besides the technologies used in class, we will be using large and sometimes messy data from which we will be deriving insights from how people move around in their environments. One such dataset is [SafeGraph's human mobility data](https://docs.safegraph.com/docs). We will be combining data like this with OpenStreetMap, US Census, and datasets on open data portals.

The class is divided into four modules:

1. Spatial Analytics with Databases -- learn the basics of SQL and PostGIS for exploring datasets and answering questions of your data
2. Python and SQL -- building basic applications with queries and interacting with web services/APIs programmatically
3. Creating an API -- use Python to create a basic API that queries a PostGIS database
4. Building a cloud-based application -- build a full-fledged application in the cloud

## Format

The course will be divided between lectures on Tuesdays and labs on Thursdays. To accommodate the different time zones students will be in, a separate lab will be scheduled.

## Assignments

There will be assignments with some lectures. Other lectures will have recommended readings and suggested exercises to give additional practice, but these will be optional.

The final project will be the culmination of all of the skills learned in the class. Students will build an application that has a custom backend (e.g., PostGIS database) hosted on the cloud that can be publicly accessed and returns custom responses based on user feedback. Expectations are that API responses will be communicated in multiple ways: a static chart or map, interactive map, and formatted statistics.

## Grading

* Homeworks: 35%
* Participation: 15%
* Final Project Proposal: 10%
* Final Project: 40%

## Software

Most software used in class will be free and open source. This includes the scientific Python software stack and PostgreSQL/PostGIS database, among other tools. We will also be using cloud services like Amazon Web Services and Google Cloud, both of which offer a free tier and/or sufficient free credits for doing course work.

## Course Data

Some of the data we are using in this course is proprietary and cannot be openly disseminated. Students will be provided with access to our private class repository of datasets. Derivative insights based on these datasets can be openly shared, especially as part of final project work.

## Academic Integrity

Students are expected to comply with and be familiar with [Penn's Code of Academic Integrity](https://catalog.upenn.edu/pennbook/code-of-academic-integrity).

When writing software, it is common to copy and paste small code snippets from online sources without citation. For larger samples, it is expected that the source is cited in the code base. In case there is uncertainty, speak with your instructor for guidance.

## Schedule

Dates and schedule are subject to change.

| Class # | Lecture Date | Lab Date | Topic | Homework |
|---------|--------------|----------|-------|----------|
| Week 1 | Sept 1 | Sept 3 | [Introductions](https://github.com/MUSA-509/week-1-introductions) | [Practice SQL](https://github.com/MUSA-509/week-1-introductions#homework) (nothing due) |
| Week 2 | Sept 8 |  Sept 10 | [Spatial databases and querying](https://github.com/MUSA-509/week-2-digging-into-databases) | Assigned: [HW 1 - SQL practice](https://github.com/MUSA-509/week-2-digging-into-databases/blob/master/homework-1.md) |
| Week 3 | Sept 15 | Sept 17 | [PostGIS and geographical SQL operations](https://github.com/MUSA-509/week-3-spatial-database-pt-2) | Due: [HW 1](https://github.com/MUSA-509/week-2-digging-into-databases/blob/master/homework-1.md) |
| Week 4 | Sept 22 | Sept 24 | [Advanced PostGIS](https://github.com/MUSA-509/week-4-spatial-joins-and-indexes) | Assigned: [HW 2 - Advanced PostGIS](https://github.com/MUSA-509/homework-2-advanced-postgis) (Due Oct 6th at 11:59pm) |
| Week 5 | Sept 29 | Oct 1 | [GIS with BigQuery](https://github.com/MUSA-509/week-5-geospatial-with-bigquery) |  |
| Week 6 | Oct 6 | Oct 8 | [Python for geographical analysis](https://github.com/MUSA-509/week-6-python-introduction) | HW 2 Due Oct 6 by 11:59pm. Assigned: [HW 3 - Python &amp; SQL](https://github.com/MUSA-509/homework-3) |
| Week 7 | Oct 13 | Oct 15 | [Accessing web services with Python](https://github.com/MUSA-509/week-7-querying-with-python) | Due: HW 3, Assigned: [HW 4 - Building APIs with Flask](https://github.com/MUSA-509/homework-4) |
| Week 8 | Oct 20 | Oct 22 | [HTTP requests and APIs](https://github.com/MUSA-509/week-8-http-requests/) | Due: HW 4 |
| Week 9 | Oct 27 | Oct 29 | [Building APIs with Python](https://github.com/MUSA-509/week-9-apis-with-flask) |  |
| Week 10 | Nov 3 | Nov 5 | [Python APIs + Cloud Databases](https://github.com/MUSA-509/week-10-pulling-pieces-together) |  |
| Week 11 | Nov 10 | Nov 12 | [Dynamically generated HTML pages](https://github.com/MUSA-509/week-11-all-together-now) | Assigned Nov 12: Final Project Proposal |
| Week 12 | Nov 17 | Nov 19 | [Building an HTML Application](https://github.com/MUSA-509/week-12-html-applications) | Due Nov 19: Final Project Proposal |
| Week 13 | Nov 24 | No class | Cloud-based APIs &amp; HTML Applications | |
| Week 14 | Dec 1 | Dec 3 | Cloud-based APIs |  |
| Week 15 | Dec 8 | No class | Final Project wrap-up |  |
