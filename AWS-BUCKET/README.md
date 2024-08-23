#commandos uteis do terraform

 
```bash
terraform init
```
baixa os provides definidos na tag provides

```bash
terraform fmt 
```
organiza o codigo pelo terraform

```bash
terraform fmt --check
```
lista todos os arquivos que sao passiveis de formatacao

```bash
terraform fmt --diff
```
Lista as alterações que o terraform realizado no meu codigo


```bash
terraform validate
```
Realiza uma validação do código terraform


```bash
terraform plan
```
Expoe um plano que o terraform ira fazer com o projeto. Ele nao executa nada ainda, porém valida os dados necessarios para a execucao futura.

```bash
terraform plan -out nomeArquivo.out
```
Salva o plano de execução em um arquivo alem de exubir o plano no console


```bash
terraform show nomeArquivo.out
```
Abre o arquivo binario e exibe o plano de execucao
