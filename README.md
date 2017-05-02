# SimpleDayLogger
SimpleDayLogger (ever!) is a very simple tool for windows platform to log your activities at work.


If you are using Scrum or other agile frameworks at work to develop software. You may have been noticed that some times you do not remember what to say in daily meetings! 

This tool can be used with windows run window (Win+R) to log your daily activities as very simple single-line snippets.

## What is it?

__SimpleDayLogger__ consists of two very simple batch file and a text file that is used as container for log snippets

__log.bat__: Records the log snippet

__viewlog.bat__: Helps you to view the log entries

__log.txt__: logs container


## How to install 

Installing the logger is very simple. Just copy the bat files and the text file from the `Src` folder of repository and past them where ever you want! 

After the copy has been successful. Place batch files in windows path. By putting the batch files to windows path you will be able to use them globally. [Check here](https://superuser.com/questions/949560/how-do-i-set-system-environment-variables-in-windows-10)



## How to record a log

Press Win+R (Windows run window) and type the following

`log "you log snippet"`

For example: `log "hello world!"`


## How to view logs

Press Win+R (Windows run window) and type the following (Remember that you need to put viewlog.bat file in the path environment variable)

`viewlogs`


Enjoy the simplicity! 

