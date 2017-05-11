# generic

 java generics basically have some advantages.some of them are Like:-
 it is type-safe:-in simple words we can say that if i gotta store similar kind of data in an arraylist.
 we can use it as it doesn't allowanyother type to store data.
 with the help of it we don't need to do additional typecasting.                                                    
 
 without using generics it will be like:-                                                                                                  
 List list = new ArrayList();                                                                                                              
 list.add("without generics");                                                                                                               
 String s = (String) list.get(0);// cast is needed                                                                                                                                                                                                                                
 
 By using generics                                                                                             
 List<String> list = new ArrayList<>();                                                                              
 list.add("hello generics");                                                                                                               
 String s = list.get(0);   // no cast

it can also used to store values in key value pair  using Generic Map.

 My sample code also include generics 2 type parameters.
 
 Enabling programmers to implement generic algorithms.
    By using generics, programmers can implement generic algorithms that work on collections of different types,
    can be customized, and are type safe and easier to read.
