You can run this code by doing any of the following:

- /gradlew test (Standard Gradle testing)
- -f SavingsAccountTest.csv (To test the fields that are already present in SavingsAccountTest.csv)
- -f CheckingAccountTest.csv (To test the fields that are already present in CheckingAccountTest.csv)
- -f 100, 10|20, , 10, 80 (Or any other combination) 

You can run the CheckingAccountTextFixture and SavingsAccountTextFixture by running the last command 
in the list or similar values

The values represent (In order) the Initial balance, 
checks, withdrawals, deposits, Montly uses (deposit, withdrawal, etc.) and ending balance

Files that I needed to modify to complete this assignment was CheckingAccountTestFixture.java
CheckingAccountTest.csv, build.gradle, .replit (To fix errors). I had to create SavingsAccountTextFixture.java,
SavingsAccountTest.csv and this readme file

A scenario that this code could not run would be transactions that a person makes such as purchases and another 
scenario that would need new code would be if the user received money from someone through cashapp, venmo or zelle