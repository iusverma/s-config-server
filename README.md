Purpose: I tried to use multiple profile to see, if we can search for config in local as well as git repo as the same time. 

Result: No matter what we try, native always overrides default profile. Plus if there is any other profile last profile in the line will override every thing.

Example: spring.profiles.active: native,dev,uat -> Then only uat profile will be applicable and active.
