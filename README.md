# SwagLabsProject

* In this project I have Automated Swaglabs [SwagLab e-commerce](https://www.saucedemo.com/) web application using Selenium and TestNG
* Tested functionalites like login, adding products to the cart, and placing an order.

* Login Functionality: Automation scripts simulate a user logging in with valid credentials.
* Add Product to Cart: The script selects a product, adds it to the cart, and validates that the cart updates correctly by verifying the product count and details.
* Place Order: The automation flow proceeds to checkout, fills in the necessary shipping and payment details, and confirms the order.

* Selenium is employed for interacting with the web interface, while TestNG is used to manage test execution and reporting.


### Built With
* [Java 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) as programming language
* [Maven](https://maven.apache.org/) for Package Management and Build Automation
* [Selenium](https://www.selenium.dev/) for Web Automation
* [TestNG](https://testng.org/) for Java testing framework that supports annotations, parallel execution, and detailed reporting for efficient test automation.
* [Cucumber](https://cucumber.io/docs/cucumber/) for writing BDD-style tests in Gherkin syntax.

### Prerequisites
  Basic understanding of Java with Maven, Selenium and TestNG  and Cucumber.

### Running the project
Steps are listed below to get this project up and running in your development environment.
* Project can be run as TestNG Suite by - right clicking the project and select "Run As -> TestNG Suite".

* To execute whole project use maven command - mvn clean test or right click on project - Run as - select maven clean and maven test to execute project

* Project can be run as Junit Test Runner by - right clicking the Cucumber Test Runner class and select "Run As -> Test Runer.

* To update maven project right click the project, and select "Maven -> Update Project -> Check the 'Force Update of Snapshots/Releases' -> Ok". This will update the "Maven Dependencies" project.

* Run maven build command if you don't see "Maven Dependencies" folder: mvn clean install
