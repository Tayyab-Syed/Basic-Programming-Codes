# Basic Programming Codes

## Just to help young learners & explorers 🙌

If you need any help in the code, Feel free to ask me.
>Connect: [Tayyab Syed](https://linktr.ee/tayyabsyed)


# # x = 6
# # while x >= 1:
# #     if x % 2 != 0:
# #         print("odd", end=' ')
# #     else:
# #         print("even", end=' ')
# #     x -= 1
    
# # y = 7 + 2**3 + (4%5)
# # print("\n", y)

# a = "xyz"
# def func():
#     a = "abc"
#     return a

# print("Local", func())
# print("Global", a)

# x, y, z =eval(input("Enter 3 no: "))
# print("(x < y and y < z) is", x < y and y < z)
# print("(x < y or y < z) is", x < y or y < z)
# print("not (x < y) is", not (x < y))

# a = float(input("Enter : "))
# b = float(input("Enter : "))
# c = a + b
# print("Float Output: ", c)

# def avg(a, b, c):
#     return (a + b + c) / 3

# x = int(input("Enter 1st no: "))
# y = int(input("Enter 2nd no: "))
# z = int(input("Enter 3rd no: "))

# print("Average is:", avg(x, y, z))

# user_input = ""
# avg_list = []
# while user_input != "0":
#     user_input = input("Enter number to add to average (0 to exit): ")
#     avg_list.append(user_input)
#     avg_list.__len__()
#     total = 0
#     for i in avg_list:
#         total += int(i)
#     print("Average is:", total / (avg_list.__len__() - 1))

# Program to compute the average of values entered by the user
# Sentinel value: 0 (to stop input)

# total = 0      # sum of all values
# count = 0      # number of values entered

# while True:
#     value = int(input("Enter a value (0 to stop): "))
#     if value == 0:   # sentinel check
#         break
#     total += value
#     count += 1

# if count > 0:
#     average = total / count
#     print("Average of entered values:", average)
# else:
#     print("No values were entered.")

# def table(number, start, end):
#     """Function to print multiplication table of 'number'
#        from 'start' to 'end'."""
#     for i in range(start, end + 1):
#         print(f"{number} x {i} = {number * i}")

# # Call the function
# table(7, 2, 4)

# --- Main Program ---
# Get inputs from user
# num_input = input("Enter a number (press Enter for default 7): ")
# start_input = input("Enter starting value (press Enter for default 5): ")
# end_input = input("Enter ending value (press Enter for default 15): ")

# Apply defaults if user leaves blank
# if num_input.strip() == "":
#     number = 7
# else:
#     number = int(num_input)

# if start_input.strip() == "":
#     start = 5
# else:
#     start = int(start_input)

# if end_input.strip() == "":
#     end = 15
# else:
#     end = int(end_input)

# letters = ["a", "b", "c", "d"]
# # del letters[1]       
# del letters[1:4]     
# print(letters) 

# def main():
#     print(8, "Hello", 9)
#     message = ("Uneeb")
#     n = 5
#     for i in range(n):
#         print(message)

# main()

# while i in range(1, 6):
#     while j in range(1, 3):
#         print(i^j, end=' ')

# for i in range (1,4):
#     for j in range (1,4):
#         if i*j > 2:
#             break
#         print(i*j, end=' ')
#     print(i)

# a = [n for n in range(10, 30) if (n % 5 == 0 or n % 7 == 0)]
# print(a)

# user_input = ""
# total = 0
# while True:
#     user_input = input("Enter a number: ")
#     if user_input != "y":
#         total += int(user_input)
#     print("Total is:", total)

# def get_color(wavelength):
#     """Return the color of visible light for a given wavelength."""
#     if 380 <= wavelength < 450:
#         return "Violet"
#     elif 450 <= wavelength < 495:
#         return "Blue"
#     elif 495 <= wavelength < 570:
#         return "Green"
#     elif 570 <= wavelength < 590:
#         return "Yellow"
#     elif 590 <= wavelength < 620:
#         return "Orange"
#     elif 620 <= wavelength <= 750:
#         return "Red"
#     else:
#         return "Error: Wavelength outside visible spectrum (380–750 nm)."

# # --- Main Program ---
# try:
#     wl = int(input("Enter wavelength in nm: "))
#     print(get_color(wl))
# except ValueError:
#     print("Error: Please enter a valid integer wavelength.")

user_input = input("Enter a number: ")
list1 = [int(x) for x in user_input.split()]
