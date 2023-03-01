# declensions
Declension of words from the languages depending on the count.

# Language

    Python 3.10.4
    
# Instalation 

    pip install declensions


# How it works
The program declines words using 3 arguments that the user must pass to the program:
      
    word - the singular word that will incline;
    quantity - the number depending on which the word will be inclined;
    endings - possible endings of the transmitted word depending on the declension variant* Example: {'first': 'ека', 'second': 'ек'}.
    
    [*] - there are two declension options - the first and the second. 
          The first option is a declination in which the last digit in the number is equal to one of these numbers - '2', '3', '4'; 
          The second option is that the last digit in the number is equal to one of these numbers -'5', '6', '7', '8', '9', '0'. 
          
After processing the arguments passed by the user, the program calculates the last digit in the number in order to select one of the declination options. After the declension variant is selected, the program recognizes the ending in the word and replaces it with one of the endings specified in the argument - endings.


# Important

At the moment, the program supports only Russian, but others will be added later.
