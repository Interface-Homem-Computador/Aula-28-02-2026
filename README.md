# Trabalho Prático: Aspectos Humanos na Interação Humano-Computador

Nesta atividade, você irá aplicar os conceitos de **Cognição, Percepção, Atenção, Memória e Carga Cognitiva** na criação de uma interface computacional real. O objetivo é testar suas habilidades como projetista (Front-end) no entendimento de como o humano processa a informação visual da tela e como construir um fluxo de baixa carga cognitiva (Carga Estranha / Extraneous).

### O Cenário

Você foi contratado para criar a **página de cadastro complexo de pacientes (Admissão de Emergência)** para o sistema interno de um Hospital. O usuário primário desta tela é o(a) recepcionista, que precisa preencher o Formulário enquanto lida com interrupções, pressão de tempo, fôlego curto dos pacientes e muito estresse no ambiente.

### A Tarefa Técnica

Codifique uma página Web (HTML, CSS e opcionalmente algum JS para validações) ou utilize algum Framework Front-end de sua preferência (React, Vue, etc.) contendo o formulário de Admissão.

Sua tela DEVE, obrigatoriamente, contemplar na prática **os 5 pilares** discutidos em aula, justificando suas escolhas através de **comentários no próprio código**.

1. **Gestalt e Percepção:** O formulário deve agrupar (via proximidade e similaridade) os conteúdos separadamente:
   - Dados Pessoais (Nome, Idade, CPF)
   - Contato de Emergência
   - Condição Médica Rápida / Sintomas Iniciais.
2. **Uso Eficiente de Cores e Contraste:** 
   - Apenas a "Ação Primária" (Confirmar Admissão) deve usar contraste acentuado.
   - Os erros e mensagens de falha obrigatória nos campos devem seguir redundância visual, contendo não apenas a cor vermelha, mas também texto avisando do erro (\textit{Daltônicos não podem ser prejudicados}).
3. **Memória e Chunking:** O campo de CPF do paciente ou telefone obrigatoriamente deve apresentar agrupamento de dados (máscara) enquanto o atendente digita (ex: 123.456.789-00 ou (11) 98888-7777). Não force a memória de curto prazo.
4. **Foco e Atenção:** Evite menus de navegação complexos no topo que dispersem a atenção do recepcionista para o que não seja a emissão do cadastro emergencial. Não use distrações animadas na tela.
5. **Redução da Carga Cognitiva:** Consistência de rótulos (Labels). Utilize \textit{Progressive Disclosure} caso ache pertinente ocultar áreas do prontuário que não sejam emergenciais num primeiro momento.

### Regra de Entrega

O exercício exige a codificação real desse formulário. Hospede o seu projeto no **GitHub** em um repositório público contendo, além do código, um arquivo `README.md` rápido explicando qual técnica dos pilares acima você julgou mais desafiadora em aplicar no seu HTML.

- **Entrega exigida pelo Professor:** A entrega final consiste em um **e-mail** enviado para o professor com o link do seu projeto hospedado no GitHub.
- **E-mail:** `karan.luciano@afya.com.br`
- **Assunto Obrigatório:** `[IHC] Exercício 02 - Nome do Aluno` *(Siga este padrão para facilitar a busca e não perder nota)*
- **Corpo do e-mail:** Cole apenas o link completo para o repositório (ex: `https://github.com/SeuUsuario/NomeDoRepositorio`).

Não anexe arquivos (ZIP, imagens) no e-mail; o envio do link do Github é a exigência formal de término desta atividade. Bom código!
