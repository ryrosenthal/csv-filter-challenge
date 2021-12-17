# csv-filter-challenge

# How-To
1. Click "Code" -> "Download ZIP".
1. Extract files locally.  
1. Open "scoirchallenge.html" in the browser.
1. Use the the default data or upload a CSV file
1. It should look like this: 

![alt text](https://github.com/ryrosenthal/csv-filter-challenge/blob/main/screenshot.JPG?raw=true)

## Assumptions
1. The user should be able to load a CSV file 
1. The CSV file is valid, and matches the "example" input format
1. The CSV file includes a header row
1. Data, such as Date of Birth, follows the given format (data is not validated)

## Instructions
1. Click "Use this template" to create a copy of this repository in your personal github account.  
1. Using technology of your choice, complete assignment listed below.
1. Update the README in your new repo with:
    * a `How-To` section containing any instructions needed to execute your program.
    * an `Assumptions` section containing documentation on any assumptions made while interpreting the requirements.
1. Send an email to Scoir (andrew@scoir.com) with a link to your newly created repo containing the completed exercise.

## Expectations
1. This exercise is meant to drive a conversation. 
1. Please invest only enough time needed to demonstrate your approach to problem solving, code design, etc.
1. Within reason, treat your solution as if it would become a production system.

## Assignment
Create a command line application that parses a CSV file and filters the data per user input.

The CSV will contain three fields: `first_name`, `last_name`, and `dob`. The `dob` field will be a date in YYYYMMDD format.

The user should be prompted to filter by `first_name`, `last_name`, or birth year. The application should then accept a name or year and return all records that match the value for the provided filter. 

Example input:
```
first_name,last_name,dob
Bobby,Tables,19700101
Ken,Thompson,19430204
Rob,Pike,19560101
Robert,Griesemer,19640609
```
