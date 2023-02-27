# Introduction-of-Vaex

## Goal
This project is created for introducing Vaex - an alternative packages of Pandas.

## Characteristics 
<img width="709" alt="image" src="https://user-images.githubusercontent.com/59221097/221464297-d4197bf6-ab9b-4e17-b28c-95fca2309582.png">

## How is the scaling ability? Strategy?
<img width="705" alt="image" src="https://user-images.githubusercontent.com/59221097/221464456-45fdebf7-d89e-4934-bca3-e3439d71236c.png">

## Pandas vs Vaex
<img width="686" alt="image" src="https://user-images.githubusercontent.com/59221097/221464503-4cc5123b-99f4-4fdc-950a-de6b902848ab.png">

## Examples of Vaex
<img width="666" alt="image" src="https://user-images.githubusercontent.com/59221097/221464548-9248046a-ba21-46ea-b694-fa269813ff42.png">

## How to do?
1. Generating 1GB, 5GB, 10GB files with random data.
2. Data processing in the following functions:
- readfile(read_hdf5, read_csv)
- plotting
- string(contains, count(), replace, upper, len)
- group aggregation (sum, mean, count, nunique, std)
- Missing values (dropna, fillna(0), isna())

3. Compare the time performance of Vaex package and Pandas package (The result is in PowerBI dashboard)
<img width="615" alt="image" src="https://user-images.githubusercontent.com/59221097/221464335-ea11db60-9570-4647-ab0d-5d631f2976d5.png">

- First select the Category (e.g. Group Aggregation)
<img width="631" alt="image" src="https://user-images.githubusercontent.com/59221097/221465066-aca17055-9fcc-4b7b-aff1-6c0f2f4c83cf.png">

- Then select the function (e.g. count())
<img width="632" alt="image" src="https://user-images.githubusercontent.com/59221097/221465207-e178728e-3440-49a1-892a-4e58826d5c4e.png">

## Result
As data(GB) becomes larger, the difference of data processing time between Pandas and Vaex becomes larger.
