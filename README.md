# webscraping.github.io
This is a project named "Python Project for Data Science" promoted by IBM. The goal of this project is to extract data from webpages. 

# Question 1 - Use yfinance do extract stock data. Reset the index, save, and display the first five rows of the 'tesla_data' dataframe using the 'head' function.

In order to use the yfinance library to extract stock data, we use the 'Ticker' module. By using this module, we can create an object that allows us to access functions to extract data. Firstly, we do this by providing the 'Ticker' symbol for the stock. The company Tesla has the 'Ticker' symbol 'TSLA'.

Thus, initially, we must install the 'yfinance' function and import the libraries. Then, we may extract the data.

![image](https://user-images.githubusercontent.com/81119854/124040867-21523400-d9dc-11eb-8004-f75235db6b6b.png)

![image](https://user-images.githubusercontent.com/81119854/124040901-3202aa00-d9dc-11eb-8053-81994e6fdaef.png)

![image](https://user-images.githubusercontent.com/81119854/124040920-4050c600-d9dc-11eb-9352-80000a5d569b.png)

# Question 2 - Use webscraping to extract Tesla revenue data. Display the last five rows of the tesla_revenue dataframe using the tail function.

![image](https://user-images.githubusercontent.com/81119854/124356568-099dca00-dbed-11eb-9999-113cb295ee41.png)

![image](https://user-images.githubusercontent.com/81119854/124356584-1b7f6d00-dbed-11eb-847f-af7bd062002f.png)

In the codes above, found the number of tables in the url used and also the index of the table we choose to work with. Now, we print the content of this index in order to confirm if that is the data we really want:

![image](https://user-images.githubusercontent.com/81119854/124356704-cabc4400-dbed-11eb-9595-f57e32141d10.png)

Thus, we may create a dataframe and append on it the data we select from the web:

![image](https://user-images.githubusercontent.com/81119854/124356783-58982f00-dbee-11eb-9153-a2b7baa27898.png)

![image](https://user-images.githubusercontent.com/81119854/124356792-69e13b80-dbee-11eb-88a5-0c2e2e1dc07e.png)

![image](https://user-images.githubusercontent.com/81119854/124356803-7c5b7500-dbee-11eb-9a21-3fc8a2af51f5.png)

![image](https://user-images.githubusercontent.com/81119854/124356837-a57c0580-dbee-11eb-8b78-f48f4778f009.png)

![image](https://user-images.githubusercontent.com/81119854/124356863-d5c3a400-dbee-11eb-8197-7fe7f40a3475.png)

# Question 3 - Use yfinance to extract stock data. Reset the index, save, and display the first five rows of the gme_data dataframe using the head function. 

![image](https://user-images.githubusercontent.com/81119854/124356915-2b984c00-dbef-11eb-98d0-a3819239e5ee.png)

# Question 4 - Use webscraping to extract GME revenue data. Display the last five rows of the gme_revenue dataframe using the tail function. 

![image](https://user-images.githubusercontent.com/81119854/124356956-73b76e80-dbef-11eb-9cd3-cddebe5e67e2.png)

![image](https://user-images.githubusercontent.com/81119854/124356970-8336b780-dbef-11eb-9c96-76160a9ba350.png)

![image](https://user-images.githubusercontent.com/81119854/124356986-98abe180-dbef-11eb-9d36-b796589481b8.png)

![image](https://user-images.githubusercontent.com/81119854/124357000-a6616700-dbef-11eb-9bdd-b0c3d215c4af.png)

![image](https://user-images.githubusercontent.com/81119854/124357017-b24d2900-dbef-11eb-86e5-3e1e79e90980.png)

# Bonus: Graphs

We may use the make_graph function to graph the Tesla Stock Data, the GameStop Stock Data, and also provide a title for the graph.

We should only care about the inputs. It takes a dataframe with stock data (dataframe must contain Date and Close columns), a dataframe with revenue data (dataframe must contain Date and Revenue columns), and the name of the stock.

![image](https://user-images.githubusercontent.com/81119854/124359171-33a9b900-dbfa-11eb-8466-b292d82862ed.png)

![image](https://user-images.githubusercontent.com/81119854/124359206-563bd200-dbfa-11eb-8ab4-b80936b9584e.png)

![image](https://user-images.githubusercontent.com/81119854/124359230-66ec4800-dbfa-11eb-9b58-e1f4ad2d29ed.png)
![image](https://user-images.githubusercontent.com/81119854/124359254-85524380-dbfa-11eb-9e9a-f13015e3ff42.png)
![image](https://user-images.githubusercontent.com/81119854/124359269-9602b980-dbfa-11eb-90b2-1b1007ab968c.png)

![image](https://user-images.githubusercontent.com/81119854/124359278-a1ee7b80-dbfa-11eb-8a81-172579f08b4b.png)

![image](https://user-images.githubusercontent.com/81119854/124359290-afa40100-dbfa-11eb-9aeb-d40909a5ec8e.png)
![image](https://user-images.githubusercontent.com/81119854/124359299-b92d6900-dbfa-11eb-8dd4-33d50ae71573.png)
![image](https://user-images.githubusercontent.com/81119854/124359313-c5b1c180-dbfa-11eb-961b-01e5948a7fed.png)

![image](https://user-images.githubusercontent.com/81119854/124359334-dfeb9f80-dbfa-11eb-85d9-4871fce80003.png)



