# **TAXIMETER**

# Information

* **It prints the taximeter amount on the screen according to the distance traveled (KM).**

# Technologies Used

* **JAVA**

# Contents

* The variable **km** is defined with int.

* The variable double **perKM** is defined because it is a decimal number.

* The starting price was set and defined as 10 TL.

* Scanner scan class defined.

* If the distance traveled is less than 20 TL, the taximeter is set to 20 TL.

<br />

# Codes

```Java

        public class Taximeter {

                public static void main(String[] args) {

                int km;

                double perKm = 2.20, total, startPrice = 10;

```

```Java

                Scanner input = new Scanner(System.in);

                System.out.print("Enter Distance in KM : ");

                km = input.nextInt();

                total = (km * perKm);

                total += startPrice;

                total = (total < 20) ? 20 : total;

                System.out.println("Total Amount :" + total);


```

```bash

        Enter Distance in KM : 10
        Total Amount :32.0

```

```bash

        Enter Distance in KM : 2
        Total Amount :20.0

```
<br />

# LINK

* Click here https://github.com/Fogo9/Taximeter.git to access the Github page for this project.

<br />

# LICENSE

* This software is licensed By Tuncay Demir under the MIT license.

<br />

>[Patika.dev](https://app.patika.dev/fogomurphy)

<br/>

| Name |  Email |
| ---- |  ----- |
| Tuncay | tuncaydemir682@gmail.com |
