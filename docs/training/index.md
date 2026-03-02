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

<h1>🧑‍🔬 Lead Ambassador: Review request and approve/reject Agent for deployment to test users - this step is NOT for the Developers - </h1> 
All Approvers (sector leads) will be informed via both Teams and Outlook of an initiated deployment. The first to approve/reject will be sufficient to cancel out the rest (first to respond logic).

<img width="1141" height="586" alt="image" src="https://github.com/user-attachments/assets/73848b20-1677-43a6-b73a-30e8675c93ec" />

Once the request is approved/rejected it will be archived

<img width="1798" height="410" alt="image" src="https://github.com/user-attachments/assets/caa84c23-5ee7-459e-8593-fdc5f641cab0" />

<h1>Returning to the steps the Developers need to follow</h1> 
After approval, the solution will land in the Test environment under Managed Solutions, the core-components and configurations will be read-only.

<img width="1860" height="700" alt="image" src="https://github.com/user-attachments/assets/e9a8dcd7-efea-476f-bbf0-619804883481" />

The original maker has access to this managed solution and can view its contents

<img width="1912" height="729" alt="image" src="https://github.com/user-attachments/assets/f8b8a137-c3da-4197-9cde-ebf97e43b0ca" />


<h1>🧪 Sharing the Agent with test users who DO NOT HAVE an M365 Copilot license</h1>
For the requested test users who DO NOT HAVE an M365 Copilot license, the maker needs to share the agent through Copilot Studio so they can test it in the testing pane (similarly how the developer tests the agent while developing). Do so by making sure you are in the Copilot Studio portal, in the Test environment. Look for your agent in the agent list. Select the agent and click **Share**

<img width="1796" height="800" alt="image" src="https://github.com/user-attachments/assets/7e1d2d1d-db78-42ff-ae07-0eb188013dae" />

In the dialogue box that opens, type the name of the Test user who does not have an M365 Copilot license. Add it, click on it and select **Editor** access. Click **Update**

<img width="1567" height="813" alt="image" src="https://github.com/user-attachments/assets/5b9afbfb-c447-4fde-a833-a999321f7206" />

Instruct the user to go to Copilot Studio in the Test environment, (s)he will find the Agent there and can interact with the agent in the Agent Tester side-pane

<img width="1712" height="878" alt="image" src="https://github.com/user-attachments/assets/b4bfc336-d799-4a63-8d76-7cceea5ec7c2" />

<h1>🧪 Sharing the Agent with test users who DO HAVE an M365 Copilot license</h1>
For the requested test users who DO HAVE an M365 Copilot license, the maker can share the agent by deploying it to Teams, right after Publishing it. To Publish the agent, open it and click on **Publish**,  located in the upper right corner of the Copilot editor pane. 

<img width="959" height="308" alt="Image" src="https://github.com/user-attachments/assets/4e9e6489-1248-44b9-bfdf-009f8d118fee" />

You will be once again prompted to review any potential issues, warnings, before publishing. Review, then click **Publish**

<img width="298" height="170" alt="Image" src="https://github.com/user-attachments/assets/08fb45a9-f070-4616-97e7-1154c50330ac" />

You are now ready to expose this agent in Teams so that your M365 Copilot license holder testers can experiment with it. To do so, navigate to the **Channels** tab, select **Teams and Microsoft 365 Copilot**, in the dialogue box that opens, unselect the "Make agent available in Microsoft 365 Copilot" and press **Add Channel**

<img width="1580" height="798" alt="image" src="https://github.com/user-attachments/assets/51ddc4ba-4000-47b5-9548-387540705355" />

Next, it is IMPORTANT for the maker to select Edit Details and further describe what the agent does, and instructions for the Test users how to interact and use the agent

<img width="1583" height="875" alt="image" src="https://github.com/user-attachments/assets/403cb342-8423-4202-9927-266bd149960c" />

<img width="1763" height="900" alt="image" src="https://github.com/user-attachments/assets/20be8537-f7c6-47f5-b39d-1c670246f71f" />

Once you Save the changes, you'll be directed a screen back. Otherwise you can also click the **Back** arrow displayed on the upper left corner of this dialogue box

<img width="956" height="452" alt="Image" src="https://github.com/user-attachments/assets/eb70be4f-8366-4797-95ee-e2bd0b7bc4fb" />

Once the Teams integration is created and the agent description is added, the maker will be prompted to select who to share it with. Click **Availability options** and then **Show my teammatest and shared users**

<img width="953" height="452" alt="Image" src="https://github.com/user-attachments/assets/a9a0c873-62a9-4a0c-9502-d7702ce86d13" />

<img width="955" height="449" alt="Image" src="https://github.com/user-attachments/assets/57f373a8-28ca-4366-8b60-5802960123ae" />

**SIDE NOTE**: While you are active in this dialogue box, make sure to also **Copy link** and save it separately. This is the agent app link which, if shared with the Tester will also direct them to Teams, directly to the Agent for them to add as an App and start testing (it can, at times, prove to accelerate the process and saves Testers the time to look for the agent in the Teams store). This is not a mandatory step, but a remark.

<img width="321" height="268" alt="Image" src="https://github.com/user-attachments/assets/14e46c63-3ff5-4239-8652-0b679cd2df41" />

Continuing, after having selecting **Show my teammatest and shared users** as instructed a step above, in the new pop-up window that appeared, add the testers who do have an M365 Copilot license, they will automatically be granted Viewer permissions, click **Update**. Viewer permissions allows them to later test this agent directly in Teams.

<img width="1766" height="905" alt="image" src="https://github.com/user-attachments/assets/a87eee98-ca29-4fa0-a7f0-a5399c33c5cc" />

Depending on your ogranization's processes, your agent might now be submitted to an Teams Administrator to approve its availability in Teams. After the approval from the Teams Admin Center it will take a couple of hourse before the agent becomes available in Teams, from where the Test users can install and start testing it (described in the Testing tab)





