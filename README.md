# lab-6a


using System;
using System.Linq;

class MainClass {
  public static void Main (string[] args) {
 

int farenheit = Convert.ToInt32(Console.ReadLine());

 for (int counter = 0; counter < 7; counter++)
 {
  Console.WriteLine("enter temperature in celsius");

  Console.ReadLine();

 }

 int[] celsius = new int[farenheit];
 
 
 int temCelsius = Convert.ToInt32(Console.ReadLine());
 farenheit = ( temCelsius * 9/5 ) +32; 


for (int counter = 0; counter < 7; counter++)
{
Console.WriteLine("farenheit: " + farenheit); 
}



int avgTemp = Convert.ToInt32(Console.ReadLine());

avgTemp = (farenheit + farenheit + farenheit + farenheit + farenheit + farenheit + farenheit )/ 7;

Console.WriteLine("average temperature is " + avgTemp );

//IM CONFUSEDDDDDDDDDDDDDDDDDDDDDDDDD

// it makes you type to progress in the program so after you enter temperature you have to enter a key then press enter to progress and i am not sure how to fix this also i am unsure how to list each temperature in farenheit by each temperture in celsius

  }
}
