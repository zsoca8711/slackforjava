# slackforjava
My objective is to create a Log4j appender which can send notification to slack channels. Aiming to have it highly configurable. 
I also want to make the underlying API integration available in this library, so the user can actually use my code without log4j.

# Objectives

* Log4j Appender
* Static, congfigurable API wrapper
* Sync API wrapper
* Async API wrapper - configurable retries

# Depedencies

* Jersey Client
* Log4j (latest version - it is almost 4 years old now, i suppose it is fine)