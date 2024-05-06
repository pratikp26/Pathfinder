# Pathfinder: Safest Route Prediction in New York City
Course project developed for CS-GY 6513 (Big Data) at NYU (Spring 24).

This project will let users set the start and end points of their commute. They will then be shown 3 paths that they can take to reach their destination along with their respective risk scores, based on historical crime statistics. Our project aims to enhance the safety of pedestrians during commute.

We have used following two datasets for our data analysis and route risk calculation:
- [NYPD Arrest Data (Year to Date)](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc/about_data)
- [NYPD Arrests Data (Historic)](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u/about_data)

Both the jupyter notebooks contain installation commands for any external libraries that may be required.

To use the data in the jupyter notebooks, download the required data from above links and upload it to the same directory as the notebook and rename it to **data.csv**.

To use Google Maps API into the notebook, follow these steps:
1. **Sign up for Google Cloud Platform**: Create an account on [Google Cloud Platform](https://console.cloud.google.com/).
2. **Create a new project**: Navigate to the Google Cloud Console and create a new project.
3. **Generate an API key**: Once your project is created, generate an API key for it.
4. **Enable required APIs**: In the Google Cloud Console, enable the **Directions API** and **Maps Static API** for your project and API key.
5. **Store API key**: Save your API key in a file named **api_key.txt**.
6. **Upload the API key file**: Upload the "api_key.txt" file to the same directory as your notebook or your project.

After uploading both **data.csv** and **api_key.txt** files, the notebooks can be run as is on Google Colab (recommended) or your local environment (you might need to follow some extra steps to set up your environment in this case).




