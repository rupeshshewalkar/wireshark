# wireshark

-Wireshark tool used to read packet data

# Display Filters 

1. To Compare field with certain value

        == eq : used to find packets equal value
        != ne : used to find packet not equal value
        > gt  : used to find greater than value
        >= ge : used to find great and equal to value
        < lt  : used to find less than value
        <= le : used to find less and equal to value

2. To work mainly with string fields 

        contains: used to find string value in packets
        matches : used to find regulare expersion value in packets
        
3. Logical operator:
   
         || or  : used to find multiple values using logical OR operator
         && and : used to find multiple values using logical And operator
         ! not  : used to find negate value using logical not operator
         in     : used to find membership value using logical in operatior  like find out tcp 80,443 using tcp          in {80,443}

4. Display filter color coding :
  
        red : indicate wrong filter/syntax error in display filter example tcp.port=53 instead of tcp.port==53
        green: indicate logically & syntaxily correct filter 
        yellow: indicate logically incorrect filter
        
   
# Capture Filter 

Using Capture filter wireshark capture less information as compare to display filter because capture filter capture only packets are required.


      