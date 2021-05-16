# home-price-prediction

## About The Research

使用 [airbnb open data](http://insideairbnb.com/get-the-data.html)，建立台北房價預測模型


<!-- GETTING STARTED -->
## Getting Started

1. 下載 [taipei airbnb list file](http://data.insideairbnb.com/taiwan/northern-taiwan/taipei/2021-03-30/data/listings.csv.gz)
2. 解壓縮該檔案，將 `listings.csv` 放置於專案 `csv` 目錄下
3. 建立虛擬環境並進入
   ```sh
   $ virtualenv venv -p python3
   $ source venv/bin/activate
   ```
4. 安裝 python packages
   ```sh
   $ pip install -r pip-requirements.txt
   ```
4. 將虛擬環境 kernel export 到 jupyter notebook
   ```sh
   $ conda create -n venv python=3.6
   $ pip install --user ipykernel
   $ python -m ipykernel install --user --name=venv
   ```
5. 執行程式
   ```sh
   $ jupyter notebook home_price_prediction.ipynb 
   ```