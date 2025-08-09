algo string_handling
var phrase:string, 
var word_num:integer, char_number:integer, voyel_num:integer, i:character
begin 
write("give your phrase and put \' . \' ")
read(phrase);
word_num := 1
char_number := 0
voyel_num := 0
for each i in phrase then 
   if (i=' ') then 
	    word_num := word_num +1 
   end if 
   if (i='o' or i='i' or i='y' or i='e' or i='a' or i='u' or i='O' or i='I' or i='Y' or i='E' or i='A' or i='U') then 
	    voyel_num := voyel_num+1
   end if 
   char_number := char_number+1
   if (i='.') then 
      break
   end if
end for
write("the number of character is :",char_number,"the number of word is :",word_num,"the number of voyel is :",voyel_num)
end 
