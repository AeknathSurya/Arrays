# Arrays-1
//Basics
class SumAverage
{
public static void main(String args[])
{
int[] numbers = (2,-5,0,8,22,21,7,-3,8);
int sum=0;
Double average;
     for (int number: numbers) {
        sum += number;
     }
     int arrayLength = numbers.length
     average =  ((double)sum / (double)arrayLength);
     System.out.println("Sum = " + sum);
     System.out.println("Average = " + average);
   }
}
