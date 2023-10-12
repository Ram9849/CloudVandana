# CloudVedana
Assignment details

JAVA PROGRAMS
1. Create an array with the values (1, 2, 3, 4, 5, 6, 7) and shuffle it.
   #CODE

import java.util.Arrays;
import java.util.Random;
public class Shuffle_Array 
{
    public static void main(String[] args) 
    {
        int[] array = {1, 2, 3, 4, 5, 6, 7};
        shuffle_Array(array);
        System.out.println(Arrays.toString(array));
    }

    public static void shuffle_Array(int[] array) 
    {
        Random rand = new Random();
        for (int k = array.length - 1; k > 0; k--) 
        {
            int n = rand.nextInt(k + 1);
            swap(array, k, n);
        }
    }

    public static void swap(int[] array, int k, int n) 
    {
        int temp = array[k];
        array[k] = array[n];
        array[n] = temp;
    }
}

Output:
[1, 3, 4, 7, 5, 6, 2]

3. Enter a Roman Number as input and convert it to an integer. (Example: IX = 9)
4. Check if the input is pangram or not. (A pangram is a sentence that contains all the
alphabets from A to Z)
JavaScript
1. Take a sentence as an input and reverse every word in that sentence.
Example - This is a sunny day > shiT si a ynnus yad.
2. Perform sorting of an array in descending order.

