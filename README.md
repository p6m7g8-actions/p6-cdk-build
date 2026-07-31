# p6m7g8-actions/cdk-build

- [p6m7g8-actions/cdk-build](#p6m7g8-actionscdk-build)
  - [Usage](#usage)

## Usage

```yaml
      - name: CDK Build
        uses: p6m7g8-actions/p6-cdk-build@main
        with:
          aws_region: ${{ secrets.CDK_DEPLOY_REGION }}
          aws_role: ${{ secrets.AWS_ROLE }}
          aws_session_name: ${{ secrets.AWS_SESSION_NAME }}
          cdk_deploy_account: ${{ secrets.CDK_DEPLOY_ACCOUNT }}
          cdk_deploy_region: ${{ secrets.CDK_DEPLOY_REGION }}
```
