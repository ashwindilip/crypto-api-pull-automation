# **Crypto Website API Pull Automation**

I made this project to learn how to automate pulling of data from a website API using Python.

All of the code for this project is contained within the **automatingCryptoWebsiteAPIPull.ipynb** file.

Key imports for this notebook include **pandas** and **seaborn** , though **matplotlib** may also be used instead for visualization.

All of the data collected from the API is directed towards the **Crypto.csv** file. For the purpose of illustration, I have gathered data over a time period of **5 minutes** , with each API pull separated from its predecessor by an interval of **a minute**. To construct more comprehensive datasets, longer time periods and shorter frequencies may also be used.

Here is a categorical plot that compares the percent change in the values of different cryptocurrencies.

![](https://lh3.googleusercontent.com/drive-viewer/AEYmBYT9DOzJJtc_lciXs3RMJF3kBmMSUA-njAUgU4xqnnJ17m8wB-syke1cbzAte0YFcA-fmV4Jt5xNcsikzYN6Od0JJpzN=s2560)

**Note** : If you wish to reproduce this project, you'll have to replace the value of **X-CMC\_PRO\_API\_KEY** in the headers dictionary with a valid API key. This can be obtained by creating a free, basic account at [**https://coinmarketcap.com/api/**](https://coinmarketcap.com/api/).
