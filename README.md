HOW TO USE: - PLEASE REFER BELOW INSTRUCTIONS
In the Collection Variables section, update the following:
Environment – Enter the target environment
 (e.g., DEV2, DEV7, QLAB02, etc.) – case insensitive.
ESP – Enter the ESP detail (e.g., QLAB02, QLAB03, etc.). – case insensitive.
RESOURCE_EXT_ENV – Optional:
Leave blank to default to the selected Environment.
Or specify a different environment if needed (e.g., DEV2, DEV7, QLAB02, etc.).

OrderID – Enter the specific Order ID you want to test.
EID_List (non-mandatory) - This can be changed if required but make sure to give in same Array format as shown in example below with any number of EIDs. ["89049032005001111110000005878097","89049032005001111110000005877418"]
TAC_Codes (non-mandatory) - This is required to generate IMEIs for ESIM and Device with no Plan orders. You can change only if required or leave as is but make sure to give in same Array format as shown in example below with any number of TAC Codes.
 ["35077773", "35487650"]
Delay (non-mandatory) - This is a delay set before triggering each request, can be modified as per requirement.
password - As part of password rotation this field has to be updated each time the password is changed.

Only update non-mandatory variables if your test case demands it; otherwise, they can be left at their default values.
Once variables are set as per your requirement:
Click on Activation / Return.
Simply run the collection.
No need to uncheck any request or modify variables unless explicitly needed for your scenario.
