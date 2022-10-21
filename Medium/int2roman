class Solution:
    
    def intToRoman(self, num: int) -> str:
        thou = {0:'', 1:'M', 2: 'MM', 3:'MMM'}
        cent = {0:'', 1:'C', 2: 'CC', 3:'CCC', 4:'CD', 5:'D', 6:'DC', 7:'DCC', 8:'DCCC', 9:'CM'}
        dec = {0:'', 1:'X', 2:'XX', 3:'XXX', 4:'XL', 5:'L', 6:'LX', 7:'LXX', 8:'LXXX', 9:'XC'}
        unit = {0:'', 1:'I', 2:'II',3: 'III', 4:'IV', 5:'V', 6:'VI',  7:'VII', 8:'VIII', 9:'IX'}

        thou_add = thou.get(num // 1000)
        cent_add = cent.get((num % 1000)//100)
        dec_add = dec.get((num % 100)//10)
        unit_add = unit.get((num % 10))
        
        return thou_add + cent_add + dec_add + unit_add
