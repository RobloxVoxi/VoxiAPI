# <img src="https://github.com/pizzaboxer/bloxstrap/raw/main/Images/Bloxstrap.png" width="48"/> Bloxstrap


> [!CAUTION]
> The only official place to download VoxiAPI are this GitHub repository. Any other websites offering downloads or claiming to be us are not controlled by us. Please note this API is diffrent from Voxi Paid API. This API is skidded af i mean its free what do u expect. The bin folder is 100000% skidded ty celery.


 ## Installing The API

> API ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/Voxi-API.dll


> INJECTOR  ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/VoxiInject.exe

> BIN  ---> https://github.com/RobloxVoxi/VoxiAPI/blob/main/CeleryIn.bin

(Click View Raw to download)

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
This opens in the background (No console pops up via VoxiAPI) A Message Box will apear as shown below:

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
