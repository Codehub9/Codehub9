import datetime
def getdate():
    return datetime.datetime.now()

print('                          health management')
print('=================================================================')
print(" welcome i am coach here\n ask 1=lock,2=retrive")
l=int(input("1 or 2"))

    
while (1):
    if l==1:
        print("pess v for harry ")
        print("press h for rohan ")
        print("press n for hammad ")
        print()
        c=('n')
        v=input("whoes diet you want to add")
    
        if v==a:
            print("a= excersice\nb=diet")
            q="a"
            w="b"
            x=input("enter a or b")
            if x==q:
                r=input("enter excersice")
                with open("harryexc.txt","a") as f:
                    f.write(str([str(getdate())])+":"+r+"\n")
                    break
            if x==w:
                z=input("enter diet food")
                with open("harrydiet.txt","a") as m:
                    m.write(str([str(getdate())])+":"+z+"\n")
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
                    m.write(str([str(getdate())])+":"+i+"\n")
                    break
    
            if u==y:
                i=input("enter diet")
                with open("rohandiet.txt","a") as m:
                    m.write(str([str(getdate())])+":"+i+"\n")
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
                    m.write(str([str(getdate())])+":"+p+"\n")
                    break                
            if o==u:
                p=input("enter diet")
                with open("hammad.txt","a") as m:
                    m.write(str([str(getdate())])+":"+p+"\n")
                    break
    
            else:
                print("please select correct option")
    
        else:
            print("please enter correct option")
            break 
    elif l==2:
        print("whoes file want to retrive\na==harry\nb==rohan\nc==hammad")
        
        
        
        v=input("enter a or b or c")
        q="a"
        e="b"
        y="c"
        
    
        if v==q:
            print("a= excersice\nb=diet")
            q="a"
            w="b"
            x=input("enter a or b")
            if x==q:
                
                with open("harryexc.txt") as f:
                    b=f.read()
                    print(b)
                    break
            if x==w:
                
                with open("harrydiet.txt") as m:
                    b=m.read()
                    print(b)
                    break
            else:
                print("please select correct option")
    
        if v==e:
            print("a=exercise\nb=diet")
            t='a'
            y='b'
            u=input("enter a or b")
            if u==t:
                    
                with open("rohanexc.txt") as m:
                    b=m.read()
                    print(b)
                    break
    
            if u==y:
                    
                with open("rohandiet.txt") as m:
                    b=m.read()
                    print(b)
                    break
            
            else:
                print("please select correct option") 
            
         
        if v==y:
            print("a= excercise\nb=diet")
            r="a"
            u="b"
            o=input("eneter a or b")
            if o==r:
                
                with open("hammadexc.txt") as m:
                    b=m.read()
                    print(b)
                    break
            if o==u:
                
                with open("hammad.txt") as m:
                    b=m.read()
                    print(b)
                    break
    
    
            else:
                print("please select correct option")
    
        else:
            print("please enter correct option")
            
    else:
        print("please choose correct option")
        break 
