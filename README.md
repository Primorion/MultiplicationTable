# MultiplicationTable
Lab Activity 3

```bash

package Funda;
import java.util.*;
public class LabAct3 {

	public static void main(String[] args) {
		
	    Scanner scn = new Scanner(System.in);
	    System.out.print("Enter Number of Rows:");
	    int Row = scn.nextInt();
	    System.out.print("Enter Number of Columns:");
	    int Col = scn.nextInt();
	    
	    for(int x = 1; x<=Row; x++)
	    {
	    for(int y = 1; y<=Col; y++)
	    {
	    System.out.format("%5d", + x*y); 
	    }
	    System.out.println(" ");

	}

 }
}

```
