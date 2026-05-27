# BANCO-DE-DADOS
TheColor - Banco de Dados
Passo a passo para Utilização
1. Criar o banco

2. Criar tabelas
Crie na ordem:
empresa
usuario
quiz
usuario_quiz
biblioteca
aviso

3. Inserir dados (Mokados para Testes)
Execute nesta ordem:
empresa
usuario
quiz
usuario_quiz
biblioteca

4.Consultar dados
SELECT * FROM usuario;
SELECT * FROM quiz;
SELECT * FROM usuario_quiz;
SELECT * FROM biblioteca;
SELECT * FROM aviso;

5. Relatório
SELECT * FROM vw_relatorio_completo;

6. Estatísticas
Usuários com maior pontuação
Média de pontos
Total de jogos
Cores pesquisadas

Importante
Criar as tabelas antes de inserir dados
usuario_quiz depende de usuario e quiz
biblioteca depende de usuario
