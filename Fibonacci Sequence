def fibonacci_sequence(n):
    # Input validation
    if not isinstance(n, int) or n <= 0:
        return "Input must be a positive integer."
    
    sequence = [0, 1]
    
    while len(sequence) < n:
        next_value = sequence[-1] + sequence[-2]
        sequence.append(next_value)
    
    return sequence

# Example usage
n = 11  # The length of the Fibonacci sequence
result = fibonacci_sequence(n)
print(result)
