# Data Preparation Stage

- Convert data into train and test.tsv in 70:30 ratio

```
data.xml
    |- train.tsv
    |-test.tsv
```

- Only 3 tags are taken from the xml data - 1. row Id , 2. title 3. Tags( specific to Python )

|Tags|feature names|
|-|-|
|row Id|row ID|
|title and body|text|
|stackoverflow
