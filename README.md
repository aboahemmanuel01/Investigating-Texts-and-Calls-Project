# Unscramble Computer Science Problems: Investigating Texts and Calls
Reference: <i class="icon-cog"></i> **[Data Structures and Algorithms Nanodegree](https://www.udacity.com/course/nd256)**

## About
This project contains five tasks based on a sampled set of calls and texts exchanged during september 2016.
I used python to analyze and answer questions about the text and calls contained in the dataset. Finally, I performed a runtime analysis of my solution in order to determine the efficiency.

## Details of the Project

The data for the text and call are provided in csv files in this directory.

The text data (text.csv) has the following columns: sending telephone number (string), receiving telephone number (string), timestamp of text message (string).

The call data (call.csv) has the following columns: calling telephone number (string), receiving telephone number (string), start timestamp of telephone call (string), duration of telephone call in seconds (string)

All telephone numbers are 10 or 11 numerical digits long. Each telephone number starts with a code indicating the location and/or type of the telephone number. There are three different kinds of telephone numbers, each with a different format:
```
Fixed lines start with an area code enclosed in brackets. The area codes vary in length but always begin with 0. Example: "(022)40840621". 

Mobile numbers have no parentheses, but have a space in the middle of the number to help readability. The mobile code of a mobile number is its first four digits and they always start with 7, 8 or 9. Example: "93412 66159". 

Telemarketers' numbers have no parentheses or space, but start with the code 140. Example: "1402316533".
