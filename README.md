### the sample code for book <<The cucumber for java book>>

* run samples
* cd LearnCucumber
* java -cp "jars/*" cucumber.api.cli.Main -p pretty --snippets camelcase .
* java -cp "jars/*:." cucumber.api.cli.Main -p pretty --snippets camelcase -g step_definitions features
* java -cp "jars/*:." cucumber.api.cli.Main -p progress --snippets camelcase -g step_definitions features

* javac -cp "jars/*:." step_definitions/CheckoutSteps.java implementation/Checkout.java
