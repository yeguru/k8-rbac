# k8-rbac

REGION_CODE=us-east-1
CLUSTER_NAME=expense
AWS_ACCOUNT_ID=050451372978

# Create IAM OIDC provider

eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve