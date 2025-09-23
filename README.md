# class7_HW
Class 7 Zion HW

1. Login to AWS Console
2. If EC2 not shown, search for EC2 then select it
3. On left side of Console, Scroll down to Networking and Security and select Security Groups
4. Click Create Security Group
5. Create SG Name
6. Under Inbound, Add rule with following settings. (HTTP, Anywhere IPv4, 0.0.0.0/0)
7. Don't modify outbound rules
8. Add Tags if necessary
10. Click Create Security Group

11. Click Instances, Then click Launch Instances
12. Add  instance name, add tags
13. Create a Key Pair, Use default settings
14. Under Network Settings, Select your created Security Group
15. Under Advanced Settings, Paste startup script into User Data Section
16. Review and verify settings
17. Click Launch Instance
18. Copy the instance's public DNS address
19. Open your web browser
20. Enter http:// prefix then paste instance's public DNS address
21. After use, begin Teardown Procdure select Instances
22. Select current running instance, Under Instance State Select Terminate Instance
23. Select Security Groups, Select created security group
24. Under Actions, Select Delete Security Group