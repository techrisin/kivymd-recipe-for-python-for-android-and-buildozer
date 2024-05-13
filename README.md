# Kivymd recipe for python for android and buildozer
This recipe is created since we faced difficulty in adding the kindmd as one of the requirements in python for android and buildozer. 

This recipe will download the latest zip file for kivymd. As of 13/05/2024, the kivymd version is 1.2.0 in https://pypi.org. So, if you plainly give kivymd as one of the requirements in building the android app, you will get errors during function calls as the kivyMD underwent major changes in latest release. 

This also has a patch to resolve the copying of kv files. 

We have also built a app with this recipe applied based on the sample code available in kivyMD to demonstrate this recipe

The app can be downloaded from [https://drive.google.com/file/d/1JdDel9pDB5ieAT8w4Af6xD2aue0d4W8P/view?usp=sharing](https://drive.google.com/file/d/1JdDel9pDB5ieAT8w4Af6xD2aue0d4W8P/view?usp=sharing)

Do the following for the recipe to work 

1. copy the folder kivymd to the recipies folder by executing the command "cp -r kivymd ~/home/gk/.local/lib/python<version number>/site-packages/pythonforandroid/recipes/" . replace the version with the version number in your system 
2. add the requirement kivymd in your build command or buildozer.spec file

## Do you need help in python based android app development 
Feel free to contact us st [https://techris.in/contact-us/](https://techris.in/contact-us/)
