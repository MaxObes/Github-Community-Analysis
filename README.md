# Github-Community-Analysis
Utilized a data pipeline to load a GitHub community into a DuckDB database and analyze the community's top contributors.

Provided a GitHub community, I utilized Python's requests library to call the GitHub API for the contributors of an open source community and pull their total commits from the last 30 days. 

Then, I connected a Data Load Tool (dlt) pipeline to DuckDB so that I could utilize a connection to run SQL commands and analyze the data columns.

Some highlights of the data include:
- All contribuors of a community 
- Top contributor of the past month
- Highest all-time contributor
- A comparison of the chamption to their peers

You can access the Google Colab Notebook here -https://colab.research.google.com/drive/1c9HrNwRi8H36ScSn47m3rDqwj5O0obMk?usp=sharing
