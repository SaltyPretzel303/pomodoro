# pomodoro
Simple pomodoro cli app.

`pomodoro work` to start work session.  
`pomodoro pause` to save previous work session and start pause session.  
`pomodoro flip` to switch to work or pause (work -> pause, pause -> pause)
`pomodoro stats [-l num]` to show sum of work sessions of previous `num` days (if specified, default is 3).  
`pomodoro today` to show summary of todays work sessions. 
`pomodoro monitor` prints string sutable for xfce4 generic monitor in format: pause|work: [+]minutes.seconds mins
