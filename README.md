# ETL-Using-Shell-Scripts

Note: This is an exercise file of coursera.

Root course: IBM Data Warehouse Certification Course (https://www.coursera.org/professional-certificates/data-warehouse-engineering)

Course Name: ETL and Data Pipelines with Shell, Airflow and Kafka 

I've integrated this section into my GitHub profile to enrich my description. As part of the IBM Data Warehouse Certification Course, I delved into the "ETL and Data Pipelines with Shell, Airflow, and Kafka" module.

_______________________________________________________________________________________________________
-----------------------------------------------------
# Problem:
Copy the data in the file ‘web-server-access-log.txt.gz’ to the table ‘access_log’ in the PostgreSQL database ‘template1’.

The file is available at the location : https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0250EN-SkillsNetwork/labs/Bash%20Scripting/ETL%20using%20shell%20scripting/web-server-access-log.txt.gz

The following are the columns and their data types in the file:
    
    a. timestamp - TIMESTAMP
    
    b. latitude - float
    
    c. longitude - float
    
    d. visitorid - char(37)

and two more columns: accessed_from_mobile (boolean) and browser_code (int)

The columns which we need to copy to the table are the first four coumns : timestamp, latitude, longitude and visitorid.

NOTE: The file comes with a header. So use the ‘HEADER’ option in the ‘COPY’ command.

-----------------------------------------------------------
_________________________________________________________________________________________________________________
# Solution Hints
<img width="730" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/37625204-5f39-4816-b961-ca5280ac1ef1">
<img width="736" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/e0a9ed1f-411f-4937-9f1a-b159840a38f0">
<img width="720" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/ef11f8b6-5427-46a5-9aa0-5be330208c0f">
<img width="728" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/e27884ed-2bbe-43f9-b06c-fe42037401c1">
<img width="724" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/02cb2e2b-79d9-49d6-b066-42ea6e688779">



# Other helpful commands and examples for ETL process.
<img width="720" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/fced9050-1079-4528-abda-225cae66f820">
<img width="733" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/6b06b329-d5a3-4891-94ae-dcab8fdc7cc3">
<img width="733" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/4f399103-098a-4f03-a823-c845bfbae9ac">
<img width="736" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/39e0ac82-538d-4268-aa21-d9d3acdbc5cb">
<img width="729" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/6cf04229-dede-4067-a14c-2d22a2566a38">
<img width="719" alt="image" src="https://github.com/kwagle7/ETL-Using-Shell-Scripts/assets/13037108/202c1b0d-9d67-4a47-bc6e-005403d999d6">
