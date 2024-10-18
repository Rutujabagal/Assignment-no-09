To find Decay Coefficient at 25°C

K1 = float(input(“Enter Decay Coefficient at 3rd day: “))

T = float(input(“Enter Temperature at 3rd day: “))

T1 = float(input(“Enter Temperature at 7th day: “))

# Calculate new Decay Coefficient (K2) using temperature correction formula

K2 = K1 * (1.047 ** (T1 – T))

Print(“The value of is:”, K2)

# To find Ultimate BOD

B1 = float(input(“Enter BOD at 3rd day (20°C): “))

T = float(input(“Enter time in days for finding BOD: “))

# Euler’s number

E = math.e

# Calculate BOD using the equation

E = (1 – e ** (-0.23 * t))

Print(“The value of E is:”, E)

# Calculate Ultimate BOD

BOD_ultimate = B1 / E

Print(“The value of Ultimate BOD is:”, BOD_ultimate)

# To find BOD at 7th day at 25°C

T1 = float(input(“Enter time in days for finding BOD at 7th day: “))

# Calculate BOD at 7th day (25°C)

E1 = (1 – e ** (-0.289 * t1))

Print(“The value of E1 is:”, E1)

B2 = BOD_ultimate * E1
