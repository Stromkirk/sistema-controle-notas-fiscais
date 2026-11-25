# Sistema de Controle de Notas Fiscais

Aplicação web em Google Apps Script para acompanhamento de pedidos, recebimento de notas fiscais e vínculo fiscal, com Google Sheets como armazenamento.

## Funcionalidades
- Perfis Administrador, Compras, Fiscal e Logística.
- Entregas totais e parciais, previsão de entrega e histórico de auditoria.
- Indicadores por cores: pendente (amarelo), entregue (azul), vinculado (verde), atraso fiscal (vermelho) e previsão vencida (laranja).
- Configuração de permissões, cores e prazo de atraso.

## Instalação
1. Crie uma planilha Google exclusiva para testes e um projeto Apps Script.
2. Copie Code.gs, Index.html e appsscript.json para o projeto.
3. Em Configurações do projeto, crie a propriedade de script SPREADSHEET_ID com o ID da sua planilha.
4. Execute setupSistema_ pelo editor, autorize e consulte o registro de execução para a senha inicial. Altere-a no primeiro acesso.
5. Implante como aplicativo da web com acesso restrito aos usuários autorizados.

## Segurança
Não compartilhe a planilha de dados, senhas, propriedades de script ou registros de execução. Esta versão é destinada a demonstração e requer testes de segurança e funcionamento antes de uso em produção.
