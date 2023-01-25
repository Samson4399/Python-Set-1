# Python-Set-1
# Python Programing Set 1
def pairsum(list,target):
  result=[]
  loop=1
  for x in list:
    for y in list:
      if x+y == target:
        result.append((x,y))
    list=list[loop:]
    loop += 1
  return result
