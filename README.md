# Chapter 16: Databases


This folder contains various examples covered in Chapter 16 of Starting Out with Java by Tony Gaddis and instructions for compilation and demonstration. To install 
the relevant packages, do 
```
sudo apt-get install derby-tools openjfx
```


7e files
CreateCoffeeDB.java
```
javac -cp .:/usr/share/java/derby.jar CreateCoffeeDB.java
java -cp .:/usr/share/java/derby.jar CreateCoffeeDB
```
16-1 TestConnection.java
```
javac -cp .:/usr/share/java/derby.jar TestConnection.java
java -cp .:/usr/share/java/derby.jar TestConnection
```
16-2 ShowCoffeeDescriptions.java
```
javac -cp .:/usr/share/java/derby.jar ShowCoffeeDescriptions.java
java -cp .:/usr/share/java/derby.jar ShowCoffeeDescriptions
```
16-3 ShowDescriptionsAndPrices.java
```
javac -cp .:/usr/share/java/derby.jar ShowDescriptionsAndPrices.java
java -cp .:/usr/share/java/derby.jar ShowDescriptionsAndPrices
```
16-4 ShowCoffeeData.java
```
javac -cp .:/usr/share/java/derby.jar ShowCoffeeData.java
java -cp .:/usr/share/java/derby.jar ShowCoffeeData
```
16-5 CoffeeMinPrice.java
```
javac -cp .:/usr/share/java/derby.jar CoffeeMinPrice.java
java -cp .:/usr/share/java/derby.jar CoffeeMinPrice
```
16-6 CoffeeMath.java
```
javac -cp .:/usr/share/java/derby.jar CoffeeMath.java
java -cp .:/usr/share/java/derby.jar CoffeeMath
```
16-7 CoffeeInserter.java
```
javac -cp .:/usr/share/java/derby.jar CoffeeInserter.java
java -cp .:/usr/share/java/derby.jar CoffeeInserter
```

16-8 CoffeePriceUpdater.java
```
javac -cp .:/usr/share/java/derby.jar CoffeePriceUpdater.java
java -cp .:/usr/share/java/derby.jar CoffeePriceUpdater
```
16-9 CoffeeDeleter.java
```
javac -cp .:/usr/share/java/derby.jar CoffeeDeleter.java
java -cp .:/usr/share/java/derby.jar CoffeeDeleter
```
16-10 CreateCustomerTable.java
```
javac -cp .:/usr/share/java/derby.jar CreateCustomerTable.java
java -cp .:/usr/share/java/derby.jar CreateCustomerTable
```
16-11 BuildEntertainmentDB.java
```
javac -cp .:/usr/share/java/derby.jar BuildEntertainmentDB.java
java -cp .:/usr/share/java/derby.jar BuildEntertainmentDB.java
```
16-12 MetaDataDemo.java
```
javac -cp .:/usr/share/java/derby.jar MetaDataDemo.java
java -cp .:/usr/share/java/derby.jar MetaDataDemo.java
```
16-13 DBViewer.java
```
javac --module-path $PATH_TO_FX --add-modules javafx.controls,javafx.fxml YourJavaFile.java

javac --module-path /usr/share/openjfx/lib --add-modules javafx.controls,javafx.fxml -cp .:/usr/share/java/derby.jar DBViewer.java
java --module-path /usr/share/openjfx/lib --add-modules javafx.controls,javafx.fxml -cp .:/usr/share/java/derby.jar DBViewer
```

16-14 CoffeeDBManager.java
16-15 OrderEntrySystem.java

The unpaid order table has to be set up first.
```
javac -cp .:/usr/share/java/derby.jar CreateUnpaidOrderTable.java
java -cp .:/usr/share/java/derby.jar CreateUnpaidOrderTable
```

This application uses one class to manage the database, and another to display the GUI.
```
javac --module-path .:/usr/share/openjfx/lib --add-modules javafx.controls,javafx.fxml -cp .:/usr/share/java/derby.jar CoffeeDBManager.java
javac --module-path .:/usr/share/openjfx/lib --add-modules javafx.controls,javafx.fxml -cp .:/usr/share/java/derby.jar OrderEntrySystem.java
java --module-path .:/usr/share/openjfx/lib --add-modules javafx.controls,javafx.fxml -cp .:/usr/share/java/derby.jar OrderEntrySystem
```



