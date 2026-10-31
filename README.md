# Concatenation-of-Array
class Solution:
    def getConcatenation(self, nums: list[int]) -> list[int]:
        if nums is None:
            return nums
        n=len(nums)
        ans=[]
        for i in range(n):
            ans.append(nums[i])
        for i in range(n):
            ans.append(nums[i])
        return ans
