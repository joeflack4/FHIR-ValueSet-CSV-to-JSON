# FHIR ValueSet CSV to JSON
Tool for converting extensional value sets in CSV format to JSON format able to 
be uploaded to a FHIR server.

## Set up / installation
1. You must have Python3 installed.
2. `git clone `

## Usage
First, `cd` into the directory where this repository was cloned.
### Syntax
1. `python3 -m fhir_value_set_csv_to_json path/to/FILE.csv`

### Example
`python3 -m fhir_value_set_csv_to_json examples/1/input/n3cLikeExtensionalValueSetExample.csv`
