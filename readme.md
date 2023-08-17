# Generate customer data with the Benerator

Proof of concept: using the [Benerator](https://www.benerator.de/) to generate customer data for Profile Core Banking System 
based on the **csv** files from the **data** directory.
Benerator supports dictionary (look-up) tables - in this project 39 such files with random distribution. 

*** 

- To start this project you need to download the [Benerator](https://github.com/rapiddweller/rapiddweller-benerator-ce/releases) release from GitHub.
 Tested at the Community Edition 3.1.0-jdk-11 version.
- Set the BENERATOR_HOME env variable and add **bin** folder to your **PATH**
- Open project directory and run `benerator` command
- It executes the **benerator.xml** script and generates customer data
- New data are written in the **cif-data.csv** file

***

### Problems to solve:

- Proper support script code for i.e. JavaScript (GraalVM is required)
