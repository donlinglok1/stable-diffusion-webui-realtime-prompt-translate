# Realtime Prompt Translate for sd-webui

This script is made to be used with the [AUTOMATIC1111 webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui).

## Installation
1. Drop the `realtime_translate.py` into `stable-diffusion-webui/scripts` folder.
2. Drop the `realtime_translate.js` into `stable-diffusion-webui/javascript` folder.
3. Restart the sd-webui, the translating panel will show at the bottom.
![image](https://user-images.githubusercontent.com/6138806/197687618-ce757498-9d5e-418d-bd97-4a0a93e8a5ff.png)

If you're using a Google Colab, you can add this in a code block before the one that starts the webui :
```
!wget https://raw.githubusercontent.com/donlinglok/realtime-prompt-translate-for-sd-webui/main/realtime_translate.py -O /content/stable-diffusion-webui/scripts/realtime_translate.py
!wget https://raw.githubusercontent.com/donlinglok/realtime-prompt-translate-for-sd-webui/main/realtime_translate.js -O /content/stable-diffusion-webui/javascript/realtime_translate.js
```
## Features
### Translate
1. Click the `Translate` button and wait for the loading
2. After loading, input your prompt, and the translated text will show at the top of the sd-webui.
3. 
![image](https://user-images.githubusercontent.com/6138806/197688223-0f38a845-5b99-4293-bfd3-cacb5f6712ed.png)

### Reversed Translate
1. Click the `Reversed Translate` button and wait for the loading.
2. After loading finish, input your prompt on the top of the sd-webui, your prompt will reverse translate to the English prompt box.

![image](https://user-images.githubusercontent.com/6138806/197688135-6a500f70-077c-4845-8c01-98d9da2a6d7a.png)

## Example
### Translate
(651KB GIFs)
![ezgif-1-fe2a5dd0f1](https://user-images.githubusercontent.com/6138806/196651954-4a3b56fd-d461-4ea8-97ec-16a2efc3279d.gif)

### Reversed Translate
(823KB GIFs)
![ezgif-5-2ffddd21eb](https://user-images.githubusercontent.com/6138806/196863977-25e8347e-23bd-4ede-89ff-60b6f705a178.gif)

## Refrences
https://github.com/AUTOMATIC1111/stable-diffusion-webui/pull/3134

https://stackoverflow.com/questions/17654458/how-to-make-an-reset-button-for-google-translate

https://github.com/Extraltodeus/advanced-loopback-for-sd-webui/blob/main/README.md

