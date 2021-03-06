# Inverse-Airfoil-Design  
Project on Inverse Airfoil Design  
Initial Airfoil which is to be modified is NACA0015 and target airfoil to be achieved is NACA0009.   
C*p* of the airfoils is plotted using [XFOIL](http://web.mit.edu/drela/Public/web/xfoil/) Software by Mark Drela MIT.  
Project is Under [Prof. A M Pradeep](https://www.aero.iitb.ac.in/~ampradeep/), [Aeropsace Dept.](https://www.aero.iitb.ac.in/home/) [IIT Bombay](http://www.iitb.ac.in/)  
Here is the Airfoil Generated  
![alt tag](https://raw.githubusercontent.com/utkarsh17091996/Inverse-Airfoil-Design/master/result.png)  
Corresponding C*p* Plots  
![alt tag](https://raw.githubusercontent.com/utkarsh17091996/Inverse-Airfoil-Design/master/cpresult.png)   
Corresponding C*p* Plots  
![alt tag](https://raw.githubusercontent.com/utkarsh17091996/Inverse-Airfoil-Design/master/l2norm.png)  
# Install Xfoil in Ubuntu 14.04 #  

run *sudo apt-get install xfoil* in terminal   

# How to Run the code on Ubuntu 14.04 #  

1) Clone the repository  
2) Make sure that it has Modified.csv file is present  
3) Run linux_code.py  
4) Wait for the iterations  to complete  
5) After iterations are completed Airfoils and C*p* plots will automatically generate  
6) **Important** In order to run the code again delete **Modified.csv, ModifiedCP.csv, n0009CP.csv and n0015CP.csv** and put a new copy of Modified.csv now run the main code (Plots will be automatically replaced)  

*Ignore the Warning for replacing modified.csv as by default it automatically replaces it*
