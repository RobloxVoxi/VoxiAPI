## <img src="https://raw.githubusercontent.com/RobloxVoxi/VoxiAPI/main/voxilogo.png" width="60"/> API


> [!CAUTION]
> The only official place to download VoxiAPI are this GitHub repository. Any other websites offering downloads or claiming to be us are not controlled by us. Please note this API is diffrent from Voxi Paid API. This API is skidded af i mean its free what do u expect. The bin folder is 100000% skidded ty celery.


 ## Installing The API

> API ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/Voxi-API.dll


> INJECTOR  ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/VoxiInject.exe

> BIN  ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/CeleryIn.bin

(Click View Raw to download)

In your [Debug folder](https://github.com/RobloxVoxi/VoxiAPI/blob/main/image_2024-07-11_002919879.png?raw=true)(To open Solution Explorer in Visual Studio, click on 'View' at the top of your screen, then select 'Solution Explorer'. Right-click on your project name and choose 'Open Folder in File Explorer') of your exploit paste these 3 files as shown below: 
<img src="https://raw.githubusercontent.com/RobloxVoxi/VoxiAPI/main/image_2024-07-11_001711541.png" />

## Starting The API
At the top of your CS file do:
```
> using VoxiAPI;
```
## Using The API
### Inject:
```
> VoxiAPI.Voxi.Inject(); 
```
This operation occurs silently (no console appears via VoxiAPI). A message box will appear to alert the user of injection success or failure.

### Execute
```
> VoxiAPI.Voxi.Execute(X,true)
```
X = Your input box, eg i have a form with 2 buttons and a rich text box it would be: VoxiAPI.Voxi.Execute(RichTextBox1,true)  

### Close Roblox:
```
> VoxiAPI.Voxi.CloseRoblox();
```
This closes roblox instantly, Killing all instances of roblox quickly.

## Injection Status;
```
> VoxiAPI.Voxi.Injectstatus();  
```
This returns either TRUE or FALSE.
