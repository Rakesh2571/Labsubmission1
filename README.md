# Labsubmission1
Nmeter

            [Test]
            public void GetSubstraction_Input3point5and2point4_Returns1point1()
            {
                //Arrange
                double numb7 = 3.5;
                double numb8 = 2.4;
                double expectedResult = numb7 - numb8;

                Calc Testcalc = new Calc(numb7, numb8);

                //Act
                double actualResult = Testcalc.GetSubtraction();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
            public void GetSubstraction_Input4point5and1point4_Returns3point1()
            {
                //Arrange
                double numb9 = 4.5;
                double numb10 = 1.4;
                double expectedResult = numb9 - numb10;

                Calc Testcalc = new Calc(numb9, numb10);

                //Act
                double actualResult = Testcalc.GetSubtraction();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);


            }
            [Test]
            public void GetSubstraction_Input5point5and3point4_Return2point1()
            {
                //Arrange
                double numb9 = 5.5;
                double numb10 = 3.4;
                double expectedResult = numb9 - numb10;

                Calc Testcalc = new Calc(numb9, numb10);

                //Act
                double actualResult = Testcalc.GetSubtraction();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
