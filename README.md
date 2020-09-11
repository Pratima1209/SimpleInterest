# SimpleInterest
#Python Program for simple interest
p=int(input("Enter the Principle Amt:"))
r=int(input("Enter the Rate of Interest:"))
t=int(input("Enter the Period:"))

def simple_int(p,r,t):
    si=(p*r*t)/100
    return si

ans=simple_int(p,r,t)
print("Simple Interest of is {3}".format(p,r,t,ans))
