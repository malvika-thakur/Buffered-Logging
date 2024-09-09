# Enabling and Configuring Buffer Log
In Buffered Logging messages are stored in a router’s memory buffer (DRAM); when buffer is full older messages are overwritten by new messages. When the router reboots, logging messages are erased.

To show the configurations available for buffered logging the following command will be used:
```
logging buffered ?
```
![image](https://github.com/user-attachments/assets/c5e04a61-cdf7-424a-95af-9696d5a826d6)

To configure the buffer to be 4096 bytes the following command will be used:
```
logging buffered 4096
```
![image](https://github.com/user-attachments/assets/6b34279d-b2e8-4366-bf30-d6066250b6b3)

To verify if the Buffered Logs are configured or not, Let us confirm it by using the following command:
```
sh log
```
This command should display the logs that are being generated as shown in the given below screenshot.
![image](https://github.com/user-attachments/assets/b72491ef-e10e-40ba-9746-0a1341622af3)
![image](https://github.com/user-attachments/assets/27fe147a-c993-4769-956e-7d0c52a9fe7b)

The Buffered Logging have been successfully enabled and configured.
