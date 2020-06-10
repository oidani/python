# Descrição

Aplicação com possibilidade de validar um CPF inserido pelo usuário e gerar um CPF válido.

## Esta aplicação deve ser utilizada para fins de teste de software.

# User Stories

## Geral

 - [ ] Ao iniciar a aplicação, o usuário irá visualizar uma mensagem solicitando que escolha entre gerar um CPF válido ou validar um CPF
 - [ ] O usuário irá escolher entre gerar um CPF válido ou validar um CPF
 - [ ] Ao receber o resultado de sua solicitação na tela, o usuário poderá escolher se deseja receber a saída obtida em um arquivo nos seguintes formatos:
    - [ ] JSON
    - [ ] YAML
    - [ ] CSV
    - [ ] JSON e YAML
    - [ ] JSON e CSV
    - [ ] YAML e CSV
    - [ ] JSON, YAML e CSV
    - [ ] Não deseja receber via arquivo
- [ ] O usuário poderá ver na tela o caminho onde os arquivos escolhidos foram salvos

## Validar CPF

- [X] O usuário irá visualizar uma mensagem solicitando que insira um CPF para validação, no formato numérico
- [X] O usuário irá inserir um valor para validação
- [X] O usuário irá visualizar na tela se o valor inserido é ou não um CPF válido
    - [X] Se for um CPF válido, o usuário também visualizará na tela a UF do CPF inserido

## Gerar CPF

- [ ] O usuário poderá ver na tela o CPF gerado em dois formatos, bem como sua UF
    - [ ] Formato 1: 11 dígitos, todos numéricos inteiros sem pontos e hífen (ex. XXXXXXXXXXX)
    - [ ] Formato 2: 14 dígitos, sendo 11 numéricos inteiros, com pontos e hífen (ex. XXX.XXX.XXX-XX)
    - [ ] UF: formato de 2 letras maiúsculas

# Etapas

## Geral

- [ ] A aplicação irá exibir uma mensagem solicitando que o usuário escolha entre gerar um CPF válido ou validar um CPF
- [ ] A aplicação irá exibir na tela o programa referente à escolha do usuário
- [ ] Após enviar a saída na tela, a aplicação solicitará que o usuário escolha se deseja receber a saída obtida em um arquivo nos seguintes formatos:
    - [ ] JSON
    - [ ] YAML
    - [ ] CSV
    - [ ] JSON e YAML
    - [ ] JSON e CSV
    - [ ] YAML e CSV
    - [ ] JSON, YAML e CSV
    - [ ] Não deseja receber via arquivo
- [ ] A aplicação exibirá na tela o caminho onde os arquivos escolhidos foram salvos
    - [ ] No Windows: a definir
    - [ ] No Linux: a definir

## Validar CPF

- [X] A aplicação exibirá uma mensagem solicitando que o usuário insira o CPF para validação
    - [X] O CPF deve ser inserido sem pontos e sem hífen
- [X] A aplicação irá verificar se o CPF inserido está no padrão necessário para validação
    - [X] Padrão: 11 dígitos numéricos inteiros sem pontos e hífen (ex. XXXXXXXXXXX)
- [X] A aplicação realizará a validação do CPF
    - [X] Verificar se o número inserido possui exatamente 11 dígitos inteiros
    - [ ] Verificar se o o número inserido não possui todos os dígitos iguais (ex. 00000000000, 33333333333, etc), uma vez que tais valores são considerados CPFs inválidos
- [X] A aplicação retornará na tela uma mensagem com o CPF inserido e se o mesmo é válido
    - [X] O CPF deverá ser exibido com pontos e hífen
    - [X] Se o CPF for válido, deverá ser exibida sua UF
    - [X] O formato da UF será 2 letras maiúsculas

## Gerar CPF

- [ ] A aplicação irá gerar um número de CPF válido
    - [ ] O CPF gerado tem de conter 11 dígitos numéricos inteiros
    - [ ] O CPF gerado não pode conter todos os dígitos iguais (ex. 00000000000, 33333333333), uma vez que tais valores são considerados CPFs inválidos
- [ ] A aplicação retornará na tela o CPF em dois formatos e sua UF
    - [ ] Formato 1: 11 dígitos, todos numéricos inteiros sem pontos e hífen (ex. XXXXXXXXXXX)
    - [ ] Formato 2: 14 dígitos, sendo 11 numéricos inteiros, com pontos e hífen (ex. XXX.XXX.XXX-XX)
    - [ ] UF: formato de 2 letras maiúsculas