# CCS-Github 

Rishit Darwade

1st Dec, 2023

## *Part 1-Installation*

a. https://www.ti.com/tool/CCSTUDIO

To install CCS use the above  link and download the offline installer for windows

![image](https://github.com/rishitdarwade/tm4c/assets/70481119/7ae82820-bf8a-4c2e-bb5a-04a82bc5c051)


b. In the setup select component TM4C12x

![image](https://github.com/rishitdarwade/tm4c/assets/70481119/e51cb934-6110-46eb-ad13-0dd2471fd030)

c. select spectrum digital debug probes

![image](https://github.com/rishitdarwade/tm4c/assets/70481119/91ebbcfb-a2ed-4ff3-ae8d-71eca4d890ac)

![image](https://github.com/rishitdarwade/tm4c/assets/70481119/5c024838-1e4b-4599-8b15-74f9c434bbf7)


## Part 2- Workspaces 

Workspaces are the space where the changes of the code are made on your own local device.For creating a workspace in CCS these are the following steps:

1. In your file explorer of your device, create a new folder of workspace and add the CCS 
   file in it.This will just create a folder called workspace.

   ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/7f5a85a6-e7db-4ff0-9a09-e28fd9ad6a77)

2. Now, to make this an actual CCS workspace there area few steps we need to do on CCS.
   a. In CCS,on the top left corner click on file→Switch Workspaces→other

   ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/de2f4bb6-e8e2-425b-ad2b-b4eaddc04c75)

   b. Now it will open up the tab given below where you can browse the workspace file you 
      have made and launch.This will result in the file you have created to be a 
      CCS workspace.

   ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/46ef13a4-7fdf-4366-92cc-39d995273db4)

## Part 2- Connecting your workspace to a local repository 

   1. Now, before connecting your Workspace to your local repository, you create a 
      project where you do the work.

      a. For that you go into the file→new→CCS project.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/4d15480e-909a-4aaa-b08d-a06467c55e49)

      b. Select the target,MCU,connection and compiler and hit finish.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/0cd2659a-9133-4e2e-bcee-8e2b64ac3d37)

      2. To connect the workspace to a local repository you will have three options 
          written

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/f77376bd-0b23-4fb7-a7ac-71e6f59555ff)

      a. To add an existing local repository click on it→browse and add the repository.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/41655b4a-0bc6-48f6-a659-feebb225d356)

      b.To clone a remote repository write the url using one protocols in the remote 
        repository go to you remote repository→click on code→copy any one link→paste itin 
        the URL section and everything else will autofill→choose branch and finish.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/b52b8e58-1aff-4c3f-adb6-470cdccbb190)

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/5c93106c-30d6-401d-a691-b888f64ca802)

      c. To create a new repository.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/3700f05e-1636-46bd-89a3-8415c33893ae)

## Part-3 To commit and push

1. Commit is a process in which the changes made in the workspace are moved to the local 
   repository from the staging (staging is basically a buffer where before committing to 
   the local repository it allows you to select specific files which you want to 
   commit)or you can directly commit from the workspace to your local repository if you 
   want tocommit all the files.
   
   The following are the steps to commit a file:
   
   a. First, right click on the project file which you want to commit→teams→commit.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/1fdb8a3c-bdcb-4263-a819-f71cd6e03d1a)

   b. Add a commit message specifying what changes have been made in the file and press 
      commit.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/b52f2c28-8f73-4496- 
      bf4b-c8cbdbaf3a9e)

2. Push: The turn push defines as when you push the file which is in your local repository to your remote repository.There are two ways to push a file:
   
   a. To press the push which is on the bottom right corner.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/3d4c9104-30de-4dec-9b42-ad69d671e94c)

   b. After clicking push a box will open where there will be an option of preview which 
      should be clicked as it previews if the file is compatible with making changes in 
      the main.

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/1ae0210a-4602-4825-9730-5d9c64fa5a81)

      ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/2ef540fb-6a1c-4592-a1ee-a48ef1b7f768)

## Part-4 Pull
1. Pull is a step where you pull a file from the remote repository directly to your 
   workspace to make changes in it. To pull a file from the remote repository right 
   click on the local repository in the git repository section —>there will be two pull 
   options,click on the 1st to pull directly.

   ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/0ffa6ee4-7c25-4e8f-9f0e-52f955ae0f52)

2. The second pull function opens a box where you can manually select the remote 
   repository, the branch and how you want the file.

   ![image](https://github.com/rishitdarwade/tm4c/assets/70481119/a46e7de3-3581-4bbd-8877-6ed1d915a1f5)

   

   
      
   


   




   
   






      



      

      
















