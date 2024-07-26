#Calculate the money, which is deposited in a piggybank,with different denominations 
#The following are the different dinominations used:1, 2, 5, 10
#Input 10=2, 5=4, 2=5, 1=1. Output=51
Ten=int(input("Enter 10 denominations:"))
Five=int(input("Enter 5 denominations:"))
Two=int(input("Enter 2 denominations:"))
One=int(input("Enter 1 denominations:"))
Total=(10*Ten)+(5*Five)+(2*Two)+(1*One)
print("The total amount in the piggybank:",Total)
