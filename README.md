# estudos em kubernetes

## Conceitos Básicos ao Deploy - com práticas em Microserviços  e Cloud

- Os Pods são as menores partes gerenciáveis do K8s.
  - São efemeros, ou seja, o K8s pode destruir e recriar o tempo todo
  - Portanto o acesso a eles não deve ser direto, e sim através de services
  - Services são componentes duráveis e portando oferece uma interface de comunicação adequada
  - Exemplo: Em um LAMP, o host no WordPress seria o service que encapsula o Mysql
