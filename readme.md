# Predicting-severity-of-Eosinophile-Oesofagitis-with-machine-learning  
  
## how to use the commandline interface of the model  

To run the program as a .jar download this entire folder: jars/latest/  

Then go to the folder where you saved the libs folder and type the following in the terminal to run on the test csv file.   
Or change folder path after the "-f" flag to classify your own csv  
`java -jar model-cli.jar -f testdata/test.csv`  

Or to run on a single instance:     
And change the values after the "-i" flag to run on your own instance.    
With the attributes in the following order:     
Neocate, Gender, B.Carbohydrates.gr, B.PUFAS.gr, B.Linoleicacid.gr, B.Calcium  

`java -jar model-cli.jar -i 1,1,20.76,1.49,19.24,1.45`  
  
This program has the following options  
-h show help  
-f input csv file   
-i classify a single instance  
