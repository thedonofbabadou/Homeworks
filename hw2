print("NET salary calculator")
name= input("How should I call you? ")

try:
    gross_salary = float(input("What is your gross salary? "))
    gross_salary = float(int(gross_salary))
    children = int(input("How many children do you have? "))
    income_tax = None
    if gross_salary < 1000:
       income_tax = 10
    elif gross_salary < 2000:
        income_tax= \
            12
    elif gross_salary < 4000:
        income_tax = 14
    elif gross_salary > 4000:
        income_tax = 18
    if gross_salary < 2000:
        tax_cut = 1*children
    elif gross_salary > 2000:
        tax_cut = 0.5*children
    total_tax_rate = income_tax - tax_cut # Calculate total tax after cut
    net_salary = gross_salary*(1-total_tax_rate/100)

    print(f"{name}, your net salary is {net_salary}")
except ValueError:
    print("Please enter valid numbers!")