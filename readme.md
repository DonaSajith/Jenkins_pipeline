class Solution(object):
    def twoSum(self, nums, target):
        for i in range(len(nums)):
            for j in range(i+1, len(nums)):
                if nums[i] + nums[j] == target:
                    return [i,j]

numbers = input("Enter a list of numbers: ")
nums = [int(x) for x in numbers.split(",")]
target = int(input("Enter the target: "))

print(sol.twoSum(nums, target))
