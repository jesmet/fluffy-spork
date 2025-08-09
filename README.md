<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/cd7148a1-3f42-4d6c-9caf-a2326ef4f3ae" />

n = int(input("Enter the number of chips: "))


position = list(map(int, input("Enter the positions of chips: ").split()))

even = 0
odd = 0

for pos in position:
    if pos % 2 == 0:
        even += 1
    else:
        odd += 1

min_cost = min(even, odd)
print("Minimum cost to move all chips to the same position:", min_cost)
4
