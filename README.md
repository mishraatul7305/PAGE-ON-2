# PAGE-ON-2 
STEP 1: Create Trigger
1.Open n8n
2.Click + Add Node
3.Select When Chat Message Received
4.This will start the workflow when a user sends a message.
STEP 2: Add AI Agent
1.Click + after trigger
2.Search AI Agent
3.Connect it with the trigger 
STEP 3: Add Chat Model
1.Open AI Agent node
2.Go to Chat Model section
3.Click Add Model
4.Select your model (like Google / OpenAI)
5.Configure API key
6.Save 
STEP 4: Add Memory
1.Inside AI Agent
2.Click Add Memory
3.Select Simple Memory or database memory
.4Set a unique Session ID (like MY id)
4.Save
Step 5: Add Tool (Google Sheets)
-Click Add Tool
-Select Google Sheets
-Choose operation → Get Rows
-Connect your Google account
-Select spreadsheet & sheet name
-Save 
Step 6: Activate Workflow
-Click Save
-Click Activate
-Open Chat
-Send a message to test 
Final Flow
Chat Trigger → AI Agent → (Model + Memory + Google Sheets Tool) → Reply.
