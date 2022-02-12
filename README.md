# 12-02-2022-assignment-1
#super market bill
ir=40
rg=70
gg=100
bg=100
oil=125
cname=input('enter customer name:')
cphno=input('enter customer phone number:')
irq=int(input('enter idly ravva quantity in KG:'))
rgq=int(input('enter red gram quantity in KG:'))
ggq=int(input('enter green gram quantity in KG:'))
bgq=int(input('enter black gram quantity in KG:'))
oilq=int(input('enter oil quantity in litres:'))
bill=(ir*irq)+(rg*rgq)+(gg*ggq)+(bg*bgq)+(oil*oilq)
if bill>=5000:
    dis=bill*10/100
elif bill>=3000:
    dis=bill*8/100
elif bill>=2000:
    dis=bill*5/100
elif bill>=1000:
    dis=bill*3/100
if bill>=3000:
    tax=bill*10/100
else:
    tax=bill*18/100
mainbill=bill-dis+tax
print('discount:',dis)
print('tax:',tax)       
print('main bill',mainbill)


output:
====================== RESTART: C:\Python37\sup bill.py ======================
enter customer name:madhu
enter customer phone number:9123456789
enter idly ravva quantity in KG:5
enter red gram quantity in KG:4
enter green gram quantity in KG:6
enter black gram quantity in KG:6
enter oil quantity in litres:10
discount: 146.5
tax: 527.4
main bill 3310.9
>>> 
