# TIC-TAC-TOE
Implementation of Tic Tac Toe game using Socket Programming in JAVA

### How to run

>To run the game on one computer get the IP address of your computer.
#### For the server
1. Import the Server/Chat_app in IntelliJ.
2. Run the main funtion in VerySimpleChatServer.java
3. The server should be up and running if no error message is shown
> While using the socket make sure you connect to a network without proxy. Ensure proxy settings from terminal has been unset.

#### For the client app
1. Import the project in the src folder in IntelliJ
2. Run the main funtion in Main.java
3. Go to edit configuration page and Allow parallel run
4. Run the main funtion again to open new instance
5. The game could be played using the two GUI interfaces.
>Update to line in Main.java in client app to look like this
>> Socket gameSocket = new Socket("YOUR_IP_HERE", 6000);

> To run the game on two different laptops get the IP address of your network.
#### For the server
1. Import the Server/Chat_app in IntelliJ.
2. Run the main funtion in VerySimpleChatServer.java
3. The server should be up and running if no error message is shown
> While using the socket make sure you connect to a network without proxy. Ensure proxy settings from terminal has been unset.

#### For the client app
1. Import the project in the src folder in IntelliJ in both the computer.
2. Run the main funtion in Main.java
>Update to line in Main.java in client app to look like this
>> Socket gameSocket = new Socket("YOUR_IP_HERE", 6000);


