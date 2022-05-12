# eztoo
An easy ec2 ssh / rsync script thing to create an ec2 and sync files fast to a cloud box

Main goals yet are:
Getting the startup script to shutdown the box after a default time limit (like 1 hour) as a safety net. (with flag to disable for long runs if you have something that needs to run for a long time).
Rsync using the current dir of wherever you are.
Recycle / re-use the last used box? Potentially. (Re-use the same ec2, not a new box every time [faster boot])
Potentially allow a docker image? So the ec2 would start a docker image, and you would ssh immediately into the docker image environment
