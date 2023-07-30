# Martyrs Data Management System

Implement a martyrs data structure using: Sorted doubly circular linked list, AVL Trees, Queues, and Stacks. The data structure contains location records sorted by location, with each location record having two AVL trees: one for storing martyr records sorted by martyr's name and the other for storing DateStack objects sorted by date. The project includes a graphical user interface (GUI) using JavaFX for a seamless user experience. Users can load martyr's data from a CSV file, perform various operations on the data: add, delete and update martyrs information, view statistics, and save the updated data back to a file.

## Installation

- Java Runtime Environment (JRE) and Java Development Kit (JDK).
- Install the source code in your IDE.
- Install the btselem.csv and Martyrs.txt file ( The second file is used for testing the functionality of the source code ).
- Install the background and the logo pictures.

## Usage

#### Data Input:
- Launch the application and load the cities on your datastructure.
#### Functionality:
- You can go to the location tap where you can choose specific city to work on.
- You can go to the summary tap where all the martyrs in all the cities are loaded in.
- In the summary tap a summary for all the cities with : Number of Marytrs, Height of the Name's AVL tree , Height of the Date's AVL tree and the date with max number of martyrs.
- You can add, delete, update, choose the city you want and then press search to load the martyrs of the choosen city.
- In the martyrs tap you can search for a martyr by a part of his name e.g: "ahmad" , all the names contains ahmad will appear in a table view, you can select one of them and there information will show up in a form where you can edit there information and you can add, delete , update a martyrs informatoin in the current choosen city.
- In the statistics tap: you can see a traverse of the names tree, backward traverse of the dates tree and stats of the city, you can switch between the cities : next and previous , since the linked list is sorted in alphabetical order.
- Switching between the cities means you can see the stats and the traverse for both of the trees.
- Save your changes in the save tap where you can type your file name and choose the directory to save your file at.

## Features

- Data Loading: you can easily load the martyrs from the csv file, populating the trees, queues, stacks, and circular linked list.
- Location Management: Insert new location records, ensuring they are sorted by location.
- Search and Martyr Listing: Search for specific location records based on location names, Load the martyrs' records associated with a selected location, presenting them in a user-friendly manner.
- Martyrs Management: Add new martyrs records, with automatic placement in both AVL trees for efficient sorting, update or delete existing martyr records seamlessly.
- Martyr Search: Find martyrs quickly by searching for their names, whether partially or fully.
- Statistics and Reporting: Generate summary reports for selected locations, presenting key information, such as the number of martyrs, AVL traversal results, maximum martyr date, and AVL heights, Efficiently navigate through locations using "Next" and "Previous" buttons to access summary reports for different locations.
- Data Saving: save the updated data structures back to a file with a simple "Save" button and the file chooser for selecting the destination directory.
- User-Friendly GUI: Employ a JavaFX graphical user interface for a pleasant and intuitive user experience.

