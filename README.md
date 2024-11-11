# Assignment-3

## Setup

Create virtual environment (first time only):

```sh
conda create -n reports-env-2024 python=3.10
```

Activate virtual environment (whenever you come back):

```sh
conda activate reports-env-2024
```

Install Packages:

```sh
pip install -r requirements.txt
```




## Usage

Run the example script:

```sh
python app/example.py
```

Run the unemployment report:

```sh
ALPHAVANTAGE_API_KEY="..." python app/unemployment_report.py
#ZA7MCBB2Y439DIXR
```