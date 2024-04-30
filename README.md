[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/234bMY4A)



---

## CSL2020 | Data Structure and Algorithms | Jan2024 

**Instructor:** Suchetana Chakraborty

**Group Project:**
- **Topic:** Navigating Airports Using Graph Algorithms
- **Mentor TAs:** 
  - Jainan Nareshkumar Tandel (M23CSA010)
  - Dhruv (B20EE016)

**Team Members:**
1. Vishwjeetsinh Jadeja (B22MT023)
2. Aaditya Kamble (B22MT024) - [b22mt024@iitj.ac.in](mailto:b22mt024@iitj.ac.in)
3. Sahil (B22MT038)
4. Ghanshyam Suthar (B22PH009)

**GitHub Repo:** [ideathon-code-submission-b22mt024](https://github.com/DSA-IITJ-2024/ideathon-code-submission-b22mt024)

**Contents:**
- **CSV Files:**
  1. airports_final.csv: Contains all the airport information which are used as vertices.
  2. routes_final.csv: Contains all the routes data which is used for making edges.
- **C Code Files:**
  1. dijkstra.c
  2. Bellman.c
  3. floyd.c
- **Other Files:**
  1. visualization.svg: Shows the visualization for the made graphs.
  2. Distance_matrix.txt: Contains the output matrix given by the Floyd algorithm.
  3. timecomplexity.xlxs: Contains all the results and graphs.
  4. DSAIdeathon.pptx: Presentation.
  5. DSAIdeathon.pdf: Presentation.
  
**PPT Link:** [https://www.canva.com/design/DAGD0ScPLPQ/Yi3yC_BpVxUc4rswWLn8ow/edit](https://www.canva.com/design/DAGD0ScPLPQ/Yi3yC_BpVxUc4rswWLn8ow/edit)

**How to Use:**
1. Make sure that two CSV files and three code files are placed in the same folder.
2. Open cmd in the folder where all files are placed.
3. Use the following commands to compile:
   - **Dijkstra:** 
     ```
     gcc -w dijkstra.c -o dijkstra
     ```
   - **Bellman-Ford:** 
     ```
     gcc -w Bellman.c -o bellman
     ```
   - **Floyd:** 
     ```
     gcc -w floyd.c -o floyd
     ```
   Ensure to include "-w" while compiling to avoid any errors.
4. To execute the programs, use the following commands:
   - **Dijkstra:** 
     ```
     dijkstra
     ```
   - **Bellman-Ford:** 
     ```
     bellman
     ```
   - **Floyd:** 
     ```
     floyd
     ```
5. If you are using VS Code, you can run the following commands in the terminal:
   - **dijkstra.c:** 
     ```
     ./dijkstra
     ```
   - **Bellman.c:** 
     ```
     ./bellman
     ```
   - **floyd.c:** 
     ```
     ./floyd
     ```
6. After executing, the program will ask for input and output IATA codes. You can refer to the CSV files for airport information. The routes CSV file contains information about the source and destination airports.
7. Use the visualization.svg file to verify the output.


**Note:** Ensure that the "-w" flag is included while compiling to avoid errors.

---
