#PYTHON
import math
nums = list(map(float,input("Enter numbers separated by space :").split()))
maximum = max(nums)
minimum = min(nums)
Total_sum = sum(nums)
Average = Total_sum / len(nums)

sqrt_values = [math.sqrt(num) for num in nums if num>=0]

round_values = [round(num) for num in nums]

print("\n results :")
print("numbers: ",nums)
print("maxmum:",maximum)
print("minimum: ",minimum)
print("sum: ",Total_sum)
print("Average: ",Average)
print("Square root: ",sqrt_values)
print("Round values: ",round_values)
