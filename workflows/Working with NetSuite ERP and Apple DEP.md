# Working with NetSuite ERP and Apple DEP
The following topic provides instructions for using Apple's Device Enrollment Program (DEP) in NetSuite. 

A store can enroll or remove items from the Device Enrollment Program as part of sales or return transactions in ERP. A typical process by which this can occur is as follows:

1. During a transaction in ERP, if both the customer and items entered are specified as Apple Device Enrollment Program eligible, a pop-up box appears asking if you want to enroll or remove these items.
   
    > [!NOTE]  
    > Please ensure that your browser’s pop-up blocker allows pop-ups from NetSuite. 
2. To enroll or remove the items, enter their serial numbers for validation. The location to enter the serial numbers will differ depending on the CS Apple DEP Preferences being set to have Serialized Inventory enabled or disabled (see Setting Up Apple DEP Preferences).

3. Verify that the Enroll in Apple DEP column shows as **Yes** and that the **DEP Device Serial #** column has all the serial numbers present and correct before saving the transaction.
4. After the transaction is saved, verify that a **CS Apple DEP Transactions Line** custom record is created. You can access this record from the transaction’s DEP Integration Line column. This custom record contains a link to the **CS Apple DEP Serial Numbers** record which Hyperspace accesses to validate the enrollment and unenrollment of eligible devices from line items in the transaction into the Apple Device Enrollment Program. 
   > [!NOTE]  
    > If a Serial Numbers Record displays the **Needs Review** box as checked, this indicates that an error was returned from Apple or Hyperspace. A list of records with Needs Review checked off is provided by a saved search that notifies a designated recipient (see Setting up Apple DEP Needs Review Reports).
