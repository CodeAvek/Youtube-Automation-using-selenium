# Youtube-Automation-using-selenium
We Will Make Youtube Automation And Run 3 videos for 5 time with Random Time....

## CodeAx

 - [Telegram](https://t.me/avekgaming)
 - [instagram](https://instagram.com/codeax1?utm_medium=copy_link)
 - [Youtube](https://youtube.com/channel/UC-Q6ZcOtcx1gZ9fI5MDDt3w)


## important to check

- check your chrome version and download chromedriver
- install Any Code Editor
- Make Folder And Add Chromedriver into it
-  install python open cmd  install selenium  using - pip install selenium
- Written by CodeAx



## Deployment

```bash
#First You Have to Downlaod AnyEditor To Run Python Code
#So First Go to your chrome check your chrome Version 
#And Donwlaod chromedriver accourding to your chrome version...Just Search On google Chromedriver
#Now MAke New Folder And Add On It And Now MAke Test.py file And Start Your Journey In Automation
#Open CMD terminal And Install - pip install selenium
###########AvekGaming-CodeAx1############

from selenium import webdriver #Importand module
import time  #for Waiting on Video And Watching
import random    #For Random Minute to Watch Video

driver = webdriver.Chrome(executable_path="chromedriver.exe") #we have chromedrive.exe in our folder Nice


for i in range(5):  #We Will Watch Our Video Again Again for five time According to you
    sleep_time = random.randint(10,15)   #we maked a variable which contain time with random second
    print("video is running for {} time".format(i))  #it will say how many time we have played video
    driver.get("https://www.youtube.com/watch?v=wEYJXPdzbgw") #1st Video  -You Can Add Your youtube Link
    time.sleep(sleep_time)  
    print(driver.title)
    driver.get("https://www.youtube.com/watch?v=Y-VwsmMRjFU") #second video -You Can Add Your youtube Link
    print(driver.title)
    time.sleep(sleep_time)
    driver.get("https://www.youtube.com/watch?v=xXxnMH7d7Pg")  #3rd video  - You Can Add Your youtube Link
    print(driver.title)
    time.sleep(sleep_time)
driver.quit()
```

Watch Our ScreenShot And Make Your Work Easy.....
From Starting to Ending----

![Screenshot (4)](https://user-images.githubusercontent.com/95927683/150201587-c9ed4572-07a1-42d7-8c9b-61105387ebed.png)

![Screenshot 2022-01-20 011616d](https://user-images.githubusercontent.com/95927683/150202965-02bede24-32e5-4621-841e-c0b9798caa93.png)

![Screenshot 2022-01-20 003658](https://user-images.githubusercontent.com/95927683/150202019-d645a132-3044-4b9f-a2a5-e79c87186661.png)

