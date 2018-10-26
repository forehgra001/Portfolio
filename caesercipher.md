## Caeser Cipher
Caeser ciphers are ciphers that shift the value of a letter based on a certain number. For example when using a shift value of 1, a=b, b=c, c=d etc.  For our program our ciphers had to include a loop that allowed for more than one message to be encrypted (using loops), Ascii art, and the option to choose your shift value.

# My code

    print("  ___   __   ____  ____  ____  ____     ___  __  ____  _  _  ____  ____ ")
    print(" / __) / _\ (  __)/ ___)(  __)(  _ \   / __)(  )(  _ \/ )( \(  __)(  _ ")
    print("( (__ /    \ ) _) \___ \ ) _)  )   /  ( (__  )(  ) __/) __ ( ) _)  )   /")
    print(" \___)\_/\_/(____)(____/(____)(__\_)   \___)(__)(__)  \_)(_/(____)(__\_)")

    run_prog = True

    while run_prog == True:

        print("")
        clear_text = input("Type in your message:")
        print("")
        shift = int(input("choose shift"))
        print("")
        input("press enter to continue")

        cipher_text = ""

        for c in clear_text:
            if c.isalpha():
                print(c)
                current = ord(c)
                if current >96:
                    current = ord(c) -96
                    current += shift
                    current = current %26
                    current = chr(current +96)
                    cipher_text += current
                    print(cipher_text)
                else:
                    current = ord(c) -64
                    current += shift
                    current = current %26
                    current = chr(current +64)
                    cipher_text += current
     
            else:
                cipher_text += c


        print("The encrypted message is:" , cipher_text)


        menu_choice = input("type 1 to encrypt another message, type 2 to exit program.  Press enter to contiue")

        if menu_choice == "1":
            print("")
            clear_text = input("Type in your message:")
            print("")
            shift = int(input("choose shift"))
            print("")
            input("press enter to continue")

            cipher_text = ""

            for c in clear_text:
                if c.isalpha():
                    print(c)
                    current = ord(c)
                    if current >96:
                        current = ord(c) -96
                        current += shift
                        current = current %26
                        current = chr(current +96)
                        cipher_text += current
                        print(cipher_text)
                    else:
                        current = ord(c) -64
                        current += shift
                        current = current %26
                        current = chr(current +64)
                        cipher_text += current
     
                else:
                    cipher_text += c


            print("The encrypted message is:" , cipher_text)

        elif menu_choice == "2":
            break

        else:
            print("I'm sorry, I didn't understand you.  Please try again")
