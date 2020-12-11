# sae framework como aws lambda layer

## Framework como Layer do Lambda
Para adicionar o node_modules como layer do lambda, deve ser movido a pasta `node_modules` para `nodejs/node_modules`, zipar a pasta e adicionar como layer.
O node irá visualizar as libs nesta pasta.