# DnA Project Submission
## PROJECT - ***IIITVR***

> **TEAM - 1**
> 
> Team Members:
> - Bhav Beri (2021111013)
> - Harshit Aggarwal (2021111015)
> - Sreyas S (2021111016)

----

## FUNCTIONS IN MAIN FILE (WITH SMALL DESCRIPTION ABOUT THEM)
### ADMIN FUNCTIONS
- `raw_sql`: Used to give power to admin to execute raw sql commands on the database

### USER FUNCTIONS
- `new_user`: To create a new user.
- `show_plan`: To show all the available plans
- `change_plan`: To update the plan of user.
- `send_chat`: To send a message to another user.
- `show_chats`: To show all chats received by user
- `new_issue`: To create a new issue
- `show_user_issues`: To show all the user created issues with their ids
- `meta_reality`: To start the meta-reality device (Assumed)
- `delete_user`: To remove a user

### EMPLOYEE FUNCTIONS
- `show_plan`: To show all the available plans
- `update_plan`: To update a specific plan
- `users_with_issues`: To show list of different users with pending issues
- `resolve_issue`: To mark a issue as Resolved
- `premium_users`: To show all the premium users (Users with plans above Avg of all plans)
- `user_high_low_plan`: To show a list of users with the highest plan (Priority Customers) & a list of users with no current plan (To remind them to take plan)
- `users_per_plans`: To show number of users per each plan, for making different plans better
- `old_new_user`: To show the most recent and the oldest active customers
- `users_after_months`: To get the number of Users joined within last n months.
- `no_msg_user`: Details of the users having no message since last 3 months (Customer Retention)