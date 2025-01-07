# OCR-service
**OCR-service** is the the starting point of the **ScanBill** project. 
## For starters, the **OCR-service** will handle mostly main logic for ScanBill project like:
  - Recieving users requests
  - Extracting text from images.
  - Analyzing the resulting text and Caategorizing the text contents.
  - Storing extracted raw data and analyzed data in any Storage solution.
  - Providing Reports according to the data analysis.
## **OCR-service** Must be designed to work only on extracting text from images
### Other Implemented logic must be moved to othe Sub-systems according to the system architecture and design needs
## Guidelines
  - Software Engineering concepts must be followed like the **SOLID** principles.
  - this service must be designed as a **modular-monolith** project where each **module** can be exrtacted and used as a standalone service on scaling is needed.
