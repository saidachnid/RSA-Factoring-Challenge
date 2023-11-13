#!/usr/bin/python3
def factorize_rsa_number(n):
    # Function to factorize an RSA number
    factors = []
    divisor = 2

    while n > 1:
        while n % divisor == 0:
            factors.append(divisor)
            n //= divisor
        divisor += 1

    return factors

def format_output(n, factors):
    # Function to format the output
    factors_str = '*'.join(map(str, factors))
    return f"{n}={factors_str}"

if __name__ == "__main__":
    # Example usage
    rsa_numbers = [6, 77, 239821585064027, 2497885147362973]

    for n in rsa_numbers:
        factors = factorize_rsa_number(n)
        output = format_output(n, factors)
        print(output)

