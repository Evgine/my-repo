# my-repo
# Function to check if a number is even or odd
def check_even_odd(number):
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"

# Main program
if __name__ == "__main__":
    # Taking input from user
    num = int(input("Enter a number: "))

    # Calling the function to check even or odd
    result = check_even_odd(num)

    # Displaying the result
    print(f"The number {num} is {result}.")
