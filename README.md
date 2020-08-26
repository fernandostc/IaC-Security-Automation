# Example of Infrastructure-as-a-Code Security Automation with Cloud One - Conformity Template Scanner

![](Diagram/Example_of_diagram_architecture.png)


## VSCode Plugin for Cloud One - Conformity (by Raphael Bottino)
- https://marketplace.visualstudio.com/items?itemName=raphaelbottino.cc-template-scanner

## Gitlab CI file Example for Template Scanner for CloudFormation Templates (gitlab-ci-example.yml)

Using the template scanner from Will Robison (https://github.com/OzNetNerd/Cloud-Conformity-Pipeline-Scanner)

Variable Configuration Needed:

- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- CC_API_KEY
- CC_REGION
- CC_RISK_LEVEL
- CFN_TEMPLATE_FILE_LOCATION
