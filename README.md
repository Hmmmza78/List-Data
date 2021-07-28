# List-Data
def Data_Function():
	Data_list = []
	index = int(input("Number of elements in the list"))
	for i in range(0,index):
		Data = int(input())
		Data_list.append(Data)
	
	    
	
	Data_1_10 = []
	Data_11_20 = []
	Data_21_30 = []
	
	for i in Data_list:
		if (i>=1) and (i<=10):
			Data_1_10.append(i)
		elif (i>=11) and (i<=20):
			Data_11_20.append(i)
		else:
			Data_21_30.append(i)
			
	print("Total Data =" , Data_list)
	print("1 to 10 = " , Data_1_10)
	print("11 to 20 = " , Data_11_20)
	print("21 to 30 = " , Data_21_30)
	
Data_Function()
