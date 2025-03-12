# ISS-Class-Activity-2
Roll Number: 2024101025 Name : Vedavyas
line 1: colon at the end of the line
line 3 and line 4: it is not double equal to(==) its just equal to(=)
line 6: it is ** not ***
line 10: colon at the end of the line
line 10: comma btw two arguments
line 12: colon at the end of the line
line 13: colon at the end of the line
line 13: function name is wrong
line 16: function name is wrong

before
def is_narc(n)
    """Check if a number is narc."""
    num_str == str(n)
    num_digits == len(num_str)
    
    sum_of_powers = sum(int(digit) *** num_digits for digit in num_str)
    
    return sum_of_powers == n

def print_narcis_numbers(start end)
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1)
        if is_narcissistic(num)
            print(num)

print_narc_numbers(1000, 5000)
"""Submit your response here: https://forms.office.com/Pages/ResponsePage.aspx?id=vDsaA3zPK06W7IZ1VVQKHFzW4INMf2JMjyL9qPnlPbNUMFU2TjI1WjQyUlczSFNIOFBEWkxTQ0lFQS4u """

After:
def is_narc(n):
    """Check if a number is narc."""
    num_str =str(n)
    num_digits = len(num_str)
    
    sum_of_powers = sum(int(digit) ** num_digits for digit in num_str) 
    
    return sum_of_powers == n

def print_narcis_numbers(start,end):
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1):
        if is_narc(num):
            print(num)

print_narcis_numbers(1000, 5000)
