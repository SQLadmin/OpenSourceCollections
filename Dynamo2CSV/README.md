# DynamoDBtoCSV

This Project is Copied from [edasque's repo](https://github.com/edasque/DynamoDBtoCSV)

## Use Case:
* Import multiple tables at one shot.

* CSV format.

* Less resource usage.

## Installation:
### PreRequirements:
* Install nodejs-legacy and npm
* Clone the repo.
* Edit the config.json and replace your Access, Secret keys and Region.
* Then execute `npm install`

## Example:
* Dump a table 	

```sh
node dynamoDBtoCSV.js -t table_name > table_name.csv
```