# Azure-Siem
created resource group<br>
![create resource group](https://user-images.githubusercontent.com/105601437/206636602-3f152094-9e4f-4c0d-a5f2-b23de7fdc469.png)


configured virtual machine
<br>
![create virtualmachine](https://user-images.githubusercontent.com/105601437/206637643-adda2366-043c-4d43-bd97-fe1737a22a26.png)
<br>
Configured Network Firewall Protocols to allow all inbound traffic
<br>
![securitygroup](https://user-images.githubusercontent.com/105601437/206639392-3759d746-800d-453e-98de-88cc207e8f57.png)
<br>
Deployment of the VirtualMachine
<br>
![deployment](https://user-images.githubusercontent.com/105601437/206640224-62771bcc-9cd6-4e84-bd0b-763aa3654c66.png)
<br>
Created Log Analytics WorkSpace
<br>
![loganalytics](https://user-images.githubusercontent.com/105601437/206645890-ed3fe25a-b15f-4a6e-b621-5b83e5ae5519.png)
<br>
From here we go to the Windows Defender for Cloud and enable windows defender on our virtual machine.
<br>
![defenderenabled2](https://user-images.githubusercontent.com/105601437/206648169-f679f8ba-b6b4-43f8-9c58-214a4589a641.png)
<br>
After upgrading from free Security Center to the upgraded version we are able to enable datacollection of all event logs on our Virtual Machine
<br>
![datacollection](https://user-images.githubusercontent.com/105601437/206828568-174993f6-e0ca-4f45-9d29-0c26bfc85c7a.png)
<br>
![create Azure sentinel](https://user-images.githubusercontent.com/105601437/206828743-54743869-a642-4067-895c-c26543f671d9.png)
<br>
![signing intovm](https://user-images.githubusercontent.com/105601437/206829911-697ed8a3-3353-4cfb-8e69-27fbd62c26e8.png)
<br>
![audit failure](https://user-images.githubusercontent.com/105601437/206829957-fc91a68a-314b-4da9-b75c-21a6722ab2ac.png)
<br>
Whoops my Firewall slipped
<br>
![superunsafe](https://user-images.githubusercontent.com/105601437/206830205-c5c4ceee-7af0-441b-a098-801780ad6b5d.png)
<br>
Using this ip exporter code found on github I am able to take all failed login and attempts extract them from windows event logs and pinpoint locations on the map
<br>
![ipexporter](https://user-images.githubusercontent.com/105601437/206830588-850be65b-aeae-4cb9-bc53-9cad58499592.png)
<br>
![create custom log](https://user-images.githubusercontent.com/105601437/206830964-a77fb4d1-d82f-4016-bcb2-3d562ab46193.png)
<br>
![customlog2](https://user-images.githubusercontent.com/105601437/206831023-9ca0796a-4bbe-4a6b-89e3-37ede1ed5f50.png)
<br>
![underattack](https://user-images.githubusercontent.com/105601437/206831329-a99f8586-8cf9-4064-ae13-c8f484684677.png)
<br>
![raw datainbound](https://user-images.githubusercontent.com/105601437/206831892-10ba3ecd-9219-42b6-a7dc-ad87da3a11bb.png)
<br>
![highlight interesting values](https://user-images.githubusercontent.com/105601437/207255705-4351ad0b-12e9-46ae-af67-f8eefe2b2641.png)
<br>
![customfields](https://user-images.githubusercontent.com/105601437/207254654-19bb6864-8516-44fd-b522-c3c842a4af94.png)
<br>
![data](https://user-images.githubusercontent.com/105601437/207260821-f523dff5-d07d-4135-960d-9057f8f19c6e.png)



