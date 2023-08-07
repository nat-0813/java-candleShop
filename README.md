# java-candleShop
Candle shop project in Java involves creating a program to manage inventory, sales, and customer information.

How the code functions:
This program generates a receipt for purchasing different candles. It creates Candle objects to represent each candle type and purchase. The receipt totals up the quantity, burn time, price, and dollar per burn time for each candle. It also calculates and prints overall totals for the full receipt.

The Candle class encapsulates the details for each candle - name, quantity, burn time, price. It calculates dollar per burn time as price / burn time.

The Main class creates Candle instances and handles printing the formatted receipt with totals.

How to run:
This program is written in Java. To run it:

Ensure you have the Java JDK installed
Compile the Java files: javac Main.java Candle.java
Run the Main class: java Main


Expected Outputs:
Running the program will print a formatted candle receipt with these details:

Candle name
Quantity purchased
Burn time
Dollar per burn time
Price
It prints this for each candle. Then at the end it prints:

Total burn time
Total dollar per burn time
Total price
This provides a detailed breakdown of the candle purchase.
