# Complex Embedded System : Smart Card 

Smart card is one of the most used embedded 
system today.it is plastic card with a built-in microprocessor, used typically to perform financial transactions.It is used for credit, debit bank card, 
e-wallet card, identification card, medical card (for 
history and diagnosis details).

* it is used for Number of new innovative application.
* Enabling authentication and verification of card and card holder by a host.
* Enabling GUI at host machine to interact with the card holder/user for the required transactions, for example, financial transactions with a bank or credit card transactions.
* smart cards are used to make fast and safe transactions 

# Hardware and software Architecture :

![New Doc 02-17-2022 23 39 59_1](https://user-images.githubusercontent.com/98826329/154547257-c8ea4768-7cad-47f8-908a-e5c2c7217da3.jpg)

## Functions of the system
* The card inserts at a host machine.
* The radiations from the host a charge pump at the card.
* The charge pump powers the SoC circuit consisting of card processor ,memory,timer,interrupt handler and IO port,Port-IO.
* On power up,system reset signals reset-Task to start
* * reset-Task :it sends the messages request Header and request start for waiting task Task_Report.
* * task_ReadPort: it sends request for host identification and reads through the port_IO the host-identification message and request for card identification
* task_PW : it sends through Port_IO the requested card indentification after system receives the host indentity through Port_IO.
* task_Appl :onces person enter correct password it will go to task_Appl and runs required API.
* The card can now be withdrawn All transactions between cardholder/user now take place through GUIs using at host control pannel (scrren or touch screen or LCD display panel).
* Onces the application is over,we can take back the card from the machine.

# Smart Card Hardware
* A plastic card in ISO standard dimensions, 85.60 mm x 53.98 x 0.80 mm.
* It is an embedded SoC (System-On-Chip). 
* now smart cards are avaiable in 2 version
* [ISO standards - ISO7816 (1 to 4) for host-machine contact based card and ISO14443 (Part A or B) for the contact-less cards.]
* Microcontroller MC68HC11D0 or PIC16C84 or a smart card processor Philips Smart XA or an ASIP Processor. Needs 8 kB+ internal RAM and 32 kB EPROM and 2/3 wire protected memory.
* CPU special features, for example, a security lock 
* standard ROM 8 kB for usual or 64 kB when using advanced cryptographic features
*  Full or part of ROM bus activates take place after a security check only.
*  chip-supply system using charge pump.
EEPROM or Flash scalable – only needed part unlocks when storing P.I.N., unlocking P.I.N., access condition, card-user data, post activation application run generated non-volatile data, invalidation lock to invalidate card after the expiry date or server instruction.

# Applications of Smart Card
* Banking
*  Medical Health Cards
*  satellite TV
*  Access Control systems
*  Electronic cash
*  Wireless(mobile) communications
*  Government identification
*  Telecommunications
*  Ticket travel systems

 
 





