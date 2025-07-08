public class SmallExample {
    public static void main(String[] args) {
        int[] nums = {1,1,2};
        Solution s = new Solution();
        int k = s.removeDuplicates(nums);
        System.out.println(k);
    }
}

class Solution {
    public int removeDuplicates(int[] nums) {
        int k = 0;
        for (int num : nums) {
            if (k == 0 || nums[k - 1] != num) {
                nums[k++] = num;
            }
        }
        return k;
    }
}
