# 30DaysOfCode---HackerRank

M=float(input())
T=int(input())
X=int(input())

tip=(T*M)/100 
tax=(X*M)/100 
price=M+tip+tax

print "The final price of the meal is $%s." %int(round(price))
