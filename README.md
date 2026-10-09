# COS 736 Big Data Engineering: Capstone 2026

My capstone submission for COS 736 (Big Data Engineering) at the University of the Western Cape. It has two projects, each in its own folder.

## Project 1: Green Logistics (`Question_1`)

Works with the Logistics Carbon Emissions dataset to look at the carbon footprint of e-commerce deliveries.

- `4024329_Question1A.ipynb`: loads the dataset into a MariaDB database, cleans it, recalculates emissions, and splits the data into one table per route type
- `4024329_Question1B.pdf`: written answers on emissions and distance per route and vehicle type
- `4024329_Question1C.pdf`: visualisations of those results

## Project 2: Streaming Data (`Question_2`)

Simulates e-commerce transactions using the Online Retail dataset.

- `4024329_Question2A.ipynb`: preprocessing, including adding a Region column and splitting the data by region
- `4024329_Question2C.pdf`: insights on top countries, sales totals, and most-sold stock items
- `4024329_Question2D.pdf`: visualisations of the results

The Kafka streaming part (Question 2B) is not included in this repository.

## Notes

- The datasets are not included. They are linked in the course brief.
- The database password in `Question1A.ipynb` has been replaced with `YOUR_PASSWORD_HERE`. To run the notebook, put in your own MariaDB credentials.
