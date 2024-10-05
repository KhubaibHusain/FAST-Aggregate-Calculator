# FAST-Aggregate-Calculator
This python code will allow the user to check it's aggregate if he/she wants admission in FAST by asking them their marks. It's quite useful

FSC_Total_Marks = int(input("Enter Total Marks of FSc: "))
FSC_Obtained_Marks = int(input("Enter Obtained Marks of FSc: "))
Fsc_Criteria = (FSC_Obtained_Marks / FSC_Total_Marks) * 100
FSc_Aggregate = (Fsc_Criteria) * 0.50


EntryTest_Total_Marks = int(input("Enter Total Marks of EntryTest: "))
EntryTest_Obtained_Marks = int(input("Enter Obtained Marks of EntryTest: "))
EntryTest_Criteria = (EntryTest_Obtained_Marks / EntryTest_Total_Marks) * 100
EntryTest_Aggregate = (EntryTest_Criteria) * 0.50


Overall_Aggregate = FSc_Aggregate + EntryTest_Aggregate
print("Your aggregate is ", Overall_Aggregate, "%")
