# act360
* Date difference in years according to the **Actual/360** daycount method
* Synonyms: Actual/360, Act/360, A/360, French


## ISO 20022 -- A004

    "Method whereby interest is calculated based on the actual number of accrued days in the interest period and a 360-day year."

[link](https://www.iso20022.org/15022/uhb/mt565-16-field-22f.htm)


### Installation
```
clib install hcnn/act360
```

Or add to your `package.json` and run `clib install`

```
{ ...
    "dependencies": {
        "hcnn/act360": "0.1.0"
        ...
```

### Test and Demo
Download, compile, and run [test.c](https://github.com/hcnn/act360/blob/master/test.c) and [demo.c](https://github.com/hcnn/act360/blob/master/demo.c)

```
git clone git@github.com:hcnn/act360.git
cd act360
make deps
make validate
make showcase
```
