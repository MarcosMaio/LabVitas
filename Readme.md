
# labVitas - Software de Gerenciamento de Laboratórios de Exame

O Vitalab é um software desenvolvido para gerenciar laboratórios de exame, proporcionando aos pacientes a facilidade de agendar exames, acompanhar seu progresso e acessar resultados. Além disso, oferece funcionalidades administrativas para a equipe de funcionários e a capacidade de compartilhar resultados com médicos.

![site illustrato](https://lh3.googleusercontent.com/pw/ADCreHfRlCyAEQ3ATlLEHJKyV0Km3CU2gqC5pgVDvUPF6X7M1EaJEqLMixfL-U_qzUBVCN4xVgFmcmv15rhyTycFwIDCVTdcqFFqq8D8PfnWcWZpWLBg8D6ivEwk2odQOzfqHMucv78UqmhSMqGoiX0LMxA=w1142-h819-s-no?authuser=1)

## Funcionalidades

Para Pacientes:

- Cadastro de Pacientes: Os pacientes podem criar uma conta, fornecendo informações como nome completo, email, username e senha.

- Login de Pacientes: Após o cadastro, os pacientes podem fazer login usando seu nome de usuário e senha.

- Agendamento de Exames: Os pacientes podem agendar exames, selecionando entre diferentes categorias, como exames de sangue ou de imagem. Eles também podem solicitar um orçamento para os exames desejados.

- Acompanhamento de Exames Agendados: Os pacientes podem acompanhar o status de seus exames agendados, verificando se estão disponíveis, marcados como "Em andamento" ou "Finalizados". O software exibe o preço de cada exame e a data da consulta.

- Visualização de Resultados de Exames: Quando um exame é concluído, os pacientes podem visualizar o resultado, que pode estar protegido por senha (a senha é fornecida no laboratório).

- Cancelamento de Exames: Os pacientes têm a opção de cancelar um exame agendado, caso não possam comparecer na data agendada.

- Histórico de Exames: Os pacientes podem acessar seu histórico de exames, onde podem ver todos os exames já realizados ou agendados, com status "Finalizado" ou "Em análise". Eles podem abrir os resultados desses exames, quando disponíveis.

- Compartilhamento com Médicos: Os pacientes podem escolher compartilhar seus resultados com médicos, gerando um link que concede acesso temporário aos médicos.

Para Funcionários/Administradores:

- Gerenciamento de Clientes: Funcionários/administradores podem acessar informações do banco de dados de clientes e filtrar os registros por nome ou CPF.

- Visualização de Exames de Clientes: Quando um cliente é encontrado, os funcionários/administradores podem acessar todos os exames e arquivos associados a esse cliente, tanto prontos quanto em andamento.

- Gerenciamento de Arquivos de Exames: Os funcionários/administradores podem adicionar, editar e definir o status dos arquivos de resultados dos exames. Eles também podem decidir se o arquivo requer uma senha para ser acessado, e, se necessário, gerar uma senha aleatória.

Para Médicos:

- Acesso a Resultados de Exames: Os médicos podem acessar os resultados dos exames compartilhados pelos pacientes. O acesso é concedido por meio de links temporários gerados pelos próprios pacientes.

  
## Tecnologias Utilizadas

**Cliente:** HTML, CSS ,JavaScript e Django

**Servidor:** Python e Django 

