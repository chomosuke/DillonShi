# DillonShi

## Language specification
a proposal:
Everything is an object calling their member function
for example 2.add(3)

we can also have a.equals(b).if(somefunction());

you can initialize a reference to int by: int n;

and then set it by: n.set(3);

now n.equals(3); would return true 

not that true is an object of boolean type

we can do n.equals(3).if(somefunction());

in this case if n == 3, somefunction will be executed

.if() is a member function of boolean

somefunction() is passed into .if() as a parameter (kind of like function pointer in c)

and i feel like this would just be a clone of smalltalk...
