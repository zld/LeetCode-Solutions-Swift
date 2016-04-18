class Solution {
    func addDigits(num: Int) -> Int {
    	if num < 1 {
    		return 0
    	}
    	return (num - 1) % 9 + 1
    }
}