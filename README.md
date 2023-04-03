# CartoonFaceGeneration
You can finish the cartoon face generation task and see the results of comparative experiments through the following link: https://colab.research.google.com/drive/1cHgjtI5BYWlYIUDiDMcmEAQgxRQt1OdL#scrollTo=zS9sjPRGsvzc

When you get generated cartoon face images from steps above, you can realize text-guided image manipulation through the following link: 
https://replicate.com/orpatashnik/styleclip
You can use the generated cartoon face image as the input, and import a line of text instruction for the image manipulation process. For example, if you want to change a woman's hair color into purple, you just need to insert "a woman with purple hair".

You can download the pretrained models through the following links.

"ffhq256.pt" : "https://drive.google.com/uc?id=1PQutd-JboOCOZqmd95XWxWrO8gGEvRcO",
"encoder_ffhq.pt" : "https://drive.google.com/uc?id=1QQuZGtHgD24Dn5E21Z2Ik25EPng58MoU",

"Disney.pt" : "https://drive.google.com/uc?id=1z51gxECweWXqSYQxZJaHOJ4TtjUDGLxA",
"Disney_FreezeSG.pt" : "https://drive.google.com/uc?id=1PJaNozfJYyQ1ChfZiU2RwJqGlOurgKl7",
"Disney_LS.pt" : "https://drive.google.com/uc?id=1PILW-H4Q0W8S22TO4auln1Wgz8cyroH6",
    
"Metface_FreezeSG.pt" : "https://drive.google.com/uc?id=1P5T6DL3Cl8T74HqYE0rCBQxcq15cipuw",
"Metface_LS.pt" : "https://drive.google.com/uc?id=1P65UldIHd2QfBu88dYdo1SbGjcDaq1YL",

We use StyleGAN2-FFHQ pre-trained model in the following link: https://github.com/NVlabs/stylegan2.
We train the model use datasets Disney and MetFaces in the following links: https://github.com/justinpinkney/toonify; https://github.com/NVlabs/metfaces-dataset.

