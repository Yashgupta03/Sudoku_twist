1. sudoku_pair_solver.py
  In this we have implemented our first problem.
  5 test cases are as follows-:
    a. input csv file is Q1_test_1.csv
    b. input csv file is Q1_test_2.csv
    c. input csv file is Q1_test_3.csv
    d. input csv file is Q1_test_4.csv
    e. input csv file is Q1_test_5.csv

  5 output file are-:
    a. Q1_out_1.csv
    b. Q1_out_2.csv
    c. Q1_out_3.csv
    d. Q1_out_4.csv
    e. Q1_out_5.csv


2. sudoku_pair_generator.py
  In this we have implemented 2nd problem.
  5 test cases are-:
    a.Q2_k2_1.csv              here k2 means k=2,and Q2 means 2nd quest. case
    b.Q2_k2_2.csv              no. signifies test no.
    c.Q2_k3_1.csv
    d.Q2_k3_2.csv
    e.Q2_k4_1.csv

  5 output file are-:
    a. Q2_k2_1_sol.csv
    b. Q2_k2_2_sol.csv
    c. Q2_k3_1_sol.csv
    d. Q2_k3_2_sol.csv
    e. Q2_k4_1_sol.csv

3. sudoku_solver.py
 is for pointing out effeciency issue, as stated in approach.pdf/ approach.txt

4. Kindly make sure by default we had make input file as testo_1.csv
   And output file as testo_2.csv

   these files are made so as to ease checking procedure and our final solution test  file is in folder tests.

   To check our result kindly change input reader and output reader file in Q1 and only output reader in Q2.

   NOTE-: To change name of file please kindly enter whole path name as
   tests/Q1_test_1 or tests/test_name.

   and in output file as tests/out_file_name.
   like tests/Q1_out_1

5. For better testing we also comment out print statement which serves the purpose of printing in console and not in file you can run it also for testing.

6. in Q1 we also have a block which can take input to be all 0. it is also commented. also for easy evaluation.