 SQL> create function itfact (a number) return number is 
2	fact number:=1; 
3	b number; 
4	begin 
5	b:=a; 
6	while b>0 
7	loop 
8	fact:=fact*b; 
9	b:=b-1; 
10	end loop; 
11	return(fact); 
12	end; 
13	/ 
