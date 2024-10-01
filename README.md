# steamship-displacement# Function to calculate the displacement volume of a ship
def ship_displacement(length, width, draft):
    # Displacement Volume in cubic meters
    displacement_volume = length * width * draft
    return displacement_volume

# Example ship dimensions in meters
length = float(input("Enter the length of the ship (m): "))
width = float(input("Enter the width of the ship (m): "))
draft = float(input("Enter the draft of the ship (m): "))

# Calculate the displacement volume
displacement = ship_displacement(length, width, draft)

# Output the result
print(f"The displacement volume of the ship is {displacement:.2f} cubic meters.")
