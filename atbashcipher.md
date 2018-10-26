## Atbash Cipher
The first cipher program that we created was a ceaser cipher using Atbash. For this cipher we had to create a program that would encrypt a simple cipher.

## My code
    print("Welcome to Atbash Cipher program")
    input("press enter to continue")

    print("")
    clear_text = input("Type in your message:")
    clear_text = clear_text.lower()
    print("")

    input("press enter to continue")
    cipher_text = clear_text.replace("a","Z")
    cipher_text = cipher_text.replace("b","Y")  
    cipher_text = cipher_text.replace("c","X")
    cipher_text = cipher_text.replace("d","W")
    cipher_text = cipher_text.replace("e","V")
    cipher_text = cipher_text.replace("f","U")
    cipher_text = cipher_text.replace("g","T")
    cipher_text = cipher_text.replace("h","S")
    cipher_text = cipher_text.replace("i","R")
    cipher_text = cipher_text.replace("j","Q")
    cipher_text = cipher_text.replace("k","P")
    cipher_text = cipher_text.replace("l","O")
    cipher_text = cipher_text.replace("m","N")
    cipher_text = cipher_text.replace("n","M")
    cipher_text = cipher_text.replace("o","L")
    cipher_text = cipher_text.replace("p","K")
    cipher_text = cipher_text.replace("q","J")
    cipher_text = cipher_text.replace("r","I")
    cipher_text = cipher_text.replace("s","H")
    cipher_text = cipher_text.replace("t","G")
    cipher_text = cipher_text.replace("u","F")
    cipher_text = cipher_text.replace("v","E")
    cipher_text = cipher_text.replace("w","D")
    cipher_text = cipher_text.replace("x","C")
    cipher_text = cipher_text.replace("y","B")
    cipher_text = cipher_text.replace("z","A")

    print(cipher_text)
    
    
    
