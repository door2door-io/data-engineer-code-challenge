# data-engineer-code-challenge
Code challenge for Senior Software Engineer with a focus on data

As a Senior Software Engineer, you will join our Mobility Intelligence team. You would work with a cross-functional team of skilled Engineers with backgrounds in Cartography, Transportation Science, Computer Science, and Geo-informatics to develop our cutting-edge Insights tool. Based on the analysis of extensive supply- and demand-data sources, we plan for our clients how to realize the vision of a car-free city. We analyze, visualize and simulate millions of data points using best-in-class technology like RxJava, GeoPandas, Mapbox GL.

Multiple times per week we receive data from various providers (e.g. cell phone data, car navigation data, app usage data) containing origin-destination trips. All the data gives us insights into the mobility patterns of people, which we use to find out how we best can improve mobility with our Rideshare service. The [linked CSV](trips.csv) file is a small sample of such a dataset. For further analysis (e.g. visualizations in a web app or simulations done by another microservice), the following requirements need to be met.

## Requirements
* Automated processes to ingest and store the data on an on-demand basis
* A service that is able to provide the following functionality:
  * Return the weekly average trip count by bounding box and region
  * Delete the data by region
  * Inform about the status of the data ingestion without using a polling solution
* The solution should be scalable to 10 million entries. It is encouraged to simplify the data by a data model. Bonus points if you proof the solution is scalable.
* The solution should be written in Python, Java or JavaScript using an SQL database
* Bonus points if you containerize your solution and if you sketch how you would set up the application on AWS

## Delivery of your solution
Please deliver your solution as a git repository in a ZIP file. The repository should contain full instructions for us to run the solution on our own machines.

## Reviewing
To avoid the bias of code reviews, we will anonymize your git history.
What matters to us is to learn how you write code and documentation, what you consider as clean code, and how you generally approach the problem given limited requirements. For us, it is more important to have an understandable project than a complex algorithm.
