# IAM-example-project
An exploration of IAM

I broke this project into four parts:
1. Created a custom policy. In this example I created a policy for EC2 development to give those granted access to Read, Write, and Tagging permissions. 
2. Created a custom role. The role contains the custom policy I previously set up. 
3. Created four example users. They were assigned to a group with the custom policy applied with a default password set to reset upon their first login.
4. Added those users to a group.
