# Outlook-Contacts-Import
This tool allows IT administrators to remotely import a list of company contacts into users’ Outlook contacts at scale. Users can then sync these contacts to their mobile devices through the Outlook app, provided contact syncing is enabled.  See the README for setup and configuration instructions.


How to:

Make sure you setup an APP registration in Entra, this is where youll find your client secret, tenant ID etc.. 


then make sure you allow these permissions<img width="782" height="222" alt="image" src="https://github.com/user-attachments/assets/c8eb8272-791c-4635-a23a-b772f7e1cea8" />

Next, open the app and go through these three options <img width="1301" height="906" alt="image" src="https://github.com/user-attachments/assets/17afef30-a0b9-47b5-aeff-cb73f8c48205" />

link your entra app registration and click test signin: <img width="953" height="669" alt="image" src="https://github.com/user-attachments/assets/0e600942-b273-40d2-aec0-e62e1a469734" />

This is where youll add your contacts that need imported into a user. you can choose to upload a csv or create them manually in the program: <img width="1365" height="481" alt="image" src="https://github.com/user-attachments/assets/2f7df438-a2c5-4dba-a7f3-8859bf938211" />


Next choose the target email address, you can do yours as a test: <img width="1384" height="469" alt="image" src="https://github.com/user-attachments/assets/a64d78d6-ebc3-4538-9a74-b42e1da25f10" />

Go to the run operations screen, this is where the magic happens. click build previewe, this will generate any changes you made in your master contacts, for the user you chose in the mailbox section. Once it builds the preview, and you are happy with everything. click Apply selected changes. <img width="1403" height="488" alt="image" src="https://github.com/user-attachments/assets/3a0bb2c3-6301-4e48-9928-63e265102ec4" />

THATS IT!








