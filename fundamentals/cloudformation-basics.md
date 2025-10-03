### CloudFormation - Infrastructure as Code

- Templates for creating AWS infrastructure
- Written in YAML or JSON
- Creates resources as "stacks"
- Free service - only pay for resources created
- Repeatable deployments across regions
- Automatic rollback if deployment fails

### Template Parts
- **Resources** - AWS services to create (EC2, S3, VPC)
- **Parameters** - input values for customization
- **Outputs** - return values from stack

### Stack Operations
- **Create** - deploy new infrastructure
- **Update** - modify existing stack
- **Delete** - remove all resources

### Common Functions
- **!Ref** - reference parameters or resources
- **!GetAtt** - get resource attributes
- **!Sub** - substitute variables

### Benefits
- Version controlled infrastructure
- Consistent deployments
- Easy cleanup - delete entire stack
- Dependency management handled automatically