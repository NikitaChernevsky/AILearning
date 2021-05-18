# AILearning
Solution pack for mobile app AI Learning

To install app in your Microsoft 365 tenant 
PREPARE:
- Register Azure account (you can use free trial)
- Create Azure Custom Vision Service and Computer Vision
- Create Project in Azure Custom Vision (https://customvision.ai) (for trash categorization)
- Upload photos of trash to Custom Vision Project and setup 4 tags
- Create free Bing Maps account
INSTALL:
- Go to https://make.powerapps.com 
- Import AILearning_currentversionnumber.zip from this repository
- Setup connectors during the import (to Azure services from step PREPARE and Translator service)
- Go to PowerApps Studio, open Natural Science screen and for button Check set Project ID and Iteration ID from Project in Azure Custom Vision
- Save your PowerApps app, publish it and now you are ready to use

If any questions - you can contact me by nikita@chernevsky.ru 
