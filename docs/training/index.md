# Training

Training materials and walkthroughs for the POC. This document will outline how to set up your environment for Agent development and how to use Copilot Studio

 
<br>

<h1>📂 Create a solution</h1>
Best Practice for everything in the Power Platform (and therefore Copilot Studio): Work INSIDE solutions. They are great for organizing your customizations and some features only work here.

Because of that our first step in the Copilot Studio portal is to navigate to **Solutions** under the [...]-Button on the left hand side

<img width="1231" height="672" alt="image" src="https://github.com/user-attachments/assets/dd720bed-8645-4bcc-98e9-18006e92012e" />

After the Solutions portal opens, click **+ New Solution**

<img width="1422" height="394" alt="image" src="https://github.com/user-attachments/assets/698cac5c-6894-4935-b974-c6e06e5d49f5" />

In the dialog side-bar which opens, give your solution a meaningful name for the usecase and either choose the **Default Publisher for orgxx (default)** or create your own New Publisher. After entering the details, click **Create**
Note: Using the default publisher is not considered best practice because you have no control about the technical prefix all your components will receive

<img width="348" height="518" alt="image" src="https://github.com/user-attachments/assets/31920667-baec-40fd-a0f8-af125334400a" />

Your solution is created and currently empty. You can now start building an agent (or any other asset) by opening the Solution, navigating to **+ New** and choose the component type. Once saved it will automatically be added to the provisioned solution.  

<img width="745" height="411" alt="image" src="https://github.com/user-attachments/assets/f8e1d5c6-d3d2-4e44-9df6-f73d7054f17f" />


  
  

<br>
<br>
<br>

<h1>✨ Develop an agent</h1>

**--- Agent development will be covered by the trainings starting January 8th ---**

 
<br>
<br>
<br>

<h1>🚀 Deploy your agent to testers (approval required)</h1>
Once the Agent has been built, tested and published, you can move on to deploy the Agent to the Test environment where you can scope it to your test users for functionality testing and feedback gathering.
To move the agent from the Dev-environment to the Test-environment, go back to this Solution window and choose **Deploy Pipelines (rocket icon)** from the left hand menu

<img width="324" height="413" alt="image" src="https://github.com/user-attachments/assets/b74bd1d6-c21d-4dc5-a72a-84ffd1754f35" />

Click **Deploy Here** to start the process

<img width="939" height="711" alt="image" src="https://github.com/user-attachments/assets/efee428a-e6df-4ec7-b3af-173153bf4808" />

On the next screen a new version will be automatically assigned to the solution and AI generated deployment notes.
**Important:** It is of upmost importance that you type in the Deployment Notes the e-mail addresses of the users in scope for testing the agent, followed by by whether they have an M365 Copilot license or not. DO NOT SKIP THIS STEP!

<img width="1261" height="699" alt="image" src="https://github.com/user-attachments/assets/2591ae35-ede1-4d4f-9d09-fca74bef9982" />

<br>

<h1>🧑‍🔬 Lead Ambassador: Review request and approve/reject Agent for deployment to test users</h1>
All Approvers (sector leads) will be informed via both Teams and Outlook of an initiated deployment. The first to approve/reject will be sufficient to cancel out the rest (first to respond logic).

<img width="1141" height="586" alt="image" src="https://github.com/user-attachments/assets/73848b20-1677-43a6-b73a-30e8675c93ec" />

Once the request is approved/rejected it will be archived

<img width="1798" height="410" alt="image" src="https://github.com/user-attachments/assets/caa84c23-5ee7-459e-8593-fdc5f641cab0" />

After approval, the solution will land in the Test environment under Managed Solutions, the core-components and configurations will be read-only.

<img width="1860" height="700" alt="image" src="https://github.com/user-attachments/assets/e9a8dcd7-efea-476f-bbf0-619804883481" />

The original maker has access to this managed solution and can view its contents

<img width="1912" height="729" alt="image" src="https://github.com/user-attachments/assets/f8b8a137-c3da-4197-9cde-ebf97e43b0ca" />


<h1>🧪 Sharing the Agent with test users</h1>
For the requested test users who DO NOT HAVE an M365 Copilot license, the maker needs to share the agent through Copilot Studio so they can test it in the testing pane (similarly how the developer tests the agent while developing). Do so by making sure you are in the Test environment, open the deployed Solution and then the Agent. You'll be directed to the Copilot Studio portal, select the agent and click **Share**

<img width="1796" height="800" alt="image" src="https://github.com/user-attachments/assets/7e1d2d1d-db78-42ff-ae07-0eb188013dae" />

In the dialogue box that opens, type the name of the Test user who does not have an M365 Copilot license. Add it, click on it and select **Editor** access. Click **Update**

<img width="1567" height="813" alt="image" src="https://github.com/user-attachments/assets/5b9afbfb-c447-4fde-a833-a999321f7206" />

Instruct the user to go to Copilot Studio, (s)he will find the Agent there and can interact with the agent in the Agent Tester side-pane

<img width="1712" height="878" alt="image" src="https://github.com/user-attachments/assets/b4bfc336-d799-4a63-8d76-7cceea5ec7c2" />

For the requested test users who DO HAVE an M365 Copilot license, the maker can share the agent by deploying it to Teams. To do so, open the Agent, navigate to the **Channels** tab, select **Teams and Microsoft 365 Copilot**, in the dialogue box that opens, unselect the "Make agent available in Microsoft 365 Copilot" and press **Add Channel**

<img width="1580" height="798" alt="image" src="https://github.com/user-attachments/assets/51ddc4ba-4000-47b5-9548-387540705355" />

Next, it is IMPORTANT for the maker to select Edit Details and further describe what the agent does, and instructions for the Test users how to interact and use the agent

<img width="1583" height="875" alt="image" src="https://github.com/user-attachments/assets/403cb342-8423-4202-9927-266bd149960c" />

<img width="1763" height="900" alt="image" src="https://github.com/user-attachments/assets/20be8537-f7c6-47f5-b39d-1c670246f71f" />

Once the Teams integration is created, the maker will be prompted to select who to share it with. Click **Show my teammatest and shared users**

<img width="1676" height="849" alt="image" src="https://github.com/user-attachments/assets/8fc1b6da-f226-4622-b41b-74855cd7d5d8" />

In the new pop-up window, add the testers who do have an M365 Copilot license, they will automatically be granted Viewer permissions, click **Update**

<img width="1766" height="905" alt="image" src="https://github.com/user-attachments/assets/a87eee98-ca29-4fa0-a7f0-a5399c33c5cc" />

Your agent will now be submitted to an Teams Administrator to approve the deployment. After the approval from the Teams Admin Center it will take a couple of hourse before the agent becomes visible to the test users.





