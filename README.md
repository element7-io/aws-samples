# aws-samples

## Description
Handy scripts and templates to get you going on AWS.

## Content

### CloudFormation
- `cfn-meta-stack.yaml`: meta stack with **global shared resources**:
  - LogBucket: bucket for general logs
  - ArtifactBucket: bucket for general artifacts (for CodeBuild, CodePipeline, ...)
- `cfn-security-stack.yaml`: stack supporting a good cloud posture
