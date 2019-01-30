### Workflow Editor

<details>
  <summary><b>How to create a new workflow?</b></summary>
  

  Click on `Workflow Editor` view.
  
 ![Workflow editor](images/workflow-editor-header.png)

Click on `+` button.

  ![Plus button](images/workflow-editor-plus.png)

  Add some blocks and end your workflow with a `Delivery` block.

Select the tool to use for each block (including ingest).

  ![Select tool](images/workflow-select-tool.png)

Fill all red fields in each block.

  ![Fill block](images/workflow-fill-block.png)

Select some files to send on `Ingest block`.

  ![Ingest](images/workflow-ingest-files.png)

Click on `Execute workflow`.

  ![Execute](images/workflow-execute.png)
  

</details>

<details>
  <summary><b>Presentation of all blocks.</b></summary>

**Ingest :** Allows to upload files to Eolementhe.

- ***Standard :***  upload file with HTTPS protocol.
- ***Standard Object Storage :*** upload file from OVH, AZURE or AMAZON. 
- ***Server File :*** use file already present on the platform.
- ***Premium :*** upload file with Signiant App.
- ***Premium Object Storage :*** upload file with Signiant App from OVH, AZURE or AMAZON.
- ***Internet :*** upload file by URL internet video.
- ***FTP :*** upload file with FTP protocol.
- ***Aspera :*** upload file with Aspera specific protocol.
- ***Live stream :*** upload file from live stream.
- ***Twitter :*** upload file from twitter publication.
- ***Dropbox :*** upload file from Dropbox account.

**Delivery :** Deliver the generated files (and sources if option added) of the workflow. 

- ***Manual :*** deliver file on Eolementhe platform.
- ***Object Storage :*** deliver file on OVH, AZURE or AMAZON.
- ***Mediashuttle :*** deliver file on mediashuttle portal.
- ***FTP export :*** deliver file on FTP instance.
- ***Youtube :*** deliver file on youtube account.
- ***Aspera connect :*** deliver file with Aspera protocol.
- ***Twitter :***  deliver file on twitter account.
- ***Dropbox :***  deliver file on dropbox account.


**Quality control :** Generates a quality control report in accordance to the preset entered. 

- ***Baton :*** Generate a quality control report with Baton.
- ***Photon :*** Generate a quality control report for  IMF package.
- ***Mediainfo :*** Generate report of technical metadata of the media file.


**Transcoding :** Generate a new media file in accordance to the preset entered.

- ***Harmonic WFS :*** Transcode file according to your Harmonic WFS workflows/presets.
- ***File360 :*** Transcode file on File360 service.
- ***RewrappAS10 :*** Rewrapp .mxf file with AS10 compliant metadata.
- ***ffmpeg :*** Transcode file with ffmpeg.
- ***Titan File :*** Transcode file with Titan File transcoder.
- ***Cambria :*** Transcode file with Cambria FTC transcoder.


**Loudness :** Generate or/and correct errors on audio tracks of the media file.

- ***Minnetonka ATS :***  Check and fix loudness with Minnetonka Audio Tools Server.
- ***ffmpeg :*** Check and fix loudness with ffmpeg.


**Metadata :** Create or read metadata to a media in accordance to your template.

- ***Metadata :*** Add metadatas according to your preset.
- ***Auto retrieve :*** Retrieves metadatas from media files and generate file with metadatas.


**Pause :** Create a pause in the execution of tasks in the workflow.

**IMF :** Generate an IMF package with `.mxf` file.

**Subtitle :** Generate, convert or burn subtitles on a media file.

- ***Convert :*** Convert subtitle files to another subtitle file format.
- ***Burn :*** Burn the subtitle file into a media file. 
- ***Translation Google :*** Generate subtitles with Google translation. 
- ***Translation Microsoft :*** Generate subtitles with Microsoft translation. 
- ***Translation Deepl :***  Generate subtitles with Deepl translation. 
- ***Speech to text :*** Generate subtitles from the audio tracks of a media file with Autosub.
- ***Speechmatics :*** Generate subtitles from the audio tracks of a media file with Speechmatics.
- ***Video Indexer :*** Generate subtitles from the audio tracks of a media file with Video Indexer.

**Antivirus :** Detect the presence of viruses in media files. 

- ***Clamav :*** Generate report with Clamav.


**Trim :** Cut a media to the time codes specified. 

**Expand :** Modify the workflow with parallel or conditional actions.

- ***Parallel :*** Create parallel branches to perform tasks simultaneously. 
- ***Conditional :*** Create conditional rules (if...then) on workflow . 


**AI :** Use of artificial intelligence to detect faces, tags etc ...

- ***Videobox :*** Detects faces, nudity images and tags with Videobox.
- ***Video Indexer :***  Detects faces with Video Indexer.

</details>



<details>
  <summary><b>Some blocks are red when I try to create a workflow.</b></summary>
  

  If you see red blocks like the following screenshot, this means that you don't have right to use these blocks.

  Check your contract to see if the dates and tools should be available.

  Contact an administrator at `support@videomenthe.fr` if the blocks should be available.
  
If the blocks are not available but you want the new functionalities please contact the sales team at `contact@videomenthe.fr`.

  ![Workflow red blocks](images/workflow-red-blocks.png)

</details>

<details>
  <summary><b>How to save a workflow?</b></summary>
  

  Build or load a workflow.

  Click on `save` to save modifications on an existing workflow

  ![Save](images/workflow-save.png)

  Click on `save as` to save as a new workflow. You will be asked to enter a name for this workflow.

  ![Save as](images/workflow-save-as.png)
</details>

<details>
  <summary><b>How to load an existing workflow?</b></summary>
  

  Click on `Select a workflow`.

  ![Select a workflow](images/workflow-select.png)

  Select the workflow you want to load.
</details>

<details>
  <summary><b>How to share a workflow?</b></summary>
  

Sharing a workflow means that the users with whom you have shared your workflow will be able to load and use your workflow, but will not be able to modify it.

Load an existing workflow and click on `Share`.

![workflow-share](images/workflow-share.png)

In the pop-up you can add and choose the email of the user you want to share the workflow with.

![workflow-share-modal](images/workflow-share-modal.png)

View when you share your workflow. 

![workflow-share-with-other](images/workflow-share-with-other.png)

View when a workflow is shared with you. 

![workflows-share-with-me](images/workflows-share-with-me.png)

</details>


<details>
  <summary><b>How to use naming rule in my workflow?</b></summary>
  

Click on  `Naming rule`.

![dropdown-manage-naming-rule](images/dropdown-manage-naming-rule.png)


Here you can add naming rules with your custom format. Enter the name of your rule and then you can write the template of naming you want for your files.

Here example of naming rule :

![workflow-namingrule](images/workflow-namingrule.png)

For adding variable in your name like `Days`, `Months`, `File Name` you just have to click on it.

After adding  naming rule, on each block appear this : 

![workflow-naming-rule](images/workflow-naming-rule.png)

So select your naming rule and this will be applied to all output files of the block. 


</details>

<details>
  <summary><b>How to notify someone?</b></summary>
  

You can notify the status of your workflow to other users with the recipient email feature. 

Recipient email appears in Pause and Delivery block. 

![workflow-recipient-email](images/workflow-recipient-email.png)

The  recipient email allows users added to have the same follow-up as the owner of the workflows (monitoring, notifications, email ...). 

Your own email address is automatically added in the recipient email list.

 You can search all users on the platform and if the user doesn't exist you can add him by writing his email address in the search bar and pressing `Enter`. You can suppress an existing email from list by clicking in the red trash button.


</details>

<details>
  <summary><b>Good practices for collaborative workflow.</b></summary>

If you want to create collaborative workflows, some good practices must be respected.

The easiest way is to use the pause block. At each pause all users in the email recipient list will have access to the file generated from the previous block. 

Thus all users in recipient list will receive an email giving them access to the file generated from the previous block. In addition, they will see the workflow in the monitoring view and  will be allow to edit the file library . They will also be able to continue or stop the workflow in the monitoring view. 

Let's take a simple example: 

A user starts a translation workflow. However, several translators must access to the file in order to be able to modify it. We create the following workflow: 

![workflow-collaborative-subtitle](images/workflow-collaborative-subtitle.png)

Once the workflow is paused, users in the recipient email list will be notified by email. They will receive the link to connect to the file library and to check the result of the previous block (here a Speech to text block). In this example they will just have to correct the subtitles file `.srt`. Once the corrections have been made, one of the users can simply  click on `Validate file and continue workflow`to make the workflow continue or click on `Stop workflow for this file` to abort the execution of the workflow (in `File library`on the file paused). 

</details>

<details>
  <summary><b>How to organize my file by folder?</b></summary>

In the `ingest` and `delivery` block you can see a `Destination folder` field that allows you to organize these files with folders.

The `Destination folder` field of the Ingest block allows you to redirect all source files to the folder/subfolder you specify. 

The `Destination folder` field of the Delivery block allows you to redirect all generated files to the folder/subfolder you specify. 

If you leave the fields empty as below: 

![workflow-editor-ingest-delivery-destination-empty](images/workflow-editor-ingest-delivery-destination-empty.png)

All your sources and generated files will be sent to the root of your Eolementhe file server.

![workflow-editor-ingest-delivery-destination-empty-result](images/workflow-editor-ingest-delivery-destination-empty-result.png)

If you specify the field `Destination folder` you will be able to classify your files simply. 

Example : 

![workflow-editor-ingest-destination-complete](images/workflow-editor-ingest-destination-complete.png)

Here we redirect all the source files to the `origin` folder, which is in the `test` folder. And we redirect all the generated files to the `loudness` folder which is in the `test` folder.

Result in the `File Library`: 

![workflow-editor-ingest-delivery-destination-complete-result](images/workflow-editor-ingest-delivery-destination-complete-result.png)

</details>

<details>
  <summary><b>How to create FTP watchfolder?</b></summary>

An FTP WatchFolder allows you to specify a folder on an external FTP server. When adding files to this folder all the files added will be taken as source files and launched by Eolementhe in a workflow of your choice. 

At first you will need to add your FTP server. For that nothing simplier select the `FTP`or `FTP export` option in the ingest or delivery of your workflow.  

Click on `Add Server`

![workflow-ftp-watch-folder-2](images/workflow-ftp-watch-folder-2.png)

Fill in the data relating to your FTP server and click on `Submit`.

![workflow-ftp-watch-folder-3](images/workflow-ftp-watch-folder-3.png)

Now click on your login at the top right of Eolementhe and click on `FTP Watch Folder`.

![workflow-ftp-watch-folder-1](images/workflow-ftp-watch-folder-1.png)

Select the FTP container you just entered before. Select the folder that will be watched. And click on `Submit`.

![workflow-ftp-watch-folder-5](images/workflow-ftp-watch-folder-5.png)

You should arrive on this page which lists all your Watchfolder folders that you have entered. This is also where you can delete FTP watchfolder by clicking on the red icon.

![workflow-ftp-watch-folder-6](images/workflow-ftp-watch-folder-6.png)

</details>

<details>
  <summary><b>How to add Baton preset?</b></summary>

First add a `Quality Control` block to your workflow and choose `Baton`. 

If your preset list is empty, add a test plan by clicking on  `Add a test plan`.

![workflow-baton-add-preset-1](images/workflow-baton-add-preset-1.png)

Clicking again on `Add a test plan` and load your test plan. 

![workflow-baton-add-preset-2](images/workflow-baton-add-preset-2.png)

When your test plan is added click on `upload` to load your test plan on your profile. 


![workflow-baton-add-preset-3](images/workflow-baton-add-preset-3.png)

Once uploaded your test plan will be displayed in the list like this (here we add test plan named `aaaaaa`). You can delete or download your test plan from here.

![workflow-baton-add-preset-4](images/workflow-baton-add-preset-4.png)

Return to your workflow and select the added test plan. 

![workflow-baton-add-preset-5](images/workflow-baton-add-preset-5.png)

</details>

<details>
  <summary><b>How to add Harmonic WFS preset?</b></summary>

First add a `Transcoding`  block to your workflow and choose Harmonic WFS. 

If your preset list is empty, add a preset by clicking on  `Add Presets`.

![workflow-harmonic-add-preset-1](images/workflow-harmonic-add-preset-1.png)

Clicking on `Add Workflow` for add your workflow preset. 
![workflow-harmonic-add-preset-2](images/workflow-harmonic-add-preset-2.png)

When your workflow preset is added click  on `upload` to load.

![workflow-harmonic-add-preset-3](images/workflow-harmonic-add-preset-3.png)

Now add all presets used by your preset workflow and click `upload` again to load your preset on your profile. 

![workflow-harmonic-add-preset-4](images/workflow-harmonic-add-preset-4.png)

Once uploaded your preset will be displayed in the list like this (here we add preset named `EOLE_2`). You can delete or download your test plan from here.

![workflow-harmonic-add-preset-5](images/workflow-harmonic-add-preset-5.png)

Return to your workflow and select the added preset. 

![workflow-harmonic-add-preset-6](images/workflow-harmonic-add-preset-6.png)

</details>

<details>
  <summary><b>Create and manipulate IMF packages.</b></summary>

Create a workflow with an IMF package block and with your `.mxf` files in Ingest as below.

![workflow-imf-1](images/workflow-imf-1.png)

When your workflow is executed go to the `File library`. A folder with all these files building your IMF package is available.

![workflow-imf-2](images/workflow-imf-2.png)

Click on the label `IMF` in `File library` :

![workflow-IMF-button](images/workflow-IMF-button.png)

window will be opened :  

![workflow-imf-3](images/workflow-imf-3.png)

Eolementhe creates a default video. Choose the audi and video file you want to create your  new version. 

![workflow-imf-4](images/workflow-imf-4.png)

Once your media version have been created, click on the envelope icon as below : 

![workflow-imf-6](images/workflow-imf-6.png)

You will be redirected to a workflow with `Cambria` transcoding ready to generate your file.


</details>

### My Workflows

<details>
  <summary><b>Structure of monitoring view.</b></summary>

  Click on `My Workflows` view.
  
  ![workflow-monitoring](images/workflow-monitoring.png)

The `My Workflows` view show all the workflows you have started. 

![workflow-monitoring-view](images/workflow-monitoring-view.png)

Different buttons can change the monitoring view. 

A button switch from the `My Workflow` view to the `My File` view. 

![workflow-monitoring-view-button-file](images/workflow-monitoring-view-button-file.png)

And the other button switch from the `Standard` view to `Premium` view. 
`Standard` view which corresponds to all workflows and files sent by the normal ingest. 
The `Premium` view that will show all the workflows and files sent by the premium ingest post (Premium mode use Signiant).

![workflow-monitoring-view-button-premium](images/workflow-monitoring-view-button-premium.png)

You can also filter your workflows list by date, file name, file status, etc... thanks to the two search bars. 

![workflow-monitoring-search-bar](images/workflow-monitoring-search-bar.png)

</details>



<details>
  <summary><b>Different state display in monitoring view.</b></summary>

In the file or workflow motoring the steps are categorized by color codes corresponding to states.

Here is an exhaustive list of the different possible statuses. 

![workflow-monitoring-running-task](images/workflow-monitoring-running-task.png)

**Running :** the task is in execution and processing please wait the end. 

![workflow-monitoring-refused-task](images/workflow-monitoring-refused-task.png)

**Refused :** the task was refused by the platform due to an unforeseen event or insufficient rights. 

![workflow-monitoring-pause-task](images/workflow-monitoring-pause-task.png)

**Paused :** If Pause block is encountered, platform wait for the user to validate or refused the pause. 

![workflow-monitoring-partial-task](images/workflow-monitoring-partial-task.png)

**Partial :** workflow had execute all tasks but some tasks have not been executed correctly.
 
![workflow-monitoring-completed-task](images/workflow-monitoring-completed-task.png)

**Completed :** workflow  is execute and deliver correctly. All tasks of the workflow were executed correctly. 

</details>


<details>
  <summary><b>Anatomie of workflow monitoring view.</b></summary>

In `My workflow` view you can unfold the details of your workflow by clicking on its name. 

![workflow-monitoring-unfold-workflow](images/workflow-monitoring-unfold-workflow.png)

Then we will be able to see two sub-menus. The first monitoring zone of the workflow and the second is the file zone.
As in the first step, unfold the two submenus.

![workflow-monitoring-view-zone](images/workflow-monitoring-view-zone.png)

Now you have the complete workflow monitoring view. You can have details of the progress of each tasks of your workflow executed. 

![workflow-monitoring-complete-view](images/workflow-monitoring-complete-view.png)

The name of the workflow used in list had specific name format like : 
Name of workflow - Start date of the workflow- Total size of all source and generated files.

![workflow-monitoring-workflow-title](images/workflow-monitoring-workflow-title.png)


At top of the workflow zone we can see the title of file ingest. And the progress and status of each task in your workflow, with the task information and the files generated by each task. 

![workflow-monitoring-workflow-zone](images/workflow-monitoring-workflow-zone.png)

The file zone  contains all the files in the workflow (sources files and generated files). It is also in this area that you will find all deletion informations for files of your workflow. 

![workflow-monitoring-file-zone](images/workflow-monitoring-file-zone.png)
</details>





<details>
  <summary><b>Anatomie of file monitoring view.</b></summary>

Click on `My files` button.

![workflow-monitoring-view-button-file-selected](images/workflow-monitoring-view-button-file-selected.png)


In the file monitoring view you  have details of the progress of each task on the source file.

![workflow-monitoring-file-file-zone](images/workflow-monitoring-file-file-zone.png)
  
In the file zone we can see the title of source file. And that show the progress and status of each task on your source file.
</details>



<details>
  <summary><b>How to purge file?</b></summary>
  

As specified in the  `My workflow` view, all files have a deletion deadline. Each file created is kept on the platform for 5 days before it is automatically deleted. 

![workflow-monitoring-workflow-purge-deadline](images/workflow-monitoring-workflow-purge-deadline.png)

In addition, many options in workflow monitoring allow you to delete files related to a workflow. 

**Purge all files** that purge all sources and generates files of your workflow.

**Purge source only** that purge all sources files of your workflow.

**Purge generated only** that purge all generates files of your workflow.

**Delete workflow** that remove all existence of the workflow on the platform ( delete : sources files, generates files and your workflow).

If you want to delete a specific file you can click on the trash icon of your target file in `My workflow` : 

![workflow-monitoring-delete-specific](images/workflow-monitoring-delete-specific.png)

</details>


### File Library

<details>
  <summary><b>Structure of file library view.</b></summary>

  Click on `File Library` menu.

![Library](images/library-menu.png)

In the `File Library` view you have all the files related to your account. To open a file in the library, simply click on the file in this section.
![library-view-file-tree](images/library-view-file-tree.png)    
You can search for a specific file or folder using the search bar. 

On hover this icon gives the information of the file: 

![library-icon-info](images/library-icon-info.png)

On hover this icon give quick view of the file: 

![library-icon-preview](images/library-icon-preview.png)

Source files are identifiable with the icon: 

![library-icon-source-file](images/library-icon-source-file.png)

Shared files are identifiable with the icon: 

![library-icon-share](images/library-icon-share.png)

When you select several files by checking them. An other menu appear just below.

![library-view-file-tree-selected](images/library-view-file-tree-selected.png)
In this menu perform additional actions. 
First, you can delete the selected files. 

![library-button-deleted](images/library-button-deleted.png)

You can also send the files to another folder. 

![library-button-move](images/library-button-move.png)

And finally you can directly start a workflow with the selected files. 

![library-button-launch](images/library-button-launch.png)


<hr>

When you open file by clicking on it, the preview look like this: 

![library-file-preview](images/library-file-preview.png)

At top you can see the file title followed by the number of days remaining before the automatic purge. 

![library-view-file-title](images/library-view-file-title.png)

Then just below there are two icons. The first one is used to download the file, and the other one is used to delete the file.

![library-view-file-icons](images/library-view-file-icons.png)

Below the two icons you can see labels. These labels are clikable an redirect you on the workflow that contain this file. 

![library-view-file-workflow](images/library-view-file-workflow.png)

If you find that the preview video of the File library is too small to work comfortably you can click on the icon below to enlarge the view :

 ![library-view-file-fullscreen](images/library-view-file-fullscreen.png)


A small keyboard icon is above the video player. When you hover with your mouse, you will see the keyboard shortcuts of the video player. 

![library-view-shortcut](images/library-view-shortcut.png)

Below the video player, there are the basics control buttons: `Back, Pause, Forward and take a screenshot`.

![library-view-button-player](images/library-view-button-player.png)

There is also a video playback speed control bar. 

![library-view-button-playbackspeed](images/library-view-button-playbackspeed.png)

On the left of the video player you have a space reserved for captures, information and video cutting : 

`Captures view` list and manage all the screenshots taken on this file. 
![library-view-panel-capture](images/library-view-panel-capture.png)


`Information view` lists all available informations about a media file. You can also add metadata or export them. 
![libray-view-panel-informations](images/libray-view-panel-informations.png)

`Trim view`  trim parts of the media file. 
![library-view-panel-trim](images/library-view-panel-trim.png)

</details>

<details>
  <summary><b>How to do capture on file?</b></summary>
  
Launch your video player. When you want to hang a capture press: 

![library-view-capture-button](images/library-view-capture-button.png)

In the menu `Captures`, the captures linked to the file are displayed and you can add a comment for your capture.

![library-view-capture-view](images/library-view-capture-view.png)

You can bring your video player to the frame of your capture by simply clicking on the timecode below the image.

 ![library-view-capture-timecode](images/library-view-capture-timecode.png)

You can delete a capture by clicking on the icon: 

![library-view-capture-supress](images/library-view-capture-supress.png)

Finally you can export all your captures in `pdf` or `csv` format with the following two buttons :

![library-view-capture-export](images/library-view-capture-export.png)

</details>

<details>
  <summary><b>How to get informations of a file?</b></summary>


In the tab `Information` you have the complete list of information about the file.  

  ![library-view-information-complete](images/library-view-information-complete.png)
  

You have access to the metadata of the file (if there are any) : 

![library-view-information-metadata-list](images/library-view-information-metadata-list.png)


You can export the information in `.pdf` format or add metadata to the file using these buttons : 

![library-view-information-button-export-add](images/library-view-information-button-export-add.png)


</details>
<details>
  <summary><b>How to trim a file?</b></summary>


In the `Trim` menu you can extract a part of the media file. 

Enter two timecode that delimit the trim of your video . 

![library-view-trim-1](images/library-view-trim-1.png)

The timecode fields are automatically set to the timecode of your video being played back. 

Then click on `Trim`. 

![library-view-trim-2](images/library-view-trim-2.png)

Wait a little while : 

![library-view-trim-3](images/library-view-trim-3.png)

Your file was created and named in the format `BaseName_trim_timecode1_timecode2` in your file Library.

![library-view-trim-4](images/library-view-trim-4.png)

</details>

<details>
  <summary><b>How to stitch files?</b></summary>


In `File Library`, select several files with the same extension.

![library-stitch-preview](images/library-stitch-preview.png)

Option button appear `Stitch files`. That allow you to stitch selected file as you want.

Click on `Stitch File`.
![library-button-stitch](images/library-button-stitch.png)

This will be displayed :
![library-stitch-1](images/library-stitch-1.png)

Add firstly a file by clicking on the icon: 

![library-button-stitch-add](images/library-button-stitch-add.png)

A view of your output file is displayed. Here you can see and modify the name of the output file.
And you can see the timeline of the new file that is going to be created by stitch.
![library-stitch-2](images/library-stitch-2.png)

Now let's add the second file. We can see on the timeline the white separation that marks the separation of our two files added.

![library-stitch-3](images/library-stitch-3.png)

You can reset your timeline by clicking on : 

![library-button-stitch-restart](images/library-button-stitch-restart.png)

Create the file by clicking on: 

![library-stitch-final-button](images/library-stitch-final-button.png)

</details>


<details>
  <summary><b>Structure of subtitle editing view.</b></summary>


Click on `File Library` menu.

  ![Library](images/library-menu.png)

Click on an `SRT` file.

![library-view-structure-1](images/library-view-structure-1.png)

If your view library does not include timecode and other informations as above, you are in simplified view. You will just have to click on the button like below for complete view : 

![library-view-subtitle](images/library-view-subtitle.png)

The current captions of subtitle is displayed as follows.

![library-view-structure-2](images/library-view-structure-2.png)

If you click on the character limits a pop-up open allowing you to change the limits for all the file.

![library-view-structure-3](images/library-view-structure-3.png)

If you change the limit but some captions have more words per second than your limit they will appear in red like this : 
![library-view-structure-11](images/library-view-structure-11.png)

If you want to make your video player go on a particular caption, just click on the subtitles caption timecode surrounded in red below :

![library-view-structure-4](images/library-view-structure-4.png)

If you want to change the timecode you just have to click on the icon next to the timecode to change it (surrounded in red below) .

![library-view-structure-5](images/library-view-structure-5.png)

Clicking on vertical arrow icons bellow advance or reverse your caption by 100 milliseconds. 

![library-view-structure-6](images/library-view-structure-6.png)

You can delete a subtitles caption by clicking on the icon surrounded in red below.

![library-view-structure-7](images/library-view-structure-7.png)

You can add a caption by clicking on the icon surrounded in red below (the subtitles captions are added underneath the current)

![library-view-structure-8](images/library-view-structure-8.png)

By clicking on icons bellow you could advance or reverse by 100 milliseconds all subtitles captions of your file. 

![library-view-structure-9](images/library-view-structure-9.png)

When you have finished working on your subtitle, don't forget to save with the following button: 

![library-view-structure-10](images/library-view-structure-10.png)

</details>

<details>
  <summary><b>How to open the subtitle editing view?</b></summary>


Click on `File Library` menu.

  ![Library](images/library-menu.png)

  Click on an `SRT` file.
  
  Only subtitles with `.srt` extension will show the subtitle editing interface.

  ![Subtitle editing](images/library-subtitle-editing.png)

If your view library does not include timecode and other informations as above, you are in simplified view. You will just have to click on the button below for complete view : 

![library-view-subtitle](images/library-view-subtitle.png)
</details>


<details>
  <summary><b>How to open subtitle editing side-by-side?</b></summary>
  

Click on `File Library` menu.

  ![Library](images/library-menu.png)

  Click on an `SRT` file.
  
  Only subtitles with .srt extension will show the subtitle editing interface.
  

</details>


<details>
  <summary><b>How to contact an other user on platform?</b></summary>
  
On Eolementhe you can contact other user and talk to them. This messaging system are per file. Each file has its own messaging system and allows different users working on the same file to communicate.

  Click on `File Library` menu and open your media file.

  ![Library](images/library-menu.png)


To open the conversation of file click on the icon indicated by the red arrows at the bottom right on the image below. 

![workflow-library-chat](images/workflow-library-chat.png)

And now communicate simply.

![workflow-library-chat-example](images/workflow-library-chat-example.png)

</details>


### Dashboard

<details>
  <summary><b>How to use dashboard effectively?</b>     
  </summary>


Click on `Dashboard` menu.  

![dashboard-header](images/dashboard-header.png)

In the Dashboard view you can see all sources files with all tasks proceed by workflow in detail. 
The advantage of the dashboard is that there are many filter to apply.

You will have something like this: 

![dashboard-complete-view](images/dashboard-complete-view.png)

The select at top allows you to add or remove rows from the table. In order to customize your dashboard. 

![dashboard-select-filter](images/dashboard-select-filter.png)

Just below the first select, you can select your custom period : 

![dashboard-period-select-filter](images/dashboard-period-select-filter.png)

You can also change the way the rows of your table are ordered by clicking on the icon next to the name of the column you want to order : 

![dashboard-icon-ordered](images/dashboard-icon-ordered.png)

If you click on a file raw that redirect you on `File library` on the file you clicked : 

![dashboard-click-raw](images/dashboard-click-raw.png)


We also have labels in the State column corresponding to the workflow that was launched on the file. By clicking on this label the platform will redirect you to the `My Workflow` view monitoring on the clicked workflow. 

![dashboard-status-label](images/dashboard-status-label.png)
</details>


### Analytics

<details>
  <summary><b>How to use analytics effectively?</b>     </summary>

  Click on `Analytics` menu.  
  

![analytics-header](images/analytics-header.png)


Analytics allow to have a follow-up of the activity of user over a given period.

![analytics-view-complete](images/analytics-view-complete.png)

 Enter email of the user in filed and press ` Enter` and select a period.

![analytics-interface-view](images/analytics-interface-view.png)

The list of selected emails is displayed. You can export the report as a `PDF` or `CSV` file with export buttons. 

Below example of one schema of the activity report.

![analytics-graphic](images/analytics-graphic.png)

</details>

### Account


<details>
  <summary><b>How to more secure my account?</b></summary>

  
  Click on your login at at the top right of Eolementhe. 
  Click on `Enable 2FA`.

![dropdown-manage-2FA](images/dropdown-manage-2FA.png)

After a modal will ask you: 

![2FA-modal](images/2FA-modal.png)

If you click on `yes` then you will activate the 2FA. 

If you active it next login on the platform you will be asked this: 

![2FA-login](images/2FA-login.png)
Code received on the email address of your Eolementhe account. 

</details>


<details>
  <summary><b>How to activate or disable notification?</b></summary>


  Eolementhe can send notifications to your browser.
  
Click on your login at at the top right of Eolementhe. 
If disabled click on `Activate notification`.

![dropdown-manage-notification](images/dropdown-manage-notification.png)

If activated click on `Disable notification`.

![dropdown-manage-notification-disab](images/dropdown-manage-notification-disab.png)

</details>


<details>
  <summary><b>How to see my team?</b></summary>


  Click on your login at at the top right of Eolementhe. 
  Click on `Teams`.

![dropdown-manage-team](images/dropdown-manage-team.png)

If a team exists it will be displayed like this.

![team-view](images/team-view.png)

  After that, just click on it to get all the information (if you are a simple user you can only see your team manager. Only manager can see all users of a team).
![team-complete-view](images/team-complete-view.png)

</details>


