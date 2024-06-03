This project is to provide an analysis and visualize a network graph corresponding to the Global Ecological Footprint API.

The src/ folder contains files as follows :

df_build.ipynb
graph_build.ipynb
main_df.csv
The project was written in Python3 (Version: 3.10.14)

To run this project, please follow the below instructions:

- We have used jupyter notebook for development, if not available kindly install using pip (pip install notebook).
- To run the project, we need to install the necessary libraries mentioned in the 'requirements.txt'. For ease, you can run using "pip install -r requirements.txt"
- The first part of the project is reading and parsing data from the GFN API (https://data.footprintnetwork.org/#/api), which is provided in the 'df-build.ipynb' which requires an API Key specified in the website on how to acquire the same.
- The 'parser.ipynb' at the end generates a CSV file (used for intermittent storage) (can take about 6-7 minutes), further used for graph visualization. We have provided a sample CSV for usage.
- The 'graph_build.ipynb' file is used for graph construction as well as visualization. The file also contains the network measures such as avg path length, clustering coeff, small-world/pref-attachment simulations as well as communities build.


Libraries Used:
NetworkX, Pandas, requests, matplotlib, numpy.

This project is part of the Course - OSNA (CS 579)