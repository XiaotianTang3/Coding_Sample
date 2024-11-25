# Top Location by Alert Type and Hour Dashboard: Data Cleaning and Visualization using Chicago Cities Data
This repository contains a coding sample focused on data cleaning and data visualization using the Chicago Cities dataset. The dataset originates from the Harris School of Public Policy's course PPHA 30538: Data and Programming for Public Policy II.

The repository showcases the implementation of a Shiny dashboard to visualize top alert locations in Chicago. It consists of two main components:

## 1. Data Cleaning

The original dataset includes columns type and subtype which are often unstructured and difficult to interpret. To enhance clarity:

Two original columns, type and subtype, are split into three new columns:   
  updated_type   
  updated_subtype   
  updated_subsubtype   
Missing subtypes (NA) are classified as "Unclassified" for better usability.   

## 2. Data Visualization

A Shiny dashboard is created to visualize the cleaned data, featuring the following components:

(1) A Dropdown Menu: Allows users to select a specific combination of type and subtype.   
(2) A Toggle: Switch to choose between viewing data for a single hour or a time range.   
(3) A Slider: To select a specific hour or time range.   

The Shiny dashboard will generate the Top Alert Locations:   
Displays the top 10 alert locations in Chicago for the selected type, subtype, and hour/time range.   



This code is developed by Xiaotian Tang. 






