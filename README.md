## Description
The script automatically updates any changes made in the Google Sheets to the associated Google form. To achive this bounded script must be added to the Google Sheets and `on-edit` trigger must be enabled.

## Reuse Set up 

1. Add the bounded script (UpdatingForm) to Google Sheet:
`Tools > Script editor`
<img align="left" alt="Script-Editor" src="https://csharpcorner.azureedge.net/UploadFile/BlogImages/10072019102513AM/1.png"/>
2. Fill in the fields in UpdatingForm with appropriate Google form id and sheet locations.<br>
3. Add `onEdit` trigger by clicking the clock in Script editor and then `Add Trigger`. In the function feild write `UpdateForm` and in triggers add `onEdit`
<img align="left" alt="Script-Editor" src="https://i1.wp.com/alicekeeler.com/wp-content/uploads/2018/12/2018-12-13_07-39-52.png?w=1052&ssl=1"/>
