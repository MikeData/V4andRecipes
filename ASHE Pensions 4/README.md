# ASHE Pensions Table 4 'recipe'

Takes 2 input file (one of data points, one of Cv values for those data points). Created two output files: one of values with Cvs and one of percentages with Cvs.

# usage

```python ASHEpensions4 <values.xls> <CV.xls>```


## details
full details are provided in the form of the attached details.json. Contents shown below

```json
{
          "uses": ["databaker","pandas"],
          "description": "Takes 2 files: 1 containing values, 1 containing CVs. Creates 2 files: one values with Cvs, one percentages with Cvs.",
          "inputs": {
                     "1": {
                           "format": "xls",
                           "distinctiveText": "",
                           "name": "ASHE Pensions 4 data"
                           },
                     "2": {
                           "format": "xls",
                           "distinctiveText": "CV",
                           "name": "ASHE Pensions 4 CV"
                           }
                    },
          "transformName": "ASHE Pensions 4",
          "outputs": [
                      "ASHE Pensions 4 Values <year>.csv",
                      "ASHE Pensions 4 Percentages <year>.csv"
                      ],
          "transformType": "many-to-many"}
```
