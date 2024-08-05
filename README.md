# SRE/Devops Interview Questions

- Expected YOE - 1 year
- mostly based on my past experience

---

## topics

1. Networking in GCP
2. monitoring infra
3. VPC
4. Deployment strategy in k8s
5. CI CD
6. K8s strategies in deployments
7. Sad Servers questions - [Link](https://sadservers.com/)
8. VM migration steps
9. DB migration steps
10. any other type of migration that you have worked on
11. Docker vs virtualization
12. Architecture of docker
13. Docker images - single vs multi stage
14. Terraform
    - modules
    - drifts
    - best practices
    - latencies

---


## Questions

1. 3 tier architecture in GKE
2. 3 tier architecture using EC2
3. 3 tier architecture end to end with best practices
4. GKE upgradation process
   - What changed in the API that you were migrated to?
   - What APIs got deprecated?
   - What APIs were added?
6. K8s replicaset vs statefulset
7. is persistent volume in deployment is equal to statefulset?
8. how networking happens in all the services?
   - internal architecture
9. How to schedule pods differently in each node?
10. Nginx in a fresh EC2 but it's not working. How will you debug it?
11. How autoscaling happens in k8s?
12. What happens when you type www.example.com?
13. difference between taints and tolerations
14. What is node selector? why it is used?
15. How will you debug nginx ingress controller and applications returning 503 -> in GKE?
16. Pods are in pending state. What could be the possible reason?
17. How to migrate docker volume? between instances
18. scp, rsync
    - how it works? difference
19. systemctl vs journalctl
20. file and inodes
21. What are services in k8s and what are they?
22. What are services in linux and what are they?
23. env and expose in docker
24. Terraform impersonification in gcp?
    - how it works
    - whole process
25. Authorization vs authentication
    - types of these
    - architecture of each one
26. service level logs - how to check
27. db or vm - how to gracefully kill them
28. signal
    - what are these?
    - how to capture signals?
    - does application capture those?
29. can subnet has same ips?
30. how you effectively update and run code in vm?
31. What are dependency injection?
32. type of file systems
33. how to mount new file system
34. permissions in linux
35. chmod vs chown
36. cidr
    - what are these and how to calculate
37. What are hosts
38. what is /24 or /32 means?
39. loadbalancer
    - layer 4 vs layer 7
40. can we do ssh from layer 7 loadbalancer
41. can we do ssh from layer 4 loadbalancer
42. ssl vs tls
    - where it happens?
    - entire architecture
43. you have a vm, and you want to give bucket list permission without any manual efforts. How will you do it?
44. statefulset vs deployment
45. secrets? how to add?
46. configmap? how to add?
47. given a web server and a db, server is not able to connect to db, how do you debug it?
    - show all cases
    - from monitoring aspect to cloud to network to linux to os to application
    - each component of architecture - and what could be the possible error and how will you debug this
48. you want to connect to outer system. username and password is same across the org.
    - you dont want to enter username and password again and again.
49. nginx?
    - usecase
    - fwd vs reverse proxy
50. vertical vs horizontal scaling
51. k8s? what it is? why it is?
52. k8s - different types of controllers
53. metrics - how to choose? what to choose?
54. ondemand vs spot
55. difference between ls ; echo hello vs ls && echo hello
56. difference between > and >> and < and <<
57. stderr vs stdout
58. how `ls && echo` works

---

## Machine round

1. Git - rebase, change config user, etc.
2. terraform - create docker container, basic ec2 instance
3. docker - create nginx container, docker compose
4. linux - count number of elements in an array
5. linux - max continuous subarray sum
6. linux - string manipulation
7. ansible - git and nginx with docker
8. terraform - aws ec2 and ami id
9. aws iam role creation and access
10. Python LLD - based on k8s functionality like autoscaling or pdbs etc.
11. linux - string manipulation - sed, awk, grep, regex
12. linux - file and folder manipulation
13. linux - optimization commands, utility and resource consumption commands like top
14. linux - get all process under your username
