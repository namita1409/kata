# Tech-Task-CSharp-Queries
`This is a standard Console-based application which allows user to read a Csv file and display output according to the user`
requests:

Here we have 3 folders:

1. The `MockTechTask` folder contains the C# solution to the application
2. The `MockTechTaskTest` folder contains the unit tests for the solution
3. The `input` folder contains input.csv file

# Business requirement
👉 Your application should read from the provided input.csv file

This “comma-separated variables” file contains (fake!) data for 500 people:

● First name

● Last name

● Company

● Address

● City

● County

● Postal

● Phone1

● Phone2

● Email

● Web

# User Story

👉 Your Program should allow for the user to choose a specific output from a list
(defined below). 

👉 Here’s the list of criteria your program must be able to output according to the user
requests:

 🏚OPTION 1: Every person who has “Esq” in their company name.
 
🏚 OPTION 2: Every person who lives in “Derbyshire”.

🏚 OPTION 3: Every person whose house number is exactly three digits.

🏚 OPTION 4: Every person whose website URL is longer than 35 characters
(including the protocol and subdomain).

🏚 OPTION 5: Every person who lives in a postcode area with a single-digit value.

🏚 OPTION 6: Every person whose first phone number is numerically larger than
their second phone number..

👉 Each program output consists of a count and then a list of people which correspond
to some criteria. Each person should be displayed on a new line consisting of their
position in the list and their name and their company.
For example, if the criteria was “Every person who is called ‘Karma Quarto’” then the
output should be:

Count: 1
30 - Karma Quarto - J C S Machinery

# Prerequisite

C#,  input.csv 

# Instructions

``The machine running the application should have [.NET 6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) (or above) installed.``

Clone the repository to your computer.

Download the file `input.csv` to your local machine and change the file location in Programe.cs file

Then run the application:

```
dotnet run
```
