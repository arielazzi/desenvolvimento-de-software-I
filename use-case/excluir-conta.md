# EXCLUIR CONTA - CASO DE USO

## NOME
UC002 - Excluir conta

## DESCRIÇÃO SUCINTA
O **Admnistrador** exclui uma conta no sistema.

## ATORES
1. Admnistrador

## PRÉ-CONDIÇÕES
1. O admnistrador está autenticado no sistema

## FLUXO BÁSICO
1. O admnistrador faz busca pela conta que ele deseja excluir
2. O admnistrador seleciona a conta que ele deseja excluir
3. O admnistrador visualiza as informações do usuário que ele tem permissão de visualização
4. O admnistrador seleciona a opção excluir conta
5. O admnistrador fornece sua senha de acesso para confirmação
6. O sistema exclui a conta
7. O sistema envia um e-mail ao endereço de e-mail vinculado à conta, informando o acadêmico
8. O caso de uso é encerrado

## ESTRUTURA DE DADOS
Nenhuma

## FLUXOS ALTERNATIVOS
- **(A1) Fluxo Alternativo ao Passo 5 - A senha fornecida está incorreta**
    1. O admnistrador é informado, e o sistema retorna ao passo 5
    
## REGRAS DE NEGÓCIO
Nenhuma
