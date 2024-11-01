# Tutorial Python

## Arithmetic and Variables

Print a message -> print("Hello, world!")

You can control the order of operations in long calculations with parentheses: print(((1 + 3) * (9 - 2) / 2) ** 2) -> 196.0  
In general, Python follows the PEMDAS rule (https://www.mathsisfun.com/operation-order-pemdas.html) when deciding the order of operations.

Create a Comment with # -> # Multiply 3 by 2

Create variable -> test_var = 4 + 5
Print variable -> print(test_var)

## Functions

![image](https://github.com/user-attachments/assets/e1fdcf6c-1963-466d-bb56-312037f255bd)

Header: def + name + Argument (input_var)
Body: output_var = input_var + 3 + return statement (return output_var)

### Run or "call" function  
new_number = add_three(10)

## Data Types

Integer = x = 14
Floats = nearly_pi = 3.141592653589793238462643383279502884197169399375105820974944
Booleans = z_one = True / z_five = not z_four
Strings = w = "Hello, Python!"

Print String length: print(len(w))

Convert float to int = y = 1.0 | z = int(y)

When you add booleans, adding False is equivalent to adding 0, and adding True is equivalent to adding 1.

## Conditions and Conditional Statements

![image](https://github.com/user-attachments/assets/b5129c3e-d553-4cb5-8d8e-9c42d3ed38df)

![image](https://github.com/user-attachments/assets/f78e1d15-03e5-42cc-8186-f68de1ce9893)

## Lists

flowers_list = ["pink primrose", "hard-leaved pocket orchid", "canterbury bells", "sweet pea", "english marigold", "tiger lily", "moon orchid", "bird of paradise", "monkshood", "globe thistle"]

print(type(flowers_list))
print(flowers_list)

print(len(flowers_list))

print("First entry:", flowers_list[0])  
print("Second entry:", flowers_list[1])

print("First three entries:", flowers_list[:3])  
print("Final two entries:", flowers_list[-2:])    
First three entries: ['pink primrose', 'hard-leaved pocket orchid', 'canterbury bells']  
Final two entries: ['monkshood', 'globe thistle']

flowers_list.remove("globe thistle")

flowers_list.append("snapdragon")

hardcover_sales = [139, 128, 172, 139, 191, 168, 170]  
print("Length of the list:", len(hardcover_sales))  
print("Entry at index 2:", hardcover_sales[2])  
print("Minimum:", min(hardcover_sales))  
print("Maximum:", max(hardcover_sales))

print("Total books sold in one week:", sum(hardcover_sales))

print("Average books sold in first five days:", sum(hardcover_sales[:5])/5)

Transform into List: print(flowers.split(","))
