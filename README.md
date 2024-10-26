Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

For the project of CS 360, the idea was to develop an android app based on a list of requirements, the app I chose to develop (from a given list of 3 options) was a weight tracking app, 
the features requested were the ability to log in, add or remove entries of data (data would me a pair of date and weight), and allow or deny SMS notifications. The "user" needs are an app to
track entries of weight data for the purpose of monitoring their health or potentially losing weight (and tracking their progress).

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

I created three screens, one for logging in, one to view data/enter data/remove data, and finally one last one to manage settings (in this project the only setting developed was the SMS permissions).

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

There was a process used across the projects done in the course (all building upon one another to result in the final project seen in this repository) where first development started by analyzing the 
requirements and writing out a plan, then designing the visuals of the app (UI) and then finally developing the code to make the app functional. This process actually helped quite a bit to keep me organized
so I'll likely be using it in the future unless I find a way that works better for me.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested repeatedly during development, every time I made a change I tested it to find out what was going wrong. Needless to say there were a large amount of errors during development that I fixed. For example
there was a point where logging in would always result in the same account data (weight/date records) so I fixed that one pretty quick. Other than that there were plenty of errors where I used logCat and
looked up the error online to see how other people handles it if it was an error I didn't really understand (there's no reason to reinvent the wheel, ya know?).

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

I don't know how much I exactly "innovated", but there were a few times where I just stared at what I was doing and testing it repeatedly with different changes because the UI on one part just didn't want
to work no matter how I changed it in ways I thought would work. The error I'm referring to is the scrollPane I used for the data grid, when scrolling to the bottom there was an error where you couldn't see
the last entry fully (but could see just a tiny sliver of the top of it), I tried so many things and eventually it worked (you know that one comic panel where it's a guy saying "Random bullshit go!"? That 
was basically me being frustrated at my UI not working).

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

There's just a really small detail that (having previously mainly done javaFX app dev) I think was really really cool to implement properly. So, when you delete or add data it shows up with the updated 
information instantly (I know that sounds silly but in java that just wasn't a thing I could do reasonably without it being extremely taxing on the system). I just think it's cool that that's a thing I can do
now.
