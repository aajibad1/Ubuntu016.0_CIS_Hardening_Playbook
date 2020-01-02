# Ubuntu016.0_CIS_Hardening_Playbook

upgrade pip 

update ansible 

touch /etc/security/pwquality.conf

## RUNS level 1 Profile only 
ansible-playbook playbook.yaml --tags "level1"  --check
