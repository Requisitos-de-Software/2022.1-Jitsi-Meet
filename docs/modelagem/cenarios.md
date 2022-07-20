# Cenários

## Versionamento

| Versão | Data  | Descrição            | Autor        |
| ------ | :---: | -------------------- | ------------ |
| 1.0    | 20/07/2022 | Criação do documento | Samuel Avila e Felipe Moura |

_Tabela 1: Versionamento_

## Introdução

Um cenário é a descrição de um evento que ocorrerá dentro do sistema. Eles são uma ferramenta importante para ter uma documentação mais detalhada e orientada ao usuário, já que em cada cenário são descritos variedades de interação em uma mesma funcionalidade.

Neste artefato estarão registrados os cenários elaborados para o Jitsi Meet.

## Metodologia

A descrição do cenário se dá pela tabela:

| Título     | Nome do Cenário                     |
| ---------- | ----------------------------------- |
| Contexto   | _local, tempo, pré e pós condições_ |
| Atores     | _atores envolvidos_                 |
| Recursos   | _recursos envolvidos_               |
| Episódios  | _detalhes e variações dos cenários_ |
| Restrições | _descrição das restrições_          |
| Exceções   | _descrição da exceção_              |

_Tabela 2: Legenda dos Cenários_
## Resultados

### Cenário 01 - Criação de uma sala

| Título     | Cenário 01 |
| ---------- | --------------- |
| Objetivo   | Criar uma sala de videoconferência.                  |
| Contexto   | Local: Tela de início. <br>Tempo: Indetermindao. <br>Pré-condição: Acesso a internet. |
| Atores     | Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone.|
| Episódios  | Usuário querendo criar uma nova sala. |
| Restrições | Acesso  internet diponível. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone. |

### Cenário 02 - Acessar uma sala

| Título     | Cenário 02 |
 ---------- | --------------- |
| Objetivo   | Entrar uma sala de videoconferência já criada.|
| Contexto   | Local: Tela de início. <br>Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e sala criada.|
| Atores     | Convidado da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. <br>Sala criada.|
| Episódios  | Usuário querendo entrar em uma sala já criada. |
| Restrições | Acesso  internet diponível. <br>Sala já criada. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone. <br>Sala não criada.|

### Cenário 03 - Compartilhar a própria tela

| Título     | Cenário 03 |
| ---------- | --------------- |
| Objetivo   | Comapartilhar a tela com outros usuários.|
| Contexto   | Local: Sala de videoconferência. <br>Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala. <br>Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. <br>Estar em uma sala.|
| Episódios  | Usuário querendo compartilhar sua tela com outros usuários. |
| Restrições | Acesso  internet diponível. <br>Estar em uma sala criada. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone. <br>Não estar em uma sala criada.|

### Cenário 04 - Desligar o som e o microfone

| Título     | Cenário 04 |
| ---------- | --------------- |
| Objetivo   | Desligar o som e o microfone para que outros usuários não escutem.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala.<br> Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. <br>Estar em uma sala.|
| Episódios  | Usuário querendo desligar seu som e microfone. |
| Restrições | Acesso  internet diponível. <br>Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|

### Cenário 05 - Sair da reunião

| Título     | Cenário 05 |
| ---------- | --------------- |
| Objetivo   | Sair de uma reunião.|
| Contexto   | Local: Sala de videoconferência. <br>Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala. <br>Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. <br>Estar em uma sala.|
| Episódios  | Usuário querendo sair da sala a qualquer momento. |
| Restrições | Acesso  internet diponível. <br>Estar em uma sala criada. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|

### Cenário 06 - "Quebrar" a reunião em salas menores separadas

| Título     | Cenário 06 |
| ---------- | --------------- |
| Objetivo   | Gerar breakout rooms de uma sala ja criada.|
| Contexto   | Local: Sala de videoconferência. <br>Tempo: Indetermindao.<br> Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. <br>Estar em uma sala.|
| Episódios  | Criador da sala querendo criar breakout rooms da sala já existente. |
| Restrições | Acesso  internet diponível. <br>Estar em uma sala criada. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone. <br>Não estar em uma sala criada. <br>Não for o criador da sala.|

### Cenário 07 - Falar por mensagens de texto

| Título     | Cenário 07 |
| ---------- | --------------- |
| Objetivo   | Se comunicar com outros usuários por meio de mensagens de texto.|
| Contexto   | Local: Sala de videoconferência. <br>Tempo: Indetermindao.<br> Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala. Criador da sala. |
| Recursos   | Internet disponível.<br> Acesso a um computador ou smartphone. <br>Estar em uma sala.|
| Episódios  | Usuário querendo mandar mensagens de texto em um chat. |
| Restrições | Acesso  internet diponível. <br>Estar em uma sala criada. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone. <br>Não estar em uma sala criada.|

### Cenário 08 - Visualizar histórico de reuniões

| Título     | Cenário 08 |
| ---------- | --------------- |
| Objetivo   | Vizualizar o histórico de reuniões já participadas.|
| Contexto   | Local: Tela de início.<br> Tempo: Indetermindao. <br>Pré-condição: Acesso a internet . |
| Atores     | Convidado da sala. <br>Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. |
| Episódios  | Usuário querendo vizualizar as reuniões que já participou. |
| Restrições | Acesso  internet diponível.  |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone. |

### Cenário 09 - Visualizar calendário

| Título     | Cenário 09 |
| ---------- | --------------- |
| Objetivo   | Vizualizar o calendário com as reuniões marcadas.|
| Contexto   | Local: Tela de início. <br>Tempo: Indetermindao.<br> Pré-condição: Acesso a internet. |
| Atores     | Convidado da sala.<br> Criador da sala. Api do Google Agendas.|
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone. |
| Episódios  | Usuário querendo vizualizar marcadas no Google Agendas da conta sincronizada.  |
| Restrições | Acesso  internet diponível.  |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone. |

### Cenário 10 - Levantar a mão

| Título     | Cenário 10 |
| ---------- | --------------- |
| Objetivo   | Pedir permissão de fala por meio de uma reação que simula o gesto de levantar a mão.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala.<br> Criador da sala. |
| Recursos   | Internet disponível.<br> Acesso a um computador ou smartphone.<br> Estar em uma sala.|
| Episódios  | Usuário pedindo a permissão para falar em uma reunião. |
| Restrições | Acesso  internet diponível.<br> Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|


### Cenário 11 - Criar enquetes

| Título     | Cenário 11 |
| ---------- | --------------- |
| Objetivo   | Criar enquetes vizando a votação de algo ou alguma coisa.|
| Contexto   | Local: Sala de videoconferência. <br>Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone.<br> Estar em uma sala.|
| Episódios  | Criador da sala querendo abrir uma enquete para a votação de algo. |
| Restrições | Acesso  internet diponível.<br> Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|


### Cenário 12 - Responder enquetes

| Título     | Cenário 12 |
| ---------- | --------------- |
| Objetivo   | Responder a enquete criada pelo criador da sala.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala. |
| Recursos   | Internet disponível.<br> Acesso a um computador ou smartphone.<br> Estar em uma sala.|
| Episódios  | Convidado querendo responder uma enquete em andamento. |
| Restrições | Acesso  internet diponível.<br> Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|


### Cenário 13 - Mudar planos de fundo do vídeo

| Título     | Cenário 13|
| ---------- | --------------- |
| Objetivo   | Mudar o fundo do vídeo.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao.<br> Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala. <br>Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone.<br> Estar em uma sala.|
| Episódios  | Usuário querendo modificar o fundo de sua câmera. |
| Restrições | Acesso  internet diponível. <br>Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone. <br>Não estar em uma sala criada.|


### Cenário 14 - Editar perfil 

| Título     | Cenário 14|
| ---------- | --------------- |
| Objetivo   | Fazer alterações no perfil durante a reunião.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala.<br> Criador da sala. |
| Recursos   | Internet disponível.<br> Acesso a um computador ou smartphone.<br> Estar em uma sala.|
| Episódios  | Usuário querendo editar o próprio perfil durante uma reunião. |
| Restrições | Acesso internet diponível.<br> Estar em uma sala criada. |
| Exceções   | Sem acesso à internet. <br>Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|

### Cenário 15 - Configurar som e vídeo

| Título     | Cenário 15|
| ---------- | --------------- |
| Objetivo   | Fazer congifurações no som e vídeo durante a videoconferência.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao. <br>Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Convidado da sala.<br> Criador da sala. |
| Recursos   | Internet disponível. <br>Acesso a um computador ou smartphone.<br> Estar em uma sala.|
| Episódios  | Usuário querendo configurar tanto entrada quanto saída de som e vídeo durante uma reunião. |
| Restrições | Acesso  internet diponível.<br> Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone.<br> Não estar em uma sala criada.|

### Cenário 16 - Moderação de outros usuários

| Título     | Cenário 16|
| ---------- | --------------- |
| Objetivo   | Ter poder de moderação sobre os convidados.|
| Contexto   | Local: Sala de videoconferência.<br> Tempo: Indetermindao.<br> Pré-condição: Acesso a internet e estar em uma sala. |
| Atores     | Criador da sala. |
| Recursos   | Internet disponível.<br> Acesso a um computador ou smartphone. <br>Estar em uma sala.|
| Episódios  | Criador da sala querendo moderar os convidados. |
| Restrições | Acesso  internet diponível.<br> Estar em uma sala criada. |
| Exceções   | Sem acesso à internet.<br> Sem acesso a um computador ou smartphone. <br>Não estar em uma sala criada.|

## Referências

[Documento de Cenário do grupo Tembici](https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/cenarios/)

[Documento de Cenário do grupo Duolingo](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/)
