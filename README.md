# Labsubmission1
Nmeter

           [Test]
            public void GetMultiplication_Input5point0and2point0_Returns10point0()
            {
                //Arrange
                double numb11 = 5.0;
                double numb12 = 2.0;
                double expectedResult = numb11 * numb12;

                Calc Testcalc = new Calc(numb11, numb12);

                //Act
                double actualResult = Testcalc.GetMultiplication();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
            public void GetMultiplication_Input6point0and3point0_Returns12point0()
            {
                //Arrange
                double numb13 = 6.0;
                double numb14 = 3.0;
                double expectedResult = numb13 * numb14;

                Calc Testcalc = new Calc(numb13, numb14);

                //Act
                double actualResult = Testcalc.GetMultiplication();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }
            [Test]
            public void GetMultiplication_Input4point0and1point0_Returns4point0()
            {
                //Arrange
                double numb15 = 4.0;
                double numb16 = 1.0;
                double expectedResult = numb15 * numb16;

                Calc Testcalc = new Calc(numb15, numb16);

                //Act
                double actualResult = Testcalc.GetMultiplication();

                //Assert
                Assert.AreEqual(expectedResult, actualResult);

            }

