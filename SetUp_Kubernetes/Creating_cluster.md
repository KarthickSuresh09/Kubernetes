Create EKS cluster and nodes from EC2 Management Host
   ```sh
   eksctl create cluster --name cluster-name  \
   --region region-name \
   --node-type instance-type \
   --nodes-min 2 \
   --nodes-max 2 \ 
   --zones <AZ-1>,<AZ-2>
```
                                  OR

   example:
```
   eksctl create cluster --name my-lab-cluster --region ap-south-1 --node-type t2.medium
```

cluster delete command 
```
eksctl delete cluster my-lab-cluster --region ap-south-1
```
