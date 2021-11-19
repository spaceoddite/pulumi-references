# Pulumi-References

## References on Pulumi component provider packages and component resources


- [Intro to Resources](https://www.pulumi.com/docs/intro/concepts/resources/) - Link to offical docs of custom and component resources 
### Creating component resources 
  - Blogposts
    - [How to write reusable infrastructure code with Pulumi](https://www.novatec-gmbh.de/en/blog/how-to-write-reusable-infrastructure-code-with-pulumi/) - Shows Component creation in typescript
    - [Walkthrough on creating s3 folder component](https://www.pulumi.com/registry/packages/aws/how-to-guides/s3-folder-component/) - [Git repo](https://github.com/pulumi/examples/tree/master/aws-js-s3-folder-component) 
  - Videos
    - Component resource - [How To Build Reusable Infrastructure as Code Patterns](https://www.youtube.com/watch?v=3BaDCrCw5FM)
           - [`jaxxstorm/pulumi-component-workshop`](https://github.com/jaxxstorm/pulumi-component-workshop) - Git repository
  - Example repos
    - [aws-go-s3-folder-component](https://github.com/pulumi/examples/tree/master/aws-go-s3-folder-component) -
    - [aws-js-webserver-component](https://github.com/pulumi/examples/tree/master/aws-js-webserver-component)
    - [classic-azure-py-webserver-component](https://github.com/pulumi/examples/tree/master/classic-azure-py-webserver-component)
    - [jen20/pulumi-aws-vpc: Good-Practice AWS VPC Component for Pulumi](https://github.com/jen20/pulumi-aws-vpc)
    - [gcp-py-network-component](https://github.com/pulumi/examples/tree/master/gcp-py-network-component)

### Creating Component Provider Packages

- Boilerplate code - Templates
  - [`pulumi-component-provider-py-boilerplate`](https://github.com/pulumi/pulumi-component-provider-py-boilerplate) - Demonstrates building a multi-lang Pulumi component provider in Python
  - [`pulumi-component-provider-go-boilerplate`](https://github.com/pulumi/pulumi-component-provider-go-boilerplate) 

- Articles
  - [https://www.pulumi.com/blog/pulumiup-pulumi-packages-multi-language-components](https://www.pulumi.com/blog/pulumiup-pulumi-packages-multi-language-components/)
  - [Easily Create and Manage AWS EKS Kubernetes Clusters](https://www.pulumi.com/blog/easily-create-and-manage-aws-eks-kubernetes-clusters-with-pulumi/)
  - [Understanding Pulumi Packages | lbr](https://www.leebriggs.co.uk/blog/2021/05/17/iac-abstractions.html)

- Videos
  - [Pulumi: Multi Language Packages | Rawkode Live](https://www.youtube.com/watch?v=_RXvNS5N8A8) - Good video 
- Component provider packages examples
  - [pulumi/pulumi-awsx: AWS infrastructure best practices in component form!](https://github.com/pulumi/pulumi-awsx)
  - [pulumi/pulumi-eks: A Pulumi component for easily creating and managing an Amazon EKS Cluster](https://github.com/pulumi/pulumi-eks)
        - Docs for eks - [eks.Amazon EKS](https://www.pulumi.com/registry/packages/eks/api-docs/)
  - [https://github.com/pulumi/pulumi-kubernetes-ingress-nginx](https://github.com/pulumi/pulumi-kubernetes-ingress-nginx)
  - [Pulumi Registry](https://www.pulumi.com/registry/) - to see available component packages in registry - set type to component in filter


 

- Other Pulumi references:
  - [AWS Modernization with Pulumi :: Modern Infrastructure as Code with Pulumi](https://pulumi.awsworkshop.io/)
