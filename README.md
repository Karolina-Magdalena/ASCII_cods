# ASCII_codes
Firstly I used char but polisch letters had then minus value.
I changed it for unsigned char but polisch letters had then strange values.
Then I used unsigned char array, but I had problems with the SIGSEGV error.
I decided to use string for all given letters.

Questionable was the beginning:

correct answer was:

while((a=cin.get())!=EOF)
    {

insted:

while (getline(cin,wyraz))
    {
