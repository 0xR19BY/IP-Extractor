# Mass IP Extractor

A quick and dirty Python script designed to extract IPv4 addresses from text (or other) files and store them in a CSV file.

## Prerequisites

Doesn't require any other dependencies. Requires Python3.xx

## Usage
To use this script, open your terminal or command prompt and navigate to the directory containing the script. Then, execute the script with the following command:
```
python ip_extractor.py -e {extension_type}
```
 - -e: This flag specifies that you want to extract IP addresses from text files. It must be followed by the file extension type (e.g., txt) for the files you want to process.
### Example:
```
python ip_extractor.py -e txt
```

## Notes:
 - The resulting CSV file will have a name like IP_ListYYYY-MM-DD_HH-MM-SS.csv, with the timestamp indicating when the script was executed.
 - Ensure that the script and the text files you want to process are in the same directory.
 - The script is designed to extract IPv4 addresses using a basic regular expression pattern. You can modify the ipv4_pattern variable in the script to customize the pattern according to your needs.