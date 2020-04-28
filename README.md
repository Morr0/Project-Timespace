# Project Timespace

This is a new methodology of time division into a pie. Where each time-block(month, week, day) is represented as a pie chat. Pie slices represent the task-regions(a region maybe allocated for study, work, free time, etc...). Each time-region is user allocated. A time-region's type is user-defined, i.e. if the user wants the time to be optional or buffer he can allocate as many as possible for each region. 

Within the time region, an allocation is the actual task. Every hierarchy is considered to be an entity, each entity is to have name, notes, timings, notifcation-ability, trackables(for statistics i.e. how many hours a week were spent on X task within).

Have the concept of forceables(ForcedEntity) where it must have information reported to by due date so that after that due date it is not possible to access/modify the time system but to log what is required by the forceable and then be able to access/modify the timetable. e.g. The forceable is a review of the day/week/month where it asks about how many hours spent doing work.

All data gathered is to be used to graph actual performance vs expected performance and any other statistical need.

Have the concept of work hours as a template the user defines to workout his timetable.

Ability to print off pie charts of a given time-block and weekly/daily timetable format.

PWA

### Possible Implementation:

    - Use of localStorage api
    -MongoDB lite or any NoSQL means of storing data lightly

### Possible additions:
    - Cloud data storage so that it can be accessed/modified from elsewhere 
    - Emergency plan (plan B, potentially C) 
    - Day designer system(simple AI) based on budget of time 
    - Suggester over-time(based on machine learning and basic AI)
    - Integration with calender APIs
    