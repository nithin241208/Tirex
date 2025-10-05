# Tirex
e=[] while 1:  c=input("a:Add s:Summary e:Exit> ")  if c=="a":e+=[(input("Cat:"),float(input("Amt:")))]  elif c=="s":   d={}   [d.update({k:d.get(k,0)+v}) for k,v in e]   print(d,sum(v for _,v in e))  elif c=="e":break
