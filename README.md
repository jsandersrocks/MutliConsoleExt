# MutliConsoleExt
Open command prompt window to every single instance hosting your Azure WebApp and run commands targeting any one of those instances

This can be especially helpful if you notice one of the instances is behaving differently than the others and you would like to get a better view of whats happening on that specific instance.
You may run all the commands that you can run via Kudu.

<h2>Installation Instructions</h2>
<h3> 1. Download Publish Profile </h3> 
a.  From the Azure Portal, navigate to the Overview section of your app and download the publish portal from there by selecting ‘Get publish profile’ (make a note of where it downloads to so you can find it later:
<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227101743150.png' />
<br/>
<h3> 2. Install Instance Explorer </h3>
a. Open you site’s Kudu page (https://<yourappname>.scm.azurewebsites.net) and select the ‘Site extensions’ section.  Click on the ‘Gallery’ tab then enter ‘Instance Detective’ in the search box and click on the ‘Search’ button.
<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227101021493.png' />
<br/>
        
b. Click the ‘+’ icon to install the extension.  When it is done installing it tells you to ‘Restart Site’ so hit the ‘Restart Site’ button so you can use this:
<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227095408213.png' />
<br/>
     

c.  From this (or the Installed tab) you can hit the Run Icon to start the extension.  The first time you run it, you need to supply the Publish Profile as pictured below.
<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227095457337.png' />
<br/>
     

d.  Press the ‘Upload Publish Profile’ button and navigate to the publish profile you downloaded in step 1.
Use the Extension!
Now the extension is loaded and you can connect to and perform various operations on the individual instances:
<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227095533576.png' />
<br/>
     

<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227095544621.png' />
<br/>
     

<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227102322857.png' />
<br/>
     

<h3>When finished you can uninstall the Extension</h3>
Simply go back to the Installed Site extensions section and click on the ‘x’ icon to remove the extension:
<br/>
<img src='https://msdnshared.blob.core.windows.net/media/2018/02/capture20180227102557607.png' />
<br/>
     
