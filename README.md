# LdClusterView
LdClusterView is a web-based genome browser with client-server architecture. LdClusterView extended the basic layout of stacked plot in genome browser by incorporating a dendrogram and Sankey plot to describe the relationship between the stacked plots. These improvements allowed illustration of both relationships between the plots and relationships between the internal elements of the plots respectively.

Configuration with server:
1. Download entire 'LdClusterView' folder
2. Set up the server by changing the IP address and Port number in 'ajaxCall.js' file
3. Go to 'resources/js/data/data.js' file to change the URL for each data object
4. Set up the data in the server according to description in https://github.com/sisisalia/FYP/blob/master/Data%20description.docx

Configuration without server:
1. Download entire 'LdClusterView' folder
2. Go to 'resources/js/data/data.js' file
3. Insert the data in JSON format into each data object as described in https://github.com/sisisalia/FYP/blob/master/Data%20description.docx

Run :
1. After setting up the data, run the application through 'mainpage.html'

# Biostatistical Network Tool (BNY)
BNT explored an emerging method of associating gene information with other types of biological data by analysing the data through non-parametric tests, plots and sub-network graph in form of Minimum Spanning Tree (MST) to identify interesting gene candidates for further exploration in LdClusterView.

Run :
1. Download 'BNT' folder
2. Prepare datasets in Excel file
3. Run 'statsMainpage.html'
4. Input the datasets through insert an Excel file or copy and paste the datasets in form of table to the textbox provided
