# Program-2.py
def print_fancy(text):
    fancy_text = ""
    for char in text:
        fancy_text += char.upper() + " "
    print(fancy_text)

def main():
    name = input("Enter your name: ")
    dream_job = input("Enter your dream job: ")

    print("\nYour Name:")
    print_fancy(name)

    print("\nYour Dream Job:")
    print_fancy(dream_job)

if __name__ == "__main__":
    main()
