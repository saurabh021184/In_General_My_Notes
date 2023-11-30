# In_General_My_Notes

1. 50 % maintainence
50 % poc

2. Out POC projects are used in:
   - mobile world congress 2018
   - NENA comtech confrence
   - comtech.com/events
3. (we know our audience)currently containerized... with current timelines but if we want to scale we can use ECS/EKS
4. Did some baseline anslysis on point of polygon for node js vs go lang (go lang was 30-40 % faster) + in tileservices we are already using golang so went with tileservices
5. out existing 988 project we got 1-2 moths to create MVP
6. Why you removed lambda deployments (lambda was giving connection issues when conneting the DB in VPC)... when we removed VPC the db connection was working fine...Lambda is basically an external connection which calls to your private VPC resources so giving some issues... unless there is some networking expert + time line pressue, we decided to swtich back to containerized application
7. Why not Dynamo DB why only SQL DB ... again intiial POC time lines + data was structured at that time... + so went with SQL DB






