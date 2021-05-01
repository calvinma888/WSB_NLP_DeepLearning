# Monetizing WallStreetBets through Short-term Options trading: A Cloud-Based Deep Neural Network and Elastic Net Approach

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project
The r/WallStreetBets (WSB) Reddit community is an online forum in which members participating in high-risk options trading engage in discourse about current market trends and trading strategies; consequently, accurate and timely predictions of how different financial holdings would move based on the aforementioned discussions would be imperative for any investor who seeks to capitalize on the more popular, and often more volatile “meme” stocks and their related financial derivatives. Using cloud-based deep neural networks and elastic nets, the authors built different models to investigate the relation between the frequency and sentiment of the words in daily comments, as well as their relation to the movements of a singular stock price PLTR and the broader equity market SPY. It was discovered that sentiment, particularly the positive sentiment expressed in WSB comments, had the best predictive power to predict the movement of the broader equity market. Furthermore, simple options trading strategies based on the predictions from the most positive words were favorable, with the strategy selling the options that are struck out-of-the-money by |Predicted Price-Current Price|*1.5 and holding them for one day generating a maximum of 27.29% return over one month.


### Built With

* []()Python


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these steps.

### Prerequisites

This is a list of packages that need to be installed before the notebook can be run.
* tensorflow
* sklearn
* PRAW
* quandl
* yFinance
* google.colab
* pandas
* numpy
* seaborn
* matplotlib
* autokeras
* scipy


### Installation

Clone the repo: https://github.com/calvinma888/WSB_NLP_DeepLearning.git
   

<!-- USAGE EXAMPLES -->
## Usage

Run with Jupyter Notebook


<!-- CONTRIBUTING -->
## Contributing

Calvin (Yu chien) Ma
