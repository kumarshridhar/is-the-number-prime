# is-the-number-prime
n=int(input('enter number:'))
if(n<2):
  print('not prime')
else:
  flag=True
  for i in range(2,n):
    if(n%i==0):
      print('not prime')
      flag=False
      break
  if(flag):
    print('prime')
