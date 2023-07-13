# WebApiVagas
A API permite que os usuários realizem operações CRUD nos dados de Empresas e Vagas.

Endpoints

Empresas
GET /api/Empresas: Recupera uma lista de todas as Empresas.
GET /api/Empresas/{id}: Recupera uma Empresa específica pelo ID.
GET /api/empresas/{id}/vagas: Recupera todas as Vagas associadas a uma Empresa específica.
PUT /api/Empresas/{id}: Atualiza uma Empresa existente.
POST /api/Empresas: Cria uma nova Empresa.
DELETE /api/Empresas/{id}: Exclui uma Empresa existente.
Vagas
GET /api/Vagas: Recupera uma lista de todas as Vagas ativas.
GET /api/Vagas/{id}: Recupera uma Vaga específica pelo ID.
PUT /api/Vagas/{id}: Atualiza uma Vaga existente.
POST /api/Vagas: Cria uma nova Vaga.
DELETE /api/Vagas/{id}: Exclui uma Vaga existente.
Autenticação
Determinados endpoints (PUT, POST, DELETE) exigem autenticação básica para garantir acesso autorizado.
