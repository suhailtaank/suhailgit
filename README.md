using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using NUnit.Framework;
using AwesomeCalculator;

namespace TestCase1
{

    [TestFixture]
    public class Class1
    {
        [Test]
        public void GetAddition_Input5point2and3point2_Returns8point4()
        {
            double num1 = 5.2;
            double num2 = 3.2;
            double result = num1 + num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetAddition();
            // Act
            Assert.AreEqual(result, actualResult);
        }

        
         [Test]
        public void GetAddition_Input2point2and2point2_Returns4point4()
        {
            double num1 = 2.2;
            double num2 = 2.2;
            double result = num1 + num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetAddition();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetAddition_Input1point2and1point2_Returns2point2()
        {
            double num1 = 1.2;
            double num2 = 1.2;
            double result = num1 + num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetAddition();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetAddition_Input5point5and5point5_Returns11point0()
        {
            double num1 = 5.5;
            double num2 = 5.5;
            double result = num1 + num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetAddition();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetMultiplication_Input9point0and9point0_Returns10point0()
        {
            double num1 = 9.0;
            double num2 = 9.0;
            double result = num1 * num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetMultiplication();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetMultiplication_Input3point0and3point0_Returns9point0()
        {
            double num1 = 3.0;
            double num2 = 3.0;
            double result = num1 * num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetMultiplication();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetMultiplication_Input7point0and7point0_Returns49point0()
        {
            double num1 = 7.0;
            double num2 = 7.0;
            double result = num1 * num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetMultiplication();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetMultiplication_Input11point0and11point0_Returns121point0()
        {
            double num1 = 11.0;
            double num2 = 11.0;
            double result = num1 * num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetMultiplication();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetSubtraction_Input6point0and5point0_Returns1point0()
        {
            double num1 = 6.0;
            double num2 = 5.0;
            double result = num1 - num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetSubtraction();
            // Act
            Assert.AreEqual(result, actualResult);
        }

        [Test]
        public void GetSubtraction_Input6point0and2point0_Returns4point0()
        {
            double num1 = 6.0;
            double num2 = 2.0;
            double result = num1 - num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetSubtraction();
            // Act
            Assert.AreEqual(result, actualResult);
        }

        [Test]
        public void GetSubtraction_Input4point0and1point0_Returns3point0()
        {
            double num1 = 4.0;
            double num2 = 1.0;
            double result = num1 - num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetSubtraction();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetSubtraction_Input9point0and6point0_Returns3point0()
        {
            double num1 = 9.0;
            double num2 = 6.0;
            double result = num1 - num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetSubtraction();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetDivision_Input64point0and8point0_Returns8point0()
        {
            double num1 = 64.0;
            double num2 = 8.0;
            double result = num1 / num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetDivision();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetDivision_Input10point0and2point0_Returns5point0()
        {
            double num1 = 10.0;
            double num2 = 2.0;
            double result = num1 / num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetDivision();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetDivision_Input81point0and9point0_Returns9point0()
        {
            double num1 = 81.0;
            double num2 = 9.0;
            double result = num1 / num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetDivision();
            // Act
            Assert.AreEqual(result, actualResult);
        }
        [Test]
        public void GetDivision_Input15point0and3point0_Returns5point0()
        {
            double num1 = 15.0;
            double num2 = 3.0;
            double result = num1 / num2;
            Calc testCalc = new Calc(num1, num2);
            // Arrange
            double actualResult = testCalc.GetDivision();
            // Act
            Assert.AreEqual(result, actualResult);
        }
    }
}




using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AwesomeCalculator
{
    class Program

    {
        public static int ValidateMenuSelection()
        {
            string userInput = "";
            bool validMenuSelect = false;

            while (validMenuSelect == false)
            {
                Console.WriteLine("1 = Get First Number");
                Console.WriteLine("2 = Change First Number");
                Console.WriteLine("3 = Get Second Number");
                Console.WriteLine("4 = Change Second Number");
                Console.WriteLine("5 = Perform Addition");
                Console.WriteLine("6 = Perform Subtraction");
                Console.WriteLine("7 = Perform Multiplication");
                Console.WriteLine("8 = Perform Division");
                Console.WriteLine("9 = Exit\n");

                Console.WriteLine("Please select an option, by entering a number:\n");
                userInput = Console.ReadLine();

                if (userInput != "1" &&
                    userInput != "2" &&
                    userInput != "3" &&
                    userInput != "4" &&
                    userInput != "5" &&
                    userInput != "6" &&
                    userInput != "7" &&
                    userInput != "8" &&
                    userInput != "9")
                {
                    Console.WriteLine("That's not a valid menu option, please try again:\n");
                }
                else
                {
                    validMenuSelect = true;
                }
            }

            Console.WriteLine();
            return int.Parse(userInput);
        }

        public static double ValidateUserInput(string chosenNumber)
        {
            double aNumber = 1;
            bool isValid = false;

            while (isValid == false)
            {
                Console.WriteLine($"Please enter the {chosenNumber}:");
                string userInput = Console.ReadLine();
                Console.WriteLine();

                bool result = double.TryParse(userInput, out aNumber);

                if (result == false)
                {
                    Console.WriteLine("That's not a valid input please, please try again.\n");
                }

                else
                {
                    isValid = true;
                    Console.WriteLine($"Your {chosenNumber} has been changed to: {aNumber}.\n");
                }
            }

            return aNumber;
        }


        static void Main(string[] args)
        {
            Calc c = new Calc();
            bool validCalcSelect = false;
            string calcSelection;
            int selection;

            while (validCalcSelect == false)
            {
                Console.WriteLine("1 = Use random numbers between 0 and 501 for your calculation\n");
                Console.WriteLine("2 = Provide your own numbers\n");
                Console.WriteLine("Choose a menu item to begin:");
                calcSelection = Console.ReadLine();
                Console.WriteLine();

                if (calcSelection != "1" && calcSelection != "2")
                {
                    Console.WriteLine("That's not a valid selection, please try again.\n");
                }
                else if (int.Parse(calcSelection) == 1)
                {
                    validCalcSelect = true;
                    Random random = new Random();
                    double firstNumber;
                    double secondNumber;

                    firstNumber = Math.Round((random.NextDouble() * 500), 2);
                    secondNumber = Math.Round((random.NextDouble() * 500), 2);

                    Console.WriteLine($"Your random numbers are {firstNumber} and {secondNumber}.\n");
                    Calc customCalc = new Calc(firstNumber, secondNumber);
                    c = customCalc;

                }
                else if (int.Parse(calcSelection) == 2)
                {
                    validCalcSelect = true;

                    double firstNumber;
                    double secondNumber;

                    firstNumber = ValidateUserInput("firstNumber");
                    secondNumber = ValidateUserInput("secondNumber");

                    Console.WriteLine($"Your custom numbers are {firstNumber} and {secondNumber}.\n");
                    Calc customCalc = new Calc(firstNumber, secondNumber);
                    c = customCalc;
                }
            }


            selection = ValidateMenuSelection();

            while (selection != 9)
            {
                double result;

                switch (selection)
                {
                    case 1:
                        Console.WriteLine($"First Number is: {c.GetFirstNumber()}\n");
                        break;
                    case 2:
                        result = ValidateUserInput("firstNumber");
                        c.SetFirstNumber(result);
                        break;
                    case 3:
                        Console.WriteLine($"Second Number is: {c.GetSecondNumber()}\n");
                        break;
                    case 4:
                        result = ValidateUserInput("secondNumber");
                        c.SetSecondNumber(result);
                        break;
                    case 5:
                        Console.WriteLine($"The result of {c.GetFirstNumber()} + {c.GetSecondNumber()} is: {c.GetAddition()}\n");
                        break;
                    case 6:
                        Console.WriteLine($"The result of {c.GetFirstNumber()} - {c.GetSecondNumber()} is: {c.GetSubtraction()}\n");
                        break;
                    case 7:
                        Console.WriteLine($"The result of {c.GetFirstNumber()} * {c.GetSecondNumber()} is: {c.GetMultiplication()}\n");
                        break;
                    case 8:
                        Console.WriteLine($"The result of {c.GetFirstNumber()} / {c.GetSecondNumber()} is: {c.GetDivision()}\n");
                        break;
                    default:
                        break;
                }

                selection = ValidateMenuSelection();

            }

        }
    }
}




