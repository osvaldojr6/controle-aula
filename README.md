# Controle de aulas · Alessandra Saliba

Aplicação para organizar aulas particulares infantis de uma hora, sem instalação de dependências.

## Como usar

Abra a aplicação em **https://osvaldojr6.github.io/controle-aula/**.

Baixe o repositório e abra `index.html` em um navegador atualizado. Cadastre alunos e responsáveis, adicione horas ao pacote e agende as aulas.

## Recursos

- Agenda semanal com prevenção de sobreposição.
- Agendamentos somente a partir do dia atual, com pelo menos 61 minutos de antecedência e início entre 08h e 18h.
- Bloqueio de datas individuais pela professora. O bloqueio impede novos agendamentos; aulas existentes precisam ser canceladas ou remarcadas separadamente.
- Bloqueio de períodos em uma data, com horário de início, fim e motivo opcional. Aulas de uma hora que coincidam parcialmente com o período também são impedidas. Os períodos podem ser desbloqueados na agenda.
- Solicitação de outros horários pelo WhatsApp da professora, configurado no perfil. A solicitação não cria uma reserva.
- Pacotes com horas contratadas, utilizadas, agendadas e disponíveis.
- Fotos dos alunos e da professora e observações por aula.
- Contagem regressiva para a próxima aula e cronômetro com pausa e retomada.
- Avisos cinco minutos antes e no início, mediante ativação. Mantenha a aplicação aberta e o dispositivo ativo; notificações e som dependem do navegador.
- Botão do WhatsApp com mensagem pronta para o responsável conferir e enviar. Inclui opções de confirmação e cancelamento, com prazo de pelo menos 24 horas de antecedência. Respostas não atualizam a agenda automaticamente.
- Financeiro por aluno: valor da hora, cobrança de aulas realizadas e faltas com desconto, recebimentos, adiantamentos e saldo. Aulas sem preço são sinalizadas.
- Exportação e restauração de backup em JSON.

## Armazenamento

Os dados e fotos ficam no armazenamento local do navegador, no dispositivo utilizado. Não há servidor, login ou sincronização entre dispositivos. Exporte backups regularmente. O repositório contém apenas a aplicação, sem cadastros de alunos.

Abrir o aplicativo por outro endereço ou navegador cria um armazenamento separado. Para transferir os cadastros, exporte e restaure um backup.

## Estrutura

`index.html` reúne a interface, os estilos e a lógica da aplicação. O GitHub Pages publica o conteúdo da raiz da branch `main` em https://osvaldojr6.github.io/controle-aula/.
