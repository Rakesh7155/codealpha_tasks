# codealpha_tasks
python programming
def fibonacci(n):
    fib_sequence = [0, 1]
    while len(fib_sequence) < n:
        fib_sequence.append(fib_sequence[-1] + fib_sequence[-2])
    return fib_sequence

n = 10  # generate first 10 Fibonacci numbers
print(fibonacci(n))
