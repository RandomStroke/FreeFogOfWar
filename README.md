##################

![fow_pr_2](https://user-images.githubusercontent.com/36265375/142424832-5b2e9567-e71b-4a9b-9910-aba0e6bd8da1.gif)
![fow2_1](https://user-images.githubusercontent.com/36265375/143087617-ca1edc58-aae9-470b-a8c6-956e4d2e12c2.gif)

Эффект тумана войны для Unity ( должен работать на любой версии ). Не использует какой-либо функционал URP или HDR пайплайна , реализован в виде пост эффекта.
Работает на бюджетных мобильных устройствах ( тестировался на INOI 2 2021 )
В пэкедже 2 сцены со всеми необходимыми ресурсами.

StaticFog : демонстрация использования параметров для получения одной "глобальной" маски
![fow_2](https://user-images.githubusercontent.com/36265375/142426116-2f90ec50-961f-446d-aeaa-280825a6566f.gif)
![fow_3](https://user-images.githubusercontent.com/36265375/142426153-fd0a06f8-d485-4e19-859e-6d69f5bac88e.gif)
![fow_4](https://user-images.githubusercontent.com/36265375/142426167-9f1919dc-a151-4aa6-bc65-3e7571062dc5.gif)
![fow_5](https://user-images.githubusercontent.com/36265375/142426177-7354c304-1168-4e49-9233-9706af24e2e1.gif)

DynamicFog : демонстрация использования RenderTexture для создания управляемых ( динамических ) масок.

##################

Fog of war post effect made for Unity ( must work on any version ). Doesn't use any advanced URP and HDR stuff, just the most basic implementation.
Also works on cheap mobiles ( tested on INOI 2 2021 )
Package contains 2 scenes with all realted resources. 
StaticFog : showcases a simple usage of a parametric "global" mask for the whole screen.
DynamicFog : showcases a simple usage of a dynamic masks that can be controlled in a run-time.
