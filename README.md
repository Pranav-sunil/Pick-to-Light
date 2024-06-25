# Pick-to-Light
Pick to Light is a warehouse management solution system used to automate and streamline the operations. The program allows for efficient management of stock of items in the warehouse. Every storage bin (Client device )is connected to a server board that controls and sends data to and from client and host device( Laptop/ PC of warehouse manager ).  
The program is done in two parts. One part is done for the client device and the other for the host device.  

Target Micro-Controller: PIC 18F4580  
Board: rhydoLABZ PIC 18F4580 CAN Developement Board( https://www.rhydolabz.com/pic18f4580-can-development-board-rhydolabz )  
Compiler: XC8  
Application used to develop program: MPLAB X IDE (v6.20 )  

Communication protocols:  
Client <-> Server : CAN  
Server <-> Host   : U-ART  

Data to identify each client board: Node ID (N_ID)  
Count of item in stock: Updated Stock (U_ST)  

The U_ST and N_ID can be changed in each board.  
