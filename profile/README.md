# Título do Projeto

API criada para o tech challenge da Pós Tech FIAP do curso de Arquitetura de Software turma 4SOAT - G60

## Iniciando projeto

### [Micro serviço de produtos](https://github.com/4soat-grupo-60/produtos-ms)


Para iniciar esse projeto, após clonar o serviço rode no terminal:

```bash
  cd k8s
```

dentro da pasta /k8s rode no terminal:

```bash
  kubectl apply -f .
```

Acompanhar o status da criação dos PODS

```bash
kubectl get pods --namespace=totem
```

Após todos os pods estarem com o status "Running" seguir para subir o próximo serviço

### [Micro serviço de pedidos](https://github.com/4soat-grupo-60/pedido-ms)

Para iniciar esse projeto, após clonar o serviço rode no terminal:

```bash
  cd k8s
```

dentro da pasta /k8s rode no terminal:

```bash
  kubectl apply -f .
```

Acompanhar o status da criação dos PODS

```bash
kubectl get pods --namespace=totem
```

Após todos os pods estarem com o status "Running" seguir para subir o próximo serviço

### [Micro serviço de pagamentos](https://github.com/4soat-grupo-60/payment-ms)

Para iniciar esse projeto, após clonar o serviço rode no terminal:

```bash
  cd k8s
```

dentro da pasta /k8s rode no terminal:

```bash
  kubectl apply -f .
```

Acompanhar o status da criação dos PODS

```bash
kubectl get pods --namespace=totem
```

## Análise OWASP

[Micro serviço de produtos](https://4soat-grupo-60.github.io/produtos-ms/scanner/produtos-report-v2-2024-07-31.html)

## Funcionalidades

#### Cliente

- Cadastrar cliente
- Buscar clientes por CPF
- Listar todos os clientes
- Cadastrar pedido

#### Pedido

- Buscar pedido por id
- Atualizar status pedido
- Link pedido

#### Fila de pedidos

- Listar pedidos em preparo
- Listar pedidos prontos
- Listar pedidos aguardando preparo

#### Produtos

- Cadastrar produtos
- Buscar produto por categoria
- Listar todos os produtos
- Atualizar produtos
- Apagar produtos
- Processar pagamento

## Postman

[Postman](https://elements.getpostman.com/redirect?entityId=26331161-07de13c2-3c77-4e02-851d-1d35a173d086&entityType=collection)

## Miro

[Miro](https://miro.com/app/board/uXjVNe6pUU4=/)

## Storytelling

[Storytelling](https://docs.google.com/document/d/1UKt6QM1xacBQHZGV9gy3_L3Li5LpHbLUMzv4UTCF_Nc/edit)

## Diagrama Arquitetura on-premises

<!--- ![Diagrama Arquitetura on-premises](https://github.com/adrianolima/tech_challenge_4soat_g60/blob/main/docs/on-premises/diagrama_onpremises.png) -->

## RIPD
[RIPD](https://1drv.ms/w/c/2212ca1d71ab54c7/Ee8_H5k-tp9BkqzgWAq3uuUB4n1KSL7ab9D5Kk5LjMKqBg?e=3hskNa)

