# Labsubmission1
Nmeter
        
         [Test]
            public void GetDivision_Input5point0and2point0_Returns2point5()
            {
                //Arrange
                double numb17 = 5.0;
                double numb18 = 2.0;
                double expectedResult = numb17 / numb18;

                Calc Testcalc = new Calc(numb17, numb18);

                //Act
                double actualResult = Testcalc.GetDivision();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            public void GetDivision_Input6point0and3point0_Returns2point0()
            {
                //Arrange
                double numb19 = 6.0;
                double numb20 = 3.0;
                double expectedResult = numb19 / numb20;

                Calc Testcalc = new Calc(numb19, numb20);

                //Act
                double actualResult = Testcalc.GetDivision();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
            public void GetDivision_Input8point0and4point0_Returns2point0()
            {
                //Arrange
                double numb20 = 8.0;
                double numb21 = 4.0;
                double expectedResult = numb20 / numb21;

                Calc Testcalc = new Calc(numb20, numb21);

                //Act
                double actualResult = Testcalc.GetDivision();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
            public void GetDivision_Input10point0and5point0_Returns2point0()
            {
                //Arrange
                double numb22 = 10.0;
                double numb23 = 5.0;
                double expectedResult = numb22 / numb23;

                Calc Testcalc = new Calc(numb22, numb23);

                //Act
                double actualResult = Testcalc.GetDivision();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
