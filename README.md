Darklight Nova Core Issue: Users
====================================

Issue for [Darklight Nova Core](https://github.com/darklight-studios/darklight-nova-core)

### Function
The Users issue checks if a user account has been disabled or removed

### Use

1. Download the latest version from the [releases](https://github.com/darklight-studios/UserIssue/releases/) section
2. Add DNCUserIssue.jar to your DNC build path
3. Create a `UserIssue userIssue = new UserIssue()` variable
4. Set the issue's username: `userIssue.setUsername("baduser");`
5. Add `userIssue` to the issues array in CoreEngine
6. Start DNC!

### License
[GPLv3](LICENSE)

### Contributors
[@IsaacJG](https://github.com/IsaacJG)
