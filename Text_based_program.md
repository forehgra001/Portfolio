Text based program
For this program we had to create a program that provided the user information over a specific topic, while using loops, menu choices, subsections, and color.

For my prodject I provided information over the Greek gods.(The syntax for some of the indents is incorrect, because other wise the program would not properly appear on the screen)
# My Code

    print("")
    print("\033[1;4;31m The Greek Gods \033[0m")
    print("")
    input("\033[33m press enter to continue\033[0m")
    print("")
    print("\033[32m In ancient Greece, the Greeks believed in the twelve Olympian Gods.  These Gods were powerful deities that lived on Mount Olympus.  All of the Gods resided on Mount Olympus, except for Persephone and Hades who lived in the Underworld.  These gods were created by the Greeks in order to explain how the world around them worked.  Each god represented a/n element of the natural world.  Although there were many minor Gods, only the main twelve were worshipped.\033[0m")
    print("")
    input("\033[33m press enter to continue\033[0m")
    print("")



    while True:

    menu_choice = input("\033[3;46;37m type 1 to learn about the Gods, or type 2 to learn about the Godesses. To exit, type x. Press enter to finalize your choice.\033[0m")



    
    if menu_choice == "1":
        print("")
        print("\033[1;3;4;31m Gods \033[0m")
        print("")
        input("\033[33m press enter to continue\033[0m")
        print("")
        menu_choice2 = input("\033[3;46;47m press 1 to learn about Zeus,2-Poseidon,3-Hades,4-Apollo,5-Ares,6-Hephaestus,7-Hermes,or 8-Dionysus \033[0m")
        if menu_choice2 == "1":  
            print("\033[1;4;34m Zeus\033[0m") 
            print("\033[31m King of the gods, and god of the sky,  and thunder.  Seen as the protector of man, and would watch them from Olympus.  Also known for his constant strife with his wife Hera, due to his numerous affairs with mortal and immortal women.  Brother of Poseidon and Hades, and claimed the sky as his domain when they divided the world.  His prominent symbols are a thunderbolt and an eagle.\033[0m")
        print("")
        if menu_choice2 == "2":
            print("\033[1;34m Poseidon\033[0m")
            print("\033[31m God of the sea, earthquakes,storms, and horses.  Known to be very ill-tempered and moody.  Brother of Zeus and Hades, and was granted the seas when they divided the world.  Said to have created, and sired many horses, including the winged horse Pegasus.  Also competed against Athena to become the patron god of Athens, but lost. His main symbols are a trident, horses, bulls, sea foam, and dolphins.\033[0m")
        print("")
        if menu_choice2 == "3":
            print("\033[1;34m Hades\033[0m")
            print("\033[31m God of the Underworld, including riches found in the earth.  Eldest brother of Zeus and Poseidon, and was given the underworld when the three brothers divided up the world.  Ruled the Underworld with his queen, Persephone.  Aided by the Furies and his dog Cerberus, he supervised the trial and punishment of souls that came to the Underworld.  Depicted as stern and pitiless.  His symbols are Cerberus, drinking horn, scepter, and Cypress.\033[0m")
        print("")
        if menu_choice2 == "4":
            print("\033[1;34m Apollo\033[0m")
            print("\033[31m God of the sun and light, music, poetry, healing, plagues, prophecy, archery, and agriculture.  His name is the same as his Roman counterpart.  He was adored, and depicted nude to show the perfect male body.  The priestess’ of Apollo were in charge of guarding the oracles, who were said to have received prophesies from Apollo.  He is the twin brother of the Goddess Artemis, goddess of the moon. His symbols were a lyre, a bow and arrow, laurel wreaths are the main symbols used in relation to Apollo.\033[0m")
        print("")
        if menu_choice2 == "5":
            print("\033[1;34m Ares\033[0m")
            print("\033[31m God of war, meaning the violent and physical wars fought.  The son of Zeus and Hera, brother of Athena.  Although he was seen as ruthless and violent, mortals would regard him in battle for his valor and strength.  Spear, chariot, boars, and vultures.\033[0m")
        print("")
        if menu_choice2 == "6":
            print("\033[1;34m Hephaestus\033[0m")
            print("\033[31m God of the forge, fire, metalworking, stone masonry, and the art of sculpting.  Commonly known for making all the weapons for Olympus and acting as blacksmith for the gods.   Son of Zeus and Hera, was cast off Olympus when he was a baby, resulting in him becoming slightly deformed.  Married to the goddess Aphrodite by Zeus to prevent the other gods from starting a war over who would get to marry her.  His symbols are hammers, tongs, and anvils.\033[0m")
        print("")
        if menu_choice2 == "7":
            print("\033[1;34m Hermes\033[0m")
            print("\033[31m God of trade, messengers, thieves, language, sleep, and travel.  Known as one of the cleverest and most mischievous of the gods.  He is known as the herald and messenger for the gods.  Also seen as the protector of cattle and sheep, and the god of dreams. Some of his symbols are winged sandals/helmet, and a caduceus.\033[0m")
        print("")
        if menu_choice2 == "8":
            print("\033[1;34m Dionysus\033[0m")
            print("\033[31m God of winemaking, wine, ritual madness, religious ecstasy, and theatre.  When his mother was blown apart by thunderbolts, Zeus sewed him up in his thigh until he reached maturity.  Many lavish festivals were held by his cult followers, who were known to succumb to the ecstasy of madness.  His symbols include grapes, wine, a panther, leopard, and a thyrsus.\033[0m")
        print("")
        input("\033[33m press enter to continue\033[0m")
        print("")




    elif menu_choice == "2":
        print("")
        print("\033[1;35mGodesses \033[0m")
        print("")
        input("\033[33m press enter to continue\033[0m")
        print("")
        menu_choice3 = input("\033[3;46;47m press 1 to learn about Hera, 2-Hestia, 3-Persephone, 4-Artemis, 5-Demeter,6-Athena, or 7-Aphrodite.\033[0m")
        if menu_choice3 == "1":
            print("\033[1;4;35m Hera\033[0m")
            print("\033[36m Queen of the gods, and goddess of marriage,and birth.  Known to be vengeful and jealous towards the many lovers and offspring that Zeus had.  Her symbols included a cow, peacock, diadem, and sacred lotus.\033[0m")
        print("")
        if menu_choice3 == "2":
            print("\033[1;35m Hestia\033[0m")
            print("\033[36m Godess of the hearth, home, order of domesticity, and family.  Was given the honor of presiding over all sacrifices after she swore to remain a maiden goddess.  Her symbols are hearth, architecture, veils, and keys.\033[0m") 
        print("")
        if menu_choice3 == "3":
            print("\033[1;35m Persephone\033[0m")
            print("\033[36m Godess of vegetation, grain, and flowers.  Daughter of Demeter, goddess of the harvest.  Was taken by Hades to the Underworld, where she had to remain for a third of the year, which resulted in the creation of winter.  Her symbols include pomegranate,torch, flowers, and deer.\033[0m")
        print("")
        if menu_choice3 == "4":
            print("\033[1;35m Artemis\033[0m")
            print("\033[36m Goddess of the hunt, moon, childbirth, and chastity.  She is a virgin goddess, and was very protective and also required her priestesses to also swear off men.  Also seen as the embodiment for athletes and hunting.  Besides killing wild animals, she would also protect them.  She is the twin sister of the god Apollo, god of the sun.  Her symbols are the moon, bow and arrows, and hunting dogs.\033[0m")
        print("")
        if menu_choice3 == "5":
            print("\033[1;35m Demeter\033[0m")
            print("\033[36m Goddess of the harvest, grains, fertility of the earth, sacred law, and the cycle of life and death.  Mother of Persephone, who was taken and married to Hades in the Underworld.  Her symbols include wheat, bread, torch, and a cornucopia.\033[0m")
        print("")
        if menu_choice3 == "6":
            print("\033[1;35m Athena\033[0m")
            print("\033[36m The goddess of wisdom, battle strategies, inspiration, law and justice, strategies, crafts, and courage.  Also know as Athene, she was born out of her father Zeus’ head fully formed.  She later became the patron goddess of Athens, after winning a competition against Poseidon by gifting the city an olive tree.  Her symbols include owls, olive trees, and an aegis.\033[0m")
        print("")
        if menu_choice3 == "7":
            print("\033[1;35m Aphrodite\033[0m")
            print("\033[36m The goddess of love, beauty, and fertility.  She is married to the God Hephaestus, but has frequent affairs with other Olympians, and mortals also.  She is often depicted nude, and is said to represent the perfect female figure.   A magic girdle, a dove, roses, and myrtles are a few of her symbols.\033[0m")
        print("")
        input("\033[33m press enter to continue\033[0m")
        print("") 

    elif menu_choice == "x":
        break



    else:
        print("\033[1;33mI'm sorry, I didn't understand you. Please try again.\033[0m")



    print("\033[1;3;4;31m Goodbye.\033[0m")
