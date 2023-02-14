<!-- Nome do projeto -->
# nubeck

<!-- Listagem dos endpoints -->
## Endpoints 

- Cadastro de desepesa 
- Listar despesas
- Apagar despesa
- Editar despesa

### Cadastro de despesa

<!-- Endereço do recurso -->
POST nubeck/api/v1/despesa
        <!-- Colocar a versão é importante para compatibilidade  -->

**Exemplo de Entrada**

```json
{
    valor: 100,
    categoria: 'Lazer',
    conta: "santander",
    data: '2023-01-01',
    descricao: 'cinema'
}
```