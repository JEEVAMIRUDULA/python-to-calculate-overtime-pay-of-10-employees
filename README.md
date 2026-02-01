# python-to-calculate-overtime-pay-of-10-employees
ovpay=0
sum=0
for i in range(1,11):if(h&gt;40):
print(&quot;Enter Working Hours of Emp &quot;,i,&quot;:&quot;)
h=int(input())

extra=h-40
ovpay=extra*12
print(&quot;Over time pay of emp &quot;,i,&quot; is &quot;,ovpay)
sum=sum+ovpay
else:
print(&quot;No Overtime Pay&quot;)

print(&quot;Total Overtime Pay of all employees : &quot;, sum)

Output:
Enter Working Hours of Emp 1 :
50
Over time pay of emp 1 is 120
Enter Working Hours of Emp 2 :
56
Over time pay of emp 2 is 192
Enter Working Hours of Emp 3 :
45
Over time pay of emp 3 is 60
Enter Working Hours of Emp 4 :
280
Over time pay of emp 4 is 2880
Enter Working Hours of Emp 5 :
550
Over time pay of emp 5 is 6120
Enter Working Hours of Emp 6 :
43
Over time pay of emp 6 is 36
Enter Working Hours of Emp 7 :
88
Over time pay of emp 7 is 576
Enter Working Hours of Emp 8 :
56
Over time pay of emp 8 is 192
Enter Working Hours of Emp 9 :
62
Over time pay of emp 9 is 264
Enter Working Hours of Emp 10 :
90
Over time pay of emp 10 is 600
Total Overtime Pay of all employees: 11040
_________________________________
