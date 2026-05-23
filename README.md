Matzilon

Matzilon is a daily-use app designed to support users in maintaining a healthy mental state. 
The app was developed in collaboration with the non-profit organization "Hamama Hevratit," which focuses on assisting individuals with mental health challenges. 
The organization works closely with the Technion to develop innovative products and services.

This project was created as part of an annual initiative by the Faculty of Computer Science at the Technion 2024, under the supervision of the ICST organization.

## My contributions:
- Made a firebase database so that the developers could edit texts(widget's values) in the application whenever they wanted (edit text for unique genders for example).
- The firebase was also used to transfer encrypted user data from one device to another via QR code. 
The encrypted data would only remain in the database for a short period of time and later deleted.
Each transaction would require the following: Unique Key, an encrpytion Iv and an encryption key:
## Unique Transaction Key: 
- Generated per request to serve as a single-use token (nonce). This explicitly prevents replay attacks, ensuring an intercepted payload cannot be maliciously re-submitted to the server.
## Cryptographic Initialization Vector (IV):
- Ensures that the encryption process is truly non-deterministic. By using a distinct, random IV for every transaction, the exact same user input (e.g., repeating a specific status log) will produce entirely different ciphertext every time, eliminating structural pattern leakage.
## Symmetric Encryption Key: 
- Utilized for high-speed, secure payload encryption, ensuring data remains completely confidential from end to end.


![image](https://github.com/user-attachments/assets/5314c6c2-c162-471f-bf31-6cbb9dfe739e)

The project was developed by David Avigdor, Tavor Ashkenazi, Dareen khair , Yoav Harpaz , Iris Becker
Dina Alexadrovich
In collaboration with Amit Clubhouse Association and the Technion's Social Incubator

