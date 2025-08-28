# GitHub Actions Self-Hosted Runner on AWS  

## Steps Performed
1. Provisioned EC2 instance  
2. Installed GitHub Actions runner binary  
3. Connected runner to GitHub repo with token  
4. Tagged runner for specific workflows  
5. Tested workflow using self-hosted runner  

## Learnings
- GitHub-hosted runners = free but limited runtime  
- Self-hosted runners = cost depends on infra, but more power  
- Self-hosted works like **IaaS** model: you manage everything  
