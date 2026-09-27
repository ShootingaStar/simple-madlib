# simple-madlib
def madlibs():
    print("Welcome to the Funny Story Generator!")
    noun = input("Give me a noun!: ")
    verb = input("Give me a verb ending in -ing!: ")
    adjective = input("Give me an adjective!: ")
    place = input("Give me a place!: ")
    character = input("Give me a Character's Name!: ")
        

    if noun.isdigit or verb.isdigit or adjective.isdigit or place.isdigit or character.isdigit:
        print("Give me what i asked you!")
        return
        
    story = f"Today I went to the {place} with my pal {character} and we saw a {adjective} {noun} that was {verb}!"
    print(story)
madlibs()
