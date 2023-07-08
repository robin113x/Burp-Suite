
1 - Run BurpLoader

--> java -jar burploader.jar

--> If any error > open CMD and enter this

          rd /s /q "%userprofile%\AppData\Roaming\BurpSuite\"

          reg delete "HKEY_CURRENT_USER\SOFTWARE\JavaSoft\Prefs\burp" /f