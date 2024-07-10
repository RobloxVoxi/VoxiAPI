# Voxi API


> [!CAUTION]
> The only official place to download VoxiAPI are this GitHub repository. Any other websites offering downloads or claiming to be us are not controlled by us.


 ## Installing The API

API ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/Voxi-API.dll (Click View Raw to download)
INJECTOR  ---> 
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
This opens in the background (No console pops up via VoxiAPI, we will get onto idenfitiny when injected later in this page.

### Execute
```
> VoxiAPI.Voxi.Execute(X,true)
```
X = Your input box, eg i have a form with 2 buttons and a rich text box it would be: VoxiAPI.Voxi.Execute(RichTextBox1,true)  

### Close Roblox:
```
> VoxiAPI.Voxi.CloseRoblox();
```
This closes roblox instantly. Idk why u need this but.


## Injection Status;
```
> VoxiAPI.Voxi.Injectstatus();  
```
This returns either TRUE or FALSE.
