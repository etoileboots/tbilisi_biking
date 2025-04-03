# Tbilisi Biking - An integrated Computer Vision & Modeling Framework for Transportation Analysis of "Transit Deserts" 
### Supplementary Code for the joint Minerva capstone projects between Etoile Boots & Mashiko Lortkipanidze

## Introduction 
<img width="500" alt="Screenshot 2025-04-02 at 17 54 21" src="https://github.com/user-attachments/assets/2014b376-cfd8-42a5-b122-197453c41739" /> <img width="470" alt="Screenshot 2025-04-02 at 17 54 02" src="https://github.com/user-attachments/assets/50251e42-9fc8-471a-8953-2ae909bafe49" />

As the name suggests, *transit deserts* are geographical areas where residents have insufficient access to transportation, more specifically, public transportation. The concept of a transit desert stems from the earlier known "food desert", and typically uses similar computational methods utilizing GIS, GTFS, as well as census data to identify areas with the most vulnerable populations. The acquisition and presence of such data, especially census-related, is often time-consuming and costly, and in many places around the world--nonexistent. The question remains of how to systematically identify such transport-vulnerable populations without traditional forms of data. Furthermore, research on effective methods to close transportation gaps is limited. This project aims to address these problems by: 
1. Building a machine learning pipeline to utilize pre-existing and abundant street view imagery data to fill in for gaps in census data and subsequently identify transit deserts.
2. Building a model to effectively reduce the size of transit deserts.
