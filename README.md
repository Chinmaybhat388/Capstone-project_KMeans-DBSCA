# Capstone-project
This repository is meant for the capstone project where i work on location data and different problems that can be solved using location data from foursquare API.

## Problem
- Most of the students pursuing a degree are on a budget, and house rents can be daunting. Low budget student hostels or dormitories can be a solution to this problem.
- A hostel which is situated in the right place and offering services at the right price can benefit a lot of students.
- This project aims to predict a suitable location for the construction of student hostels.

## Interest
- The stake holders interested in this project would be a hypothetical construction company, willing to enter into hostels and hospitality sector,
trying to identify the right locations in the state of New York for establishing hostels so that it can be profitable as well as budget friendly.
- Also, the students enrolled in colleges and universities in New York.

## Data sources
- For the sake of simplicity, we will only be studying the community colleges in NY. The model can be scaled with details from all the colleges if and when needed. 
- The primary source of community college data was web scraped from the site community college review.
- We will be using the ‘Location’ feature from this data to obtain geo coordinates of each college from geopy library.
- We will then use Foursquare API to get hotspots around a college where students are most likely to hang out. 

## Modelling
- We will be using kMeans and DBSCAN to determine the optimal locations to set up student hostels.
  

