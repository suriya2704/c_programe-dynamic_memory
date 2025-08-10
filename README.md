# c_programe-dynamic_memory
char letters[] = {'A','B','C'};
char *cp = letters;

printf("%c\n", *cp);   // A
cp += 2;
printf("%c\n", *cp);   // C
cp--;                  
printf("%c\n", *cp);   // B
