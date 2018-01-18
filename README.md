# Predicting phone prices in python using neuron network
The main goal of this project is to help users to predict the price of a particular phone whose price has not been revealed yet so that the users are able to choose one which is resonably priced as opposed to some are usually exorbitant such as Iphone right after they are on sale.

Data is collect through 2 main sources, namely thegioididong.com and fptshop.com. As these 2 websites are the most reliable and always offer phones with actual price. Data collector for thegioididong.com and fptshop.com are contained in Thegioididong.ipynb and FPTshop.ipynb respectively. We use selenium along with beautifulsoup to control a web browser to receive data (you can use solely beautifulsoup for better performance, but these 2 website hide some information that beautifulsoup cannot parse), I assure that the information we are going to collect is accessible and legal.

In terms of data preprocessing, we use a fixed number zero to fill any gaps as not every information is available for a phone (take a phone manufactured a long time ago for example, it does not have information for RAM so there is a gap in that section)

As for the model, we use neuron network through keras.

In this project, the best result we gained was the error of roughly 1.000.000 VND for each phone.
