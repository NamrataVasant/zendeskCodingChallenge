# Zendesk Ticket viewer

This is a Java maven project created for zendesk intern coding challenge which has an implementation of Zendesk CLI Ticket Viewer.

### Installation and usage steps on IDE:
1. Install java JDK 17 on your machine

2. Install maven on your machine

3. Open the project on any popular java IDE for etc intellij idea or eclipse.

4. Run the code in TickerViewer. The program is run on the terminal.

5. Follow along the terminal inputs and outputs.

6. To run the test cases run the code in TicketServiceTest class.


### Run the program on terminal instead of IDE:
1. cd to the project root folder in command line.

2. mvn compile

3. mvn exec:java -Dexec.mainClass="com.zendesk.ticket.viewer.TicketViewer"

Note: Maven and Java JDK 17 must be installed and reachable from cmdline.

Note: Set the JAVA_HOME environment variable appropriately.


## Configuration needed:
Please edit the connectionInfo.properties file to enter the correct email, password and subdomain fields before executing the program.

Thank you!
