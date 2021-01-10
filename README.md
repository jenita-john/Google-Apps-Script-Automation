## Description
The purpose of the script was to update the Google form automatically whenever a change has been made to the Google Sheet. In this specific case, a specific field, that is, a dropdown list in the Google form is updated automatically. Further, it is updating an existing Google form that has a dropdown list. For this scenario, the script should be bounded to the Google Sheet and the `onEdit` trigger must be enabled.

## Set Up 

1. Copy & Paste the script (UpdatingForm) to Google Sheet Script editor in the Google Sheets: `Tools > Script editor` <img align="left" alt="Script-Editor" src="https://user-images.githubusercontent.com/55056316/103392928-17637d00-4aee-11eb-8efd-63b3f5de1f3d.png"/>
2. Fill in the fields in UpdatingForm with appropriate Google form id and sheet locations.
3. Set `onEdit` trigger by clicking the clock in Script editor and then `Add Trigger`. <img align="left" alt="Trigger" src="https://user-images.githubusercontent.com/55056316/103393425-948ff180-4af0-11eb-9435-8cfd8c50a13b.png"/> 
4. In the function feild write `UpdateForm` and in triggers add `onEdit`<img align="left" alt="Trigger-setup" src="https://user-images.githubusercontent.com/55056316/103393558-30b9f880-4af1-11eb-87eb-656ff7c6e757.png"/> 

## Testing and Results 
As soon as a change is made to the Google Sheets, the `On Edit` triggers `UpdateForm` function and the dropdown list in the Google form is updated: 

<img align="center" alt="R1" src="https://user-images.githubusercontent.com/55056316/104116534-688e2080-52e7-11eb-962b-5465b1cfef25.png"/> 

<img align="center" alt="R2" src="https://user-images.githubusercontent.com/55056316/104116543-78a60000-52e7-11eb-9945-9fb1943abc70.png"/> 

<img align="center" alt="R3" src="https://user-images.githubusercontent.com/55056316/104116548-83f92b80-52e7-11eb-8bc9-64b848845839.png"/> 
