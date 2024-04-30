[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/234bMY4A)

CSL2020 | Data Structure and Algorithms | Jan2024 

Instructor: - Suchetana Chakraborty

Group Project:
Topic: - Navigating Airports Using Graph Algorithms

Mentor TA's : - Jainan Nareshkumar Tandel (M23CSA010) & Dhruv(B20EE016) 


Team Menmbers : -
1. Vishwjeetsinh Jadeja (B22MT023)
2. Aaditya Kamble (B22MT024)
3. Sahil (B22MT038)
4. Ghanshyam Suthar (B22PH009)

In case of any Problem while using this codes contact Aaditya Kamble (b22mt024@iitj.ac.in)

***This File Contains Instructions on how to use the codes submitted by our group***
Link to the Github Repo: - "https://github.com/DSA-IITJ-2024/ideathon-code-submission-b22mt024"

what our subbmission contains: -
A) 2 csv files
    1. airports_final.csv
    2. routes_final.csv

B) 3 'c' code files
    1. dijkstra.c
    2. Bellman.c
    3. floyd.c

C) 1 svg file
    1. visualization.svg
D) 1 xl file

**How to Use**
1. Make sure that two csv files and 3 code files are placed in same folder.
2. open cmd in the folder all files are placed.
3. Use the following comands 
      To Compile: -
          Dijkstra: - "gcc -w dijkstra.c -o dijkstra"
          Bellman-Ford: - "gcc -w Bellman.c -o bellman"
          Floyd: - "gcc -w floyd.c -o floyd"
        
        make sure to include "-w" while compiling to avoid any errors.
          
      To Execute: -
          Dijkstra: -"dijkstra"
          Floyd: -"floyd"
          Bellman-Ford: -"bellman"
        
4. If you are using VS code you can run the following comands in the terminal from VS Code
        while executing the program 
        dijkstra.c: -"./dijkstra"
        Bellman.c: -"./bellman"
        floyd.c: - "./floyd"

5. After Executing The program will ask for input and output IATA codes For that you can reffer to the CSV files the airports file contains informatation of every airport there you can find IATA codes, there is also a routes csv file where only the IATA codes are mentioned of source and destinatation airports.
6. There is a SVG File that was gentrated on this dataset which visvalizes the data along with the weights you can refer to that to verify the output.
7. the timecomplexity.xlxs file contains the result graphs.
