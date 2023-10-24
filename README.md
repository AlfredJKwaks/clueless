# clueless

def main():

    needed_words = ["adjective", "noun", "name", "name", "adjective", "verb"]
    story = "Once upon a time, there was a XXX house next to the sea.\nThere was a huge XXX in the front yard of the house.\nXXX and XXX happened to walk past the house.\nThey felt XXX after seeing it and that's why they decided to XXX."

    print("Welcome to the story generator.")
    own_story = input("Do you want to use your own story? yes/no:\n")
    if own_story == "yes":
        print("Give your story on one line. It should have 6 XXX marks in the middle.")
        story = input("The XXX's should correspond to: 1) Adjective 2) Noun 3) Name 4) Name 5) Adjective 6) Verb\n")
    user_inputs = []
    print("Give the asked words:")
    for word in needed_words:
        user_word = input(f"Give one {word}:\n")
        user_inputs.append(user_word)

    # write your own code here

main()
