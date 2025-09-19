** start of main.py **

def cost_to_fill(tank_size, fuel_level, price_per_gallon):

    cost =(tank_size - fuel_level) * price_per_gallon
    co=format(cost, ".2f")
    return '$'+co

** end of main.py **

