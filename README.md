# CPSC 368 Group 04 Group Project
This is a file that details some things that the teaching team should know about before running our project code.

## Project Short Summary
This project focuses on exploring the relationships between GDP, PM2.5 air pollution levels, the provision of safely managed sanitation, and global mortality rates. Economic development, air pollution levels, the provision of safely managed sanitation, and global mortality rates are all related to sustainable human development. Exploring the links between mortality rates helps us to analyse the situation and helps us to make the right decisions.

## Prerequisites
Before running the project, please ensure the following prerequisites are met:

- Access to Syzygy with Jupyter terminal.
- An Oracle account is available for database access (provided by our team).
- Python environment (oracledb packages installed).

## Getting Started

### Step 1: Tunnelling to the department server

In Jupyter terminal, use one of our group members's Oracle account

```bash
ssh -l yy1108 -L 127.0.0.1:1522:dbhost.students.cs.ubc.ca:1522 remote.students.cs.ubc.ca
```
### Step 2: Install OracleDB Python Package

```bash
pip install oracledb
```

### Step 3: Navigate to the Project Directory
Change your working directory to where the project data is stored:

```bash
cd cpsc368
```

### Step 4: Connect to the Oracle Database

```bash
rlwrap sqlplus ora_yy1108@stu
```

Password might be needed, which is a89657605

### Step 5: Open the SQL file

```bash
start project.sql
```
## Step 6: Exit the SQL server

```bash
exit
```

## Step 7: Open the data analysis file in Jupter

Finally, open the data analysis Jupyter notebook provided by our team. Follow the instructions within the notebook.

For any questions related to the project, please feel free to contact any of our group members. Thank you for your cooperation and interest in our project.

