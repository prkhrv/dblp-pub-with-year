# dblp-pub-with-year
A modified code to download year data from dblp

## Setup

1. Clone this repo
```
git clone git@github.com:prkhrv/dblp-pub-with-year.git
```
*You can also just download the zip file*

2. Install Dependencies
```
pip install -r requirements.txt
```
## How to Use

1. import dblp file in your notebook
```
import dblp
```
2. Search with Year as the second Parameter (This way you can get 30 titles for each year)
```
results = dblp.search(["Gradient"],2021)
```
