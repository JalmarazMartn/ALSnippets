# Miscelaneous AL snippets in individual files.
Copy them in your work folder %APPDATA%\Code\User\snippets

# Test dependencies Snippet.
Bring to your app.json file all test app dependencies when you type TtestDependencies. Tabstop for version.

#Singleton Pattern 
This is a https://github.com/al-design-patterns/al.singleton snippet implementation. Pattern=Snippet!!

# AL Navision/Business Central Notification Snippet
This is a JSON Snippet to implement Notifications in AL Business Central.
Create a new Codeunit with all the methods to create a new Notification in a very easy way.
Tabstops decription:
- Codeunit ID. Codeunit number. Example 50001.
- Codeunit Name. Example: "Sales Line Price Check".
- Record to check. Name of the record to Check: SalesLine.
- Table Name to check: Name of table to check: "Sales Line".
- Field1,Field2: Could Add more, are basics fields of the tabla to perform check: "No.", "Sell-To Customer No.".
- FieldVar1,FieldVar2: Parameters and variables to set Notification data. ItemNo, CustNo.
- GUID. Notification GUID.
- MasterTable. Master Table to check Notification is enabled. Example: Item.
- Details Page. Name of the variable of page details. Example: ItemAvailabilityCheck.
- Details Page Name: Example: "Item Availability Check".
