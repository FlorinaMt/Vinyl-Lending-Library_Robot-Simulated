## Use


&emsp;A Vinyl has at least a title, artist, year, and a lending state. The Vinyl can be in different states depending on availability, reservation, borrowing or a combined borrowing and reservation.

&emsp;You can borrow a Vinyl either if it is not reserved by someone else, is not already borrowed or if it is reserved by you (reserved). 

&emsp;You cannot reserve a Vinyl if it already contains a reservation (there is no reservation list, only one person at the time can reserve the Vinyl). However, you are allowed to reserve

&emsp;A Vinyl if it is available (no reservation and not borrowed) or if it is borrowed and does not have another reservation. 

&emsp;A Vinyl can be removed from the library if it has no reservation and is not borrowed (available). If the Vinyl is borrowed, reserved or both, then the removal sets a flag such that the Vinyl cannot be reserved any longer. 

&emsp;The Vinyl is not fully removed until it has been returned and does not have a reservation (the person who may have reserved the Vinyl will still be able to borrow it, before it is finally removed)

&emsp;A GUI with two windows displays a list of Vinyls including their states. Select one Vinyl and Reserve, Borrow or Return it. Remove a Vinyl (mark it to be removed until its state allows it to be fully removed).
Information that a Vinyl is about to be removed (before it is fully removed) is displayed. Two threads simulate “Bob” and “Wendy” reserving, borrowing and returning a Vinyl.

### Requirements
- MVVM with at least two windows;
- the Observer design pattern;
- the State design pattern for the different states of a Vinyl;
- threads for the simulation and still be able to manually use the system (in the GUI)

#### Class Diagram
![image](https://github.com/betelgeuseBet/Single-User-Vinyl-Lending-Library_Robot-Simulated/assets/151634373/fa17e59e-fd34-4295-867d-122ffa234d10)

#### State Machine Diagram
![image](https://github.com/betelgeuseBet/Single-User-Vinyl-Lending-Library_Robot-Simulated/assets/151634373/12b83ee7-596f-484e-84f0-a495bc61b6c5)

#### The application:
![image](https://github.com/user-attachments/assets/1ca4bec8-11ad-4c94-847e-fa2f466e837e)
![image](https://github.com/user-attachments/assets/7efdc465-0e64-442a-8061-42db42e9e259)
![image](https://github.com/user-attachments/assets/c8c6288e-87b1-4f9b-b55c-9201c28262ac)

