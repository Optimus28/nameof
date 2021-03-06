# nameof

A simple and handy tool to find the name of a student from command line using their Institute ID

## What can it do?

This is a command line tool whch can give you the name of any student from the batch of 2018-2022 by their institute ID.

## Why I built it?

Considering the strength of our batch and the fact that almost every academic activity involves our ID's, it sometimes becomes difficult to identify and find people by their ID's. Hence I've buit this command line tool to find names from ID.

## How to use?

1.) Clone this repository using 

  `git clone https://github.com/ashutoshsingh05/nameof.git`

 2.) Change current directory to your local repository

  `cd nameof`

3.) Execute install.sh

  ```
  ./install.sh
  ```

4.) Run by executing the following commands on the terminal
 
  ```
  nameof <9-digit-space-separated-institute-ids>
  nameof <space-separated-keywords>
  ```
  
 **Try using sudo if you encounter any permission related issues**
 
  ## Screenshot
 
 ![A sample execution](preview.png)
 
 
 ## Proposed Enhancements in future
 
 :heavy_exclamation_mark: Addition of more details like

  - Section
  - Lab Group

 :heavy_check_mark: Enabling searching of student details using name

 :heavy_check_mark: Making provisions for getting names of multiple students at a time by providing multiple space separated arguments.
