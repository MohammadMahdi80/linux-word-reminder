# linux-word-reminder
bash script for word reminder and help to learning english.

## Why use it:
* Review words that read in every day causes learn this word easily and over time.
* In addition to develop your reading skill, develop your listening skill by listening voice of word in google translate and learn correct pronunciation.

## How to use:
* Every Time that enter a word in google translate, star it:
> ![image](https://user-images.githubusercontent.com/82968741/211553277-1cc6396f-f397-48bf-8004-2e7ad15256dc.png)


* go to saved section and then click on `Export to google sheets`:
>![image](https://user-images.githubusercontent.com/82968741/211554064-37529aef-d462-4937-a5b2-86d1d3efed83.png)


* click on `import the data` and then copy `C` and `D` column:
>![image](https://user-images.githubusercontent.com/82968741/211554581-7e64992b-13df-4d3e-9905-29c5b7cdb88f.png)


* paste data to a file located in `dic-notif` directory.

* run script:
>```
>$ sh dic-notif
>```

![image](https://user-images.githubusercontent.com/82968741/211560245-4f42888c-684a-4913-9e67-0d40a81cff70.png)


* you can change icon of notifications in script:
```
notify-send -u critical -i /"your path"/icon.ico "$english" "<a href=\"$link\"> $persian </a>"
```

* determine period of notifications:
```
sleep 5m
```



