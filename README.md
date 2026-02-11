# Introduction

Thank you for applying to Preventx as a Full Stack Engineer.

To help guage your experience and knowledge as a candidate we require the completion of the test outlined within this project. 
# Requirements

Please submit this back through the recruiter in a zipped folder.
The content below outlines any expectations we require for test completion.
## Required tools

- .Net 8.0 SDK (download [here](https://dotnet.microsoft.com/en-us/download/dotnet/8.0))
- Nuget Package Manager
- Visual Studio Code (or equivelent IDE)
- Unit testing Extension ([csdevkit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) for Visual Studio Code)

# Tasks
## Task 1 
Currently, the unit tests in this application are failing.
Please find the issues and resolve them.

## Task 2
ListResults always returns all results. 
Please add a wildcard filter for name (checks anywhere in the string)
Please add a sort function that orders by ChlamydiaResultsLevel or Gonorrhea Results Level ascending or descending.

## Task 3
We need to filter results that are over a specified level, please add a filter option to return results that are above specified value.
 
## Task 4
Using React, create a webpage that consumes the API endpoint /Laboratory/ListResults, this page must include:
 - a text box that filters the name field of the records
 - a dropdown that filters the minimum level
 - a submit button that submits the above filters and refreshes the page with filtered results
