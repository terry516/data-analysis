1. json -> dataFrame
-------------------------------
```python
with open('test.json') as f:
    data = pd.DataFrame(json.loads(line) for line in f)
```
--------------------------------
2. csv file -> dataFrame
```python
df = pd.read_csv(/locate/title.csv)
```
