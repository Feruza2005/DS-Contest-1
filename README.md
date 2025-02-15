# DS-Contest-1
Task1.py
def kwargsAcceptFun(**a):
    print("Named arguments:")
    for key, val in a.items():
        print(key,":",val)

#Call    
kwargsAcceptFun(name="Feruza", age=20, country="Uzbekistan")
