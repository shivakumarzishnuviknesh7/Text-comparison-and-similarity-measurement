**Text comparison and similarity measurement**

**Overview**

This application allows you to visualize the similarity between job descriptions using cosine similarity and hierarchical clustering. It presents the results in both a graph and a table format.

**Prerequisites**

Python 3.x Flask Flask-ngrok Sentence-transformers Pandas Networkx Matplotlib Seaborn Scipy

**Installation**

Install the required Python packages using pip:
Copy code pip install flask flask-ngrok sentence-transformers pandas networkx matplotlib seaborn scipy
Download and install ngrok from https://ngrok.com/download.
Usage
Clone this repository or download the app.py file. Navigate to the directory containing app.py in your terminal. Run the Flask application: Copy code python app.py Open the ngrok URL provided in the terminal to access the web application. Explore the job description similarity graph and table.

**How it works**

The application loads a dataset containing job descriptions. It preprocesses and cleans the text data. It uses a pre-trained sentence transformer model to encode the job descriptions into embeddings. Cosine similarity between all pairs of descriptions is computed. A graph is created where each node represents a job description, and edges represent the similarity between descriptions. Hierarchical clustering is performed on the cosine similarity matrix. The resulting graph and heatmap are displayed in the web interface.

**Credits**

This application uses the Sentence Transformers library for text embedding and similarity calculation. It also utilizes Flask for the web framework and ngrok for exposing the local server to the internet.
