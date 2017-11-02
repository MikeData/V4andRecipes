# ASHE Table 8 'recipe'

Takes a zip of 22 files as input. Outputs 2 datasets.


## usage: 
```python ASHE8.py <Zip File>```


## example source file(s)

https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/earningsandworkinghours/datasets/placeofresidencebylocalauthorityashetable8


## details
full details are provided in the form of the attached details.json. Contents shown below

```json
{
          "uses": ["pandas"],
          "description": "Creates 2 load files from a zip containing 22 xls files",
          "inputs": {
                     "1": {
                           "format": "zip",
                           "distinctiveText": "",
                           "name": "ASHE Table 8 Zip"
                           },
                    },
          "transformName": "ASHE Table 8",
          "outputs": [
                      "ASHE Hours <year>.csv",
                      "ASHE Earnings <year>.csv"
                      ],
          "transformType": "many-to-many"}
```
