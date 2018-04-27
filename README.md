# python--
算法练习题

#去除列表里的字符串
def filter_list(l):
  #return a new list with the strings filtered out
    ll=[]
    for i in range (len(l)):
        if type(l[i]) is int:
            ll.append(l[i])
    print(ll)

filter_list([1,2,'a','b'])
