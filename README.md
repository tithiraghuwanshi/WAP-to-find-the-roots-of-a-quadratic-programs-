# WAP-to-find-the-roots-of-a-quadratic-programs-
# program 1 
# python-program-1
import cmath  # cmath is used to handle complex roots

# Input coefficients
a = float(input("Enter the coefficient a: "))
b = float(input("Enter the coefficient b: "))
c = float(input("Enter the coefficient c: "))

if a == 0:
    print("This is not a quadratic equation.")
else:
    # Calculate the discriminant
    d = (b ** 2) - (4 * a * c)

    # Calculate the roots
    root1 = (-b + cmath.sqrt(d)) / (2 * a)
    root2 = (-b - cmath.sqrt(d)) / (2 * a)

    # Display the roots
    print(f"The roots of the quadratic equation are: {root1} and {root2}")
