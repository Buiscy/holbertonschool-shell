0-iam_betty > su betty: "su" - run a command with substitute user and group ID. User must already exist before actioning this command
1-who_am_i > id -nu: "id" prints user and group infomation for each specified user. -n prints the name instead of a number, -u prints only the effective user id.
2-groups > groups: lists groups. Print group memberships for each USERNAME or, if no USERNAME is specified, for the current process
3-new_owner > chown betty hello: Change the owner and/or group of each FILE to OWNER and/or GROUP. 
4-empty > touch hello: uses the touch command to create a file called hello.