print("pess v for harry diet")
print("press h for rohan diet")
print("press n for hammad diet")
a=("v")
b=('h')
c=('n')
v=input("whoes diet you want to add")

while (1):
    if v==a:
        print("a= excersice\nb=diet")
        q="a"
        w="b"
        x=input("enter a or b")
        if x==q:
            r=input("enter excersice")
            with open("harryexc.txt","a") as f:
                f.write(r)
                break
        if x==w:
            z=input("enter diet food")
            with open("harrydiet.txt","a") as m:
                m.write(z)
                break
        else:
            print("please select correct option")
    
    if v==b:
        print("a=exercise\nb=diet")
        t='a'
        y='b'
        u=input("enter a or b")
        if u==t:
            i=input("enter exercise")
            with open("rohanexc.txt","a") as m:
                m.write(i)
                break
    
        if u==y:
            i=input("enter diet")
            with open("rohandiet.txt","a") as m:
                m.write(i)
                break
            
        else:
            print("please select correct option") 
            
         
    if v==c:
        print("a= excercise\nb=diet")
        r="a"
        u="b"
        o=input("eneter a or b")
        if o==r:
            p=input("enter excersice")
            with open("hammadexc.txt","a") as m:
                m.write(p)
                
        if o==u:
            p=input("enter diet")
            with open("hammad.txt","a") as m:
                m.write(p)
    
    
        else:
            print("please select correct option")
    
    else:
        print("please enter correct option")
        break 
