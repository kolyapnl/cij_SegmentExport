# **Dynamics 365 Customer Insights - Journeys Solution for RTM Segment Export**


This solution provides feature parity with OBM (Outbound Marketing) and enables you to export RTM (Real-Time Marketing) Segments from Customer Insights - Journeys. It has been tested with segments containing over 1 million members.



**Features**
* Export RTM segments from Customer Insights - Journeys
* Seamless integration with Dynamics 365
* Handles large segments efficiently



**Installation steps**
1. Download the Soltuion
2. Import the soltuon to your target environment
3. Publish all customization
4. Ensure the solution is imported and published successfully. Use the Solution history to check the completion.



**Instruction**
1. Go to your environment
2. Find and open the "Segment Export" Model-Driven App (MDA)

TIP: Ensure you configure access for this app to allow only authorized users to export data.

![image](https://github.com/user-attachments/assets/02c48501-7281-43f2-bad8-9abd05a85fe6)

4. MDA contains the Segment view
5. The "Export Segment" function is available when a single record is selected with:

   Source = "Customer Insights - Journey"

   Status = "Ready to use"

![image](https://github.com/user-attachments/assets/c6df3699-dcc3-4807-bd01-f192393c06ce)


**Known limit**

Works for Segment with < 2 million members (due to this Dataverse limitation - https://learn.microsoft.com/en-us/troubleshoot/power-platform/dataverse/plug-in-execution/dataverse-plug-ins-errors#error-message-size-exceeded-when-sending-context-to-sandbox )


**Troubleshooting**

Ensure you have the necessary permissions to access and use the Segment Export MDA.

Verify the segment's status and source before attempting to export.
