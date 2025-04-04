# Tbilisi Biking - An integrated Computer Vision & Modeling Framework for Transportation Analysis of "Transit Deserts" 
### Supplementary Code for the joint Minerva capstone projects between Etoile Boots & Mashiko Lortkipanidze

## Introduction 
<img width="480" alt="Screenshot 2025-04-02 at 17 54 21" src="https://github.com/user-attachments/assets/2014b376-cfd8-42a5-b122-197453c41739" /> <img width="450" alt="Screenshot 2025-04-02 at 17 54 02" src="https://github.com/user-attachments/assets/50251e42-9fc8-471a-8953-2ae909bafe49" />

As the name suggests, *transit deserts* are geographical areas where residents have insufficient access to transportation, more specifically, public transportation. The concept of a transit desert stems from the earlier known "food desert". It typically uses similar computational methods utilizing GIS, GTFS, and census data to identify areas with the most vulnerable populations. The acquisition and presence of such data, especially census-related, is often time-consuming and costly, and in many places around the world, nonexistent. The question remains of how to systematically identify such transport-vulnerable populations without traditional forms of data. Furthermore, research on effective methods to close transportation gaps is limited. This project aims to address these problems by: 
1. Building a machine learning pipeline to utilize pre-existing and abundant street view imagery data to fill in for gaps in census data and subsequently identify transit deserts.
2. Building a model to effectively reduce the size of transit deserts.

This repo serves as the living documentation of the Capstone projects, and is organized intuitively for reproducibility of results (with all API tokens removed). Key sections of this project manage the stage of data handling. For a sequential understanding of [Etoile's Capstone project]([url](https://docs.google.com/document/d/1k1j-69vU9mEy6jiMM5oEkEbUdHXZnyIOvpI-GEXw6hs/edit?usp=sharing)), look to the code in this order: 
1. data_gathering
2. data_postprocess
3. data_abstraction
4. data_analysis

For a look into the tried, and ultimately removed parts of this project (such as ML classification of transit deserts, look at **failed_experements**.

The documentation of Mashiko's project can be seen under the **bike_modeling** folder. 
