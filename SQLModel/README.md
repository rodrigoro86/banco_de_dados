

### Iniciar o alembic
`alembic init alembic`

### Criar script de criação das tabelas
`alembic revision --autogenerate -m "Criando Tabelas"`

### Crias as tabelas
`alembic upgrade head `

### Fazer o Downgrade das tabelas
`alembic downgrade base`