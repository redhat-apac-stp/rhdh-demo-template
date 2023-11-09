# rhdh-demo-template
Some customize template for Red Hat Dev Hub Show Case or DevSecOps End to End Show Case


## How to run the demo
1. Provision the configured platform in https://demo.redhat.com/catalog?item=babylon-catalog-prod%2Fenterprise.red-hat-developer-hub-demo.prod

This gave you a  configured platform with many components which described on https://docs.google.com/document/d/1xc8Toj-553q52WVyQ65PRpIqhy5CCpdVJtSdhWeGR3w/edit?usp=sharing 

2) Run post configure script to make the platform ready for devsecops

You need to login into the platform before run the ansible script:
```
ansible-playbook template.yaml
```

3) Trigger the template from the RHDH and pick up the template name ""


