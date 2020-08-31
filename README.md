class node:
    def __init__(self, data):
     self.data=data
     self.data=None;
class LinkedList:
    def __init__(self):
     self.start=None;
def deleteFirst(self):
         if self.start==None:
             print("linkedlist is empty")
         else:
            self.start=self.start.next
def viewList(self):
        if self.start==None:
              print("list is empty")
        else:
            temp=self.start
        while temp!=None:
                print("temp.data,end= ' '")
                temp=temp.next   
def insertLast(self, value):
        newNode=node(value)
        if (self.start==None):
            self.start=newNode;
        else:
           temp=self.start
        while temp.next!=None:
               temp=temp.next
               temp.next=newNode
Mylist=LinkedList()
Mylist.insertLast(10)
Mylist.insertLast(20)
Mylist.insertLast(30)
Mylist.insertLast(40)
Mylist.viewList()
print()
Mylist.deleteFirst()
mylist.viewList()
