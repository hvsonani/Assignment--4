# Assignment-4

Uploaded SSIS package which used Foreach loop container to read multiple files from source and create pipelines to import the files into staging Table. Data from Staging Table was then imported to Archive  and destination Table by deriving date and year column in the staging table. Validation table was created to audit the total of the national row counts. Audit table was created to count no of rows imported from a source file and create a log of year of the file and date on which file was imported.

The zip folder contains the following files

1. Assignment-4.docx which contains documentation of all 6 questions.

2. Assignment-4(SSIS) folder contains SSIS package for all questions.

3. Archive.txt file contains output data in txt format after using multicast function on staging table.

4. Medicare Files folder contains Files for (Copy of Medicare_Part_D_Opioid_Prescribing_Geographic.txt files for year 2013, 2014, 2015 and 2016)

