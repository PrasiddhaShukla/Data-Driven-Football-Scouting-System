# Data-Driven-Football-Scouting-System
This is a Completely Data driven Football Scouting System. This involves 100+ Football Data/Stats of over 2000+players, to determine which player suits a particular managerial Playstyle. The data is imported on to My-SQL and then imported over to python to create a user interface using Tkinter library in python.

How to Run the Program..
1. Download the csv files given,
2. Run the mysql code.
3. Import the data from the csv files in the created tables using the table data import wizard OR directly import the csv files into python and change the code accordingly.
4. Update the Host name and password of your mysql in your device in the python code
5. Run the python code file to get the output


System Specifications

A] Hardware Specifications

The football scouting system is a data-driven application, meaning it predominantly relies on software for processing and analyzing player data. However, hardware components play an important role in supporting the system, especially during data entry, testing, and running the system. Below are the detailed hardware specifications:
1.	Computer System (PC/Laptop)
o	Processor: Intel i5 or above (or equivalent AMD Ryzen processor)
o	RAM: Minimum of 8 GB RAM for smooth operation
o	Storage: At least 500 GB of hard drive or SSD storage for storing databases and large datasets
o	Operating System: Windows 10 or 11, macOS, or a Linux-based OS such as Ubuntu
o	Display: Full HD (1920x1080) display for better visualization and interaction with the system’s graphical user interface (GUI)
2.	Internet Connection (for data retrieval and updates)
o	Speed: Minimum of 5 Mbps for cloud-based data storage, API access, and other web-based services (if used)
o	Type: Wired or wireless broadband connection for seamless data access and updates
3.	Database Server (Optional for large scale)
o	Processor: Dual-core or higher processor
o	RAM: Minimum 4 GB (8 GB recommended for large datasets)
o	Storage: SSD recommended for faster data retrieval, especially for large player datasets
o	Network Interface: Ethernet or Wi-Fi connection to ensure stable connection to the main application for database synchronization
4.	Backup Storage Device (For Data Security)
o	External Hard Drive/Cloud Storage: For backing up the database, ensuring data redundancy and protection against hardware failure.

B] Software Specifications

The software components of the football scouting system enable the processing, management, and visualization of player data. These components are selected based on the project's requirements for performance, scalability, and usability.
1.	Operating System:
o	Windows 10/11, macOS, or Linux: Any of these operating systems will work, but Windows 10/11 or Linux (Ubuntu) is most commonly used for database management and Python programming in professional setups.
2.	Database Management System (DBMS):
o	MySQL: An open-source relational database management system (RDBMS) used to store player data, such as statistics, player profiles, match records, and other relevant information. It provides a reliable and scalable platform for querying and managing large datasets efficiently.
o	Backup Tool: Tools like MySQL Workbench for managing databases and performing routine backups of player data and system settings.
3.	Programming Languages:
o	Python: Python is the primary programming language used to implement the data processing, querying, and analysis functionalities of the system. Python’s libraries make it a great choice for data manipulation, machine learning, and GUI development.
	Libraries Used:
	Pandas: For data manipulation and analysis, including cleaning and transforming player data into useful formats.
	Numpy: For numerical calculations, especially when performing statistical analysis on player performance metrics.
	Tkinter: For creating a graphical user interface (GUI) that allows scouts to filter and search for players based on different criteria and view the results in a structured format.
	SQLAlchemy: For managing the database connection in a more abstracted and flexible manner, using SQLAlchemy’s ORM (Object-Relational Mapping) to interact with the MySQL database. It allows for easier querying and database management within the Python environment.
	Tkinter (with ttk): For building a GUI that allows users to interact with the system by providing input and viewing player data in a tabular or graphical format. The ttk module is used for more modern, themed widgets, improving the UI appearance and functionality.
	tkinter.messagebox: For displaying pop-up message boxes in the GUI, such as showing confirmation messages or alerts when certain actions are completed (e.g., saving data, filtering results).
4.	Data Storage and Backup:
o	Cloud Storage Solutions: Services like Google Drive, Dropbox, or AWS S3 (for larger datasets) to store backups of the player data and system configuration files.
o	Local Storage: The database will be primarily stored locally on the system or server (as mentioned in the hardware section) to ensure fast access.
5.	Data Processing & Analysis Tools:
o	Excel or CSV Files: For importing/exporting data, as player statistics are often available in CSV format. The system will support importing player data from CSV files, which can be processed and stored in the database.
