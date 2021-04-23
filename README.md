```
eksctl enable repo \
    --cluster=craft-us-west-2 \
    --region=us-west-2 \
    --git-url=git@github.com:yahavb/craft-mmo-agones.git \
    --git-email=birayaha+gko2021@amazon.com


eksctl enable profile \
    --cluster=craft-us-west-2 \
    --region=us-west-2 \
    --git-url=git@github.com:yahavb/craft-mmo-agones.git \
    --git-email=birayaha+gko2021@amazon.com \
    app-dev
```
