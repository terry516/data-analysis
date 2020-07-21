1. json -> dataFrame
-------------------------------
```python
with open('../location/title.json') as fl:
    for i, line in enumerate(fl):
        users.append(json.loads(line))
        if i+1 >= 100000:
            break
df = pd.DataFrame(users)
df.head()
```
--------------------------------
2. csv file -> dataFrame
```python
df = pd.read_csv(/locate/title.csv)
```
