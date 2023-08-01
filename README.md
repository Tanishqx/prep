# To check if an integer is palindrome or not (python3)
**Follow this code**
class Solution:
    def isPalindrome(self, x: int) -> bool:
        x = str(x)
        if (x == x[::-1]):
            return True
        return False        
        
