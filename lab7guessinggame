print("Hello, COMP101 students!")
print("Do you want to play a guessing game with me?")

while True:
    start = input('Enter "1" to play or replay, "0" to stop: ')
    
    if start == "0":
        print("Okay, goodbye!")
        break
    elif start == "1":
        print("\nGreat! Think of a number between 1 and 100 and write it down.")
        print("I will try to guess it. Type:")
        print('   "b" if your number is bigger than my guess,')
        print('   "s" if your number is smaller than my guess,')
        print('   "y" if I guessed it right.\n')

        low = 1
        high = 1000
        rounds = 0

        while low <= high:
            guess = (low + high) // 2
            rounds += 1
            print(f"My guess #{rounds}: {guess}")
            response = input('Is your number (b)igger, (s)maller, or (y)es? ').lower()

            if response == "y":
                print(f"\nYay! I found your number {guess} in {rounds} rounds!\n")
                break
            elif response == "b":
                low = guess + 1
            elif response == "s":
                high = guess - 1
            else:
                print("Invalid input. Please type 'b', 's', or 'y'.")
    else:
        print('Please enter only "1" or "0".')
