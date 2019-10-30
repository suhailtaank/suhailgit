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








