# LeetCode 9 - Palindrome Number
# Author: wilson muriithi

class Solution:
    def isPalindrome(self, x: int) -> bool:
        if x < 0:
            return False
        s = str(x)
        return s == s[::-1]
