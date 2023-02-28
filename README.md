<!-- Nome do projeto -->
# nubeck

<!-- Listagem dos endpoints -->
## Endpoints 

- Cadastro de desepesa 
- Listar despesas
- Apagar despesa
- Editar despesa
---
### Cadastro de despesa

<!-- Endereço do recurso -->
`POST` nubeck/api/v1/despesa
        <!-- Colocar a versão é importante para compatibilidade  -->

**Exemplo de Entrada**
```js
{
    'valor': 100,
    'categoria_id': 1,
    'conta_id': 1,
    'data': '2023-01-01',
    'descricao': 'cinema'
}
```

**Campos da Requisição**
| Campo | Obrigatório | Tipo  | Descrição |
|-------|-------------|-------|-----------|
|valor  |sim          |decimal|O valo da despesa
|categoria_id|sim|int| O id da categoria de despesa, deve ser uma categoria previamente cadastrada
|conta_id|sim|data|A data da despesa
|descricao|não|texto| Uma descrição da despesa com até 255 caracteres
