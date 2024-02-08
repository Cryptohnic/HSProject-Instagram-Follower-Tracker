# Instagram-Follower-Tracker
Python program that will track Instagram followers telling you when someone follows or unfollows.

THIS IS MADE FOR UNIX ONLY
This program is used to see the names of accounts who have followed and who have unfollowed Instagram accounts recently.
The module that is used doesn't work from time to time.
This will also work for private accounts under 2 conditions:
1. You log in with the private account you want to check
2. The account you use to log in follows the private account you want to check.

If the account is public that you want to check, you can log in with any account and
still check said account's followers.
The code stores a set of all the followers an account has in the Documents folder.
The next time the code is run, it will compare current followers to the followers saved originally. 
If the new followers set is missing someone from the old followers, that means they unfollowed and that is 
output to the user. Vice versa is true for followers.

You can also see who is not following you back at the end of the run if you choose to.
