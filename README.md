# Labsubmission1
Nmeter
            [Test]
            public void GetAddition_Input1point5and2point5_Returns4point0()
            {
                //Arrange
                double numb1 = 1.5;
                double numb2 = 2.5;
                double expectedResult = numb1 + numb2;

                Calc Testcalc = new Calc(numb1, numb2);

                //Act
                double actualResult = Testcalc.GetAddition();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);
            }
            [Test]
            public void GetAddition_Input2point5and2point5_Returns5point0()
            {
                //Arrange
                double numb3 = 2.5;
                double numb4 = 2.5;
                double expectedResult = numb3 + numb4;

                Calc Testcalc1 = new Calc(numb3, numb4);

                //Act
                double actualResult = Testcalc1.GetAddition();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
            public void GetAddition_Input3point5and3point5_Returns7point0()
            {
                //Arrange
                double numb5 = 3.5;
                double numb6 = 3.5;
                double expectedResult = numb5 + numb6;

                Calc Testcalc = new Calc(numb5, numb6);

                //Act
                double actualResult = Testcalc.GetAddition();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
