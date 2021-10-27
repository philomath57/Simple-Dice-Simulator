# Simple-Dice-Simulator
from random import randint
x = randint(1,6)


if x==1:
  print ("[0 0 0]")
  print ("[0 * 0]")
  print ("[0 0 0]")

elif x==2:
  print ("[0 0 0]")
  print ("[* 0 *]")
  print ("[0 0 0]")

elif x==3:
  print ("[* 0 0]")
  print ("[0 * 0]")
  print ("[0 0 *]")

elif x==4:
  print ("[* 0 *]")
  print ("[0 0 0]")
  print ("[* 0 *]")

elif x==5:
  print ("[* 0 *]")
  print ("[0 * 0]")
  print ("[* 0 *]")

else:
  print ("[* * *]")
  print ("[0 0 0]")
  print ("[* * *]")
