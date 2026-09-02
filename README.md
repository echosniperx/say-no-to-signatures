This is a flow made with Microsoft PowerAutomate.

It lets you send a file to a specific user (Approver) via SharePoint to get their approval.
This is limited to a single level of approval.
The approver would receive a workflow via Teams and email. 
They may also view the overall status via Microsoft Approvals.
More than one approver can be chosen, and only one person needs to approve the document. 
You can track the status for this request using the Sign-off status column in the SharePoint directory.

If using this workflow, please note that you would need to amend the code's SharePoint List code, as every SharePoint list has a unique ID. 
SharePoint columns would also need to be updated as the coding / formula does not populate on its own. It needs to be linked to the PowerAutomate flow ID.

SharePoint Columns Type:
Sign-off Single line of text
Approved By Person 
Approved Date Date & Time
