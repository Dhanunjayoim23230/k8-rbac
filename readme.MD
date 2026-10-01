# RBAC 
*ADMINISTROTOR ACTIVITY

REGION_NAME=us-east-1
CLUSTER_NAME=roboshop
AWS_ACCOUNT_ID=753369745113

### PERMISSIONS
* OIDC Provider: K8 to connect external resources
'''
eksctl utils associate-iam-oidc-provider \
    --region $REGION_NAME \
    --cluster $CLUSTER_NAME\
    --approve