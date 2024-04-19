
## Notes/thoughts after using with prolific platform.

- Ensure the background check for expired tasks is often or else it’ll only expire after the designated time not when task actually expires.
- “returned” prolific tasks DO NOT return allocated tasks to waiting tasks. This means prolific could try to recruit more participants before the allocated tasks have timed out. Those participants will be shown the “no tasks available” prompt.

- It is recommended to monitor the study whilst using the prolific flask app. The /abdn route is also handy as it will manually run the timed out check against the database. You can also look at the allocated tasks at /allocatedtasks - it is in json and a little hard to read but ctrl f will be your friend. Do keep in mind browsers may cache the response.
