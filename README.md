# Calculator
A calculator, for calculating. It is in the VB.NET code type.

The code is:
Imports System
				
Public Module Module1
	Public Sub Main()
    Dim num1, num2 as integer 
		Dim q, total as string
    Console.WriteLine("please enter 2 numbers") 
    num1 = console.ReadLine() 
    num2 = console.ReadLine() 
		Console.WriteLine("please enter * to multiply, + to add, / to divide or - to subtract")
		q = Console.ReadLine()
		total = num1 & q & num2
    console.WriteLine("Total is " & total) 
	End Sub
End Module
