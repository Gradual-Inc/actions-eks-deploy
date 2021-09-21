# Usage

```yaml
      - name: EKS Deploy
        uses: gradual-inc/actions-eks-deploy@v1
        with:
          aws-access-key-id: ${{ secrets.EKS_AWS_ACCESS_KEY_ID }}
          aws-secret-access-key: ${{ secrets.EKS_AWS_SECRET_ACCESS_KEY }}
          docker-image-name: ${{ env.ECR_APP_NAME }}
          eks-app-name: ${{ env.EKS_APP_NAME }}
          eks-namespace: ${{ env.EKS_NAMESPACE}}
```