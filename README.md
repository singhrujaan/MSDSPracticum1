# Data Source

The dataset used in this project is obtained from:

Denver Open Data Portal – 311 Service Requests

Getting Started

Follow the steps below to set up and run the project locally.

1. Clone the Repository

First, clone the repository from GitHub.

git clone https://github.com/singhrujaan/MSDSPracticum1.git

2. Create a Python Environment

Using conda:

conda create -n denver-road-risk python=3.11
conda activate denver-road-risk

or using virtualenv:

python -m venv env
source env/bin/activate

3. Install Dependencies

Install the required Python libraries.

pip install pandas
pip install geopandas
pip install scikit-learn
pip install xgboost
pip install matplotlib
pip install folium
pip install requests
pip install jupyter

You can also create a requirements.txt file for easier installation.

4. Set Up Google Street View API

This project retrieves images using the Google Street View Static API.

Steps

Go to the Google Cloud Console

Enable the Street View Static API

Create an API key

Set the API key as an environment variable.

Mac / Linux:

export GMAPS_API_KEY="your_api_key_here"

Windows:

set GMAPS_API_KEY=your_api_key_here

5. Run the Project

Launch Jupyter Notebook:

jupyter notebook

Open the notebook located in:

notebooks/denver_project.ipynb

Run the notebook cells sequentially to:

preprocess the data

train the machine learning model

generate predictions

retrieve Street View images

create the interactive map
