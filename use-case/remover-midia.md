# REMOVER MÍDIA - CASO DE USO

## NOME
UC004 - Remover Midia

## DESCRIÇÃO SUCINTA
O **Autor da mídia** ou o **Admnistrador** remove uma mídia do sistema.

## ATORES
1. Autor da mídia ou Admnistrador (Usuário)

## PRÉ-CONDIÇÕES
1. O usuário está autenticado no sistema

## FLUXO BÁSICO
1. O usuário faz busca pela mídia que ele deseja remover
2. O usuário seleciona a opção "Remover Mídia" (disponível apenas para um admnistrador, ou o autor da mídia)
3. O usuário fornece sua senha de acesso para confirmação
6. O sistema verifica senha fornecida
7. O sistema remove a mídia
8. O sistema notifica o autor que a mídia foi removida
9. O caso de uso é encerrado

## ESTRUTURA DE DADOS
Nenhuma

## FLUXOS ALTERNATIVOS
- **(A1) Fluxo Alternativo ao Passo 6 - A senha fornecida está incorreta**
    1. O usuário é informado, e o sistema retorna ao passo 5

## REGRAS DE NEGÓCIO
Nenhuma