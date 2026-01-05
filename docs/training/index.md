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

**--- Agent development will be covered by the trainings starting January 8th ---**

 
<br>
<br>
<br>

Once the Agent has been built, tested and published, you can move on to deploy the Agent to the Test environment where you can scope it to your test users for functionality testing and feedback gathering.
To move the agent from the Dev-environment to the Test-environment, go back to this Solution window and choose **Deploy Pipelines (rocket icon)** from the left hand menu

<img width="324" height="413" alt="image" src="https://github.com/user-attachments/assets/b74bd1d6-c21d-4dc5-a72a-84ffd1754f35" />

Click **Deploy Here** to start the process

<img width="939" height="711" alt="image" src="https://github.com/user-attachments/assets/efee428a-e6df-4ec7-b3af-173153bf4808" />

On the next screen a new version will be automatically assigned to the solution and AI generated deployment notes.
**Important:** It is of upmost importance that you type in the Deployment Notes the e-mail addresses of the users in scope for testing the agent, followed by by whether they have an M365 Copilot license or not. DO NOT SKIP THIS STEP!

<img width="1261" height="699" alt="image" src="https://github.com/user-attachments/assets/2591ae35-ede1-4d4f-9d09-fca74bef9982" />






