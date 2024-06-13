# pod1
today LeetCode problem solution

class Solution {
    public int minMovesToSeat(int[] seats, int[] students) {
        int count=0;
        Arrays.sort(seats);
        Arrays.sort(students);
        for(int i=0;i< seats.length;i++){
            count+=Math.abs(students[i]-seats[i]);
        }
        return count;
    }
}


// roman number to interger number conversion code
