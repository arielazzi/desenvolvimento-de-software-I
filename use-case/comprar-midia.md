# COMPRAR MIDIA - CASO DE USO

## NOME
UC005 - Comprar Midia

## DESCRIÇÃO SUCINTA
O **Acadêmico** compra uma mídia

## ATORES
1. Acadêmico

## PRÉ-CONDIÇÕES
1. O acadêmico está autenticado no sistema
2. A Mídia não foi previamente comprada pelo acadêmico

## FLUXO BÁSICO
1. O acadêmico faz busca pela mídia que ele deseja comprar
2. O acadêmico seleciona a opção "Comprar Mídia"
3. O sistema verifica a quantidade créditos disponível do acadêmico
4. O acadêmico fornece sua senha de acesso para confirmação
5. O sistema verifica a senha fornecida
6. O valor da mídia é subtraido do valor de créditos do usuário
7. 90% do valor da mídia é adicionado aos créditos do autor da mídia
8. 10% do valor da mídia é adicionado aos créditos do admnistrador do sistema
9. O sistema adiciona a midia à lista de mídias compradas do usuário
10. O caso de uso é encerrado

## ESTRUTURA DE DADOS
Nenhuma

## FLUXOS ALTERNATIVOS
- **(A1) Fluxo Alternativo ao Passo 3 - Crédito insuficiente**
    1. O acadêmico é informado que ele não contém crédito suficiente para compra, e o fluxo é interrompido
    
## REGRAS DE NEGÓCIO
Nenhuma