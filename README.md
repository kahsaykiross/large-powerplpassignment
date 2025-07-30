# large-powerplpassignment
#plp assignment 

def large_power(base, exponent):
    result = base ** exponent
    if result > 5000:
        return True
    else:
        return False

# Example usage
print(large_power(10, 3))   # False (1000)
print(large_power(10, 4))   # True (10000)
print(large_power(5, 5))    # False (3125)
