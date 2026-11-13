<img width="1917" height="1078" alt="Screenshot 2026-11-13 145115" src="https://github.com/user-attachments/assets/c6be1d40-fbd0-463f-a5cd-2964f0c4a442" /># Working-Floci-Cloud-Guide-Installation
Build a document storage environment using Azure Blob Storage.  Imagine an organisation needs to store documents, reports and invoices in the cloud.  I will implement: - A storage container. - File uploads. - File downloads. - File listing. - Cloud storage connection strings.

THIS IS FOR EDUCATIONAL PURPOSE ONLY...

OUR GOAL
<img width="707" height="621" alt="Screenshot 2026-11-13 152148" src="https://github.com/user-attachments/assets/42b68a7f-5a66-41e9-8a9b-b9e6085f0766" />
The architecture works as follows:
1. You run Floci CLI.
2. Floci starts the Floci-AZ Docker container.
3. The container exposes Azure-compatible endpoints on your computer.
4. Azure CLI or your application communicates with those endpoints.
5. You develop and test without consuming your actual Azure subscription.
Floci-AZ advertises support for multiple Azure services, including Blob Storage, Key Vault, Functions, Cosmos DB and networking-related resource APIs. However, emulator support is not identical to full production Azure functionality.

INSTALLING DOCKER AND ALSO STARTING THE ENGINE
<img width="1172" height="733" alt="Screenshot 2026-11-13 152429" src="https://github.com/user-attachments/assets/685cc2eb-d3e5-4a12-8919-f1b9f57f80ba" />

INSTALLING FLOCI CLI USING POWERSHELL
<img width="1917" height="1078" alt="Screenshot 2026-11-13 132901" src="https://github.com/user-attachments/assets/72394d79-0f46-4ee1-b213-ce1e68c5b20e" />
<img width="1917" height="1078" alt="Screenshot 2026-11-13 133526" src="https://github.com/user-attachments/assets/95d05691-0c36-4fbb-ab95-243481b19101" />

Starting our first local Azure environment including a PATH to our floci storage
<img width="1917" height="1073" alt="Screenshot 2026-11-13 134853" src="https://github.com/user-attachments/assets/8f89df4a-8236-4494-8f95-a18a4d295091" />

CREATING A STORAGE AND Configuring the certificate bundle:
<img width="1917" height="1078" alt="Screenshot 2026-11-13 135054" src="https://github.com/user-attachments/assets/76fca21f-38f3-4801-86d2-bcbd6eb8f2e6" />

DISPLAYING ACCOUNT CREATED
<img width="1917" height="1078" alt="Screenshot 2026-11-13 140333" src="https://github.com/user-attachments/assets/f8f5f18c-2597-4e62-95bb-ff428e41dd9d" />

CREATING AZURE RESOURCE GROUP AND ADDING A CONNECTIONG STRING OF OUR STORAGE
<img width="1917" height="1078" alt="Screenshot 2026-11-13 142559" src="https://github.com/user-attachments/assets/928c8fd7-5f03-44ba-9ecb-4012aa261c4f" />

CREATE A STORAGE CONTAINER
<img width="1917" height="1078" alt="Screenshot 2026-11-13 141411" src="https://github.com/user-attachments/assets/fc6ec223-a85a-490c-9bca-3f64fbb97abf" />

CREATING A SAMPLE DOCUMENT >> UPDLOAD IT IN STORAGE >> LIST STORED DOCUMENTS
<img width="1917" height="1078" alt="Screenshot 2026-11-13 151513" src="https://github.com/user-attachments/assets/8a6f7715-bbe0-422a-a546-96e23c85ffbf" />
<img width="1917" height="1078" alt="Screenshot 2026-11-13 151429" src="https://github.com/user-attachments/assets/3bd766f4-b68b-4e53-b6e9-b5cab3c2c50a" />
<img width="1917" height="1078" alt="Screenshot 2026-11-13 145115" src="https://github.com/user-attachments/assets/b7537d54-1e2a-43d1-9920-49522269e3e8" />
<img width="1917" height="1078" alt="Screenshot 2026-11-13 144958" src="https://github.com/user-attachments/assets/713996ff-6541-4828-a10f-f256b6da3052" />








