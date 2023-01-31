def Parenthesis(str,n):
    if(n > 0):
        _Parenthesis(str,0,n,0,0)
    return
def _Parenthesis(str,pos,n,open,close):
    if(close==n):
        for i in str:
            print(i,end="")
        print()
        return
    else:
        if(open>close):
            str[pos] = '}'
            _Parenthesis(str,pos+1,n,open,close+1)
        if(open<n):
            str[pos] = '{'
            _Parenthesis(str,pos+1,n,open+1,close)
n =int(input("enter no of paranthesis="))
str = [""] * 2 * n
Parenthesis(str, n)
