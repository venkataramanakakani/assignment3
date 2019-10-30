using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using AwesomeCalculator1;
using NUnit.Framework;


namespace CalculatorTest1

{
    [TestFixture]
    class CalcTests
    {
        [Test]
        public void GetAddition_Input1point4and6point6_Returns8point0()
        {

            //Arrange
            double number1 = 1.4;
            double number2 = 6.6;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetAddition_Input6point4and7point4_Returns13point8()
        {

            //Arrange
            double number1 = 6.4;
            double number2 = 7.1;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetAddition_Input12point0and1point0_Returns13point0()
        {

            //Arrange
            double number1 = 12.0;
            double number2 = 1.0;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input18point0and13point4_Returns4point6()
        {

            //Arrange
            double number1 = 18.0;
            double number2 = 13.4;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input2point6and1point1_Returns1point5()
        {

            //Arrange
            double number1 = 2.6;
            double number2 = 1.1;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input9point0and1point0_Returns8point0()
        {

            //Arrange
            double number1 = 9.0;
            double number2 = 1.0;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input10point0and1point0_Returns10point0()
        {

            //Arrange
            double number1 = 10.0;
            double number2 = 1.0;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input22point0and22point0_Returns484point0()
        {

            //Arrange
            double number1 = 22.0;
            double number2 = 22.0;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input10point10and2point10_Returns21point21()
        {

            //Arrange
            double number1 = 10.10;
            double number2 = 2.10;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input2point3and1point0_Returns2point3()
        {

            //Arrange
            double number1 = 2.3;
            double number2 = 1.0;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input3point0and1point0_Returns3point0()
        {

            //Arrange
            double number1 = 3.0;
            double number2 = 1.0;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input5point0and1point0_Returns5point0()
        {

            //Arrange
            double number1 = 5.0;
            double number2 = 1.0;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
    }
}
