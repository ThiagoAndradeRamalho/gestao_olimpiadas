# Sistema de Gestão das Olimpíadas (SGO)

## Descrição

O Sistema de Gestão das Olimpíadas (SGO) é uma solução projetada para coordenar e gerenciar diversos aspectos dos Jogos Olímpicos. O sistema oferece funcionalidades para:

- Gerenciamento de competições
- Inscrição de atletas
- Alocação de locais para provas
- Controle de resultados
- Geração de relatórios de medalhas

## Regras de Negócio

1. **Cadastro de Competições**
   - Permite o registro de competições com detalhes como nome da modalidade, data, horário, local e lista de atletas inscritos.

2. **Inscrição de Atletas**
   - Atletas podem se inscrever em competições específicas, representando um único país por modalidade, mas participando de várias competições.

3. **Alocação de Locais**
   - Os locais são alocados para evitar conflitos de horário, com um local podendo abrigar apenas uma competição por vez.

4. **Controle de Resultados**
   - Registra os resultados das competições, determinando os atletas vencedores e os classificados em segundo e terceiro lugares.

5. **Relatórios de Medalhas**
   - Gera relatórios que mostram o desempenho dos países com base nas medalhas de ouro, prata e bronze conquistadas.

## Diagramas

<img width="1000px" height="800px" src="https://github.com/ThiagoAndradeRamalho/gestao_olimpiadas/blob/main/images/Diagrama-de-Classes.png"/>
<img width="1000px" height="800px" src="https://github.com/ThiagoAndradeRamalho/gestao_olimpiadas/blob/main/images/diagrama-de-caso-de-uso.png"/>
<img width="1000px" height="800px" src="https://github.com/ThiagoAndradeRamalho/gestao_olimpiadas/blob/main/images/Diagrama-de-Pacotes.png"/>
<img width="1000px" height="800px" src="https://github.com/ThiagoAndradeRamalho/gestao_olimpiadas/blob/main/images/diagrama-de-componentes.png"/>
<img width="1000px" height="800px" src="https://github.com/ThiagoAndradeRamalho/gestao_olimpiadas/blob/main/images/diagrama-de-implantação.png"/>

## Histórias de Usuário

### 1. Realizar Login
- **Como** um usuário (atleta ou administrador),
- **Eu quero** realizar login no sistema,
- **Para que eu** possa acessar funcionalidades específicas do meu perfil e contribuir para a organização e participação nos Jogos Olímpicos.

### 2. Verificar Local Disponível
- **Como** um administrador,
- **Eu quero** verificar a disponibilidade de locais para as competições,
- **Para que eu** possa planejar adequadamente as datas e evitar conflitos de agenda.

### 3. Alocar Local
- **Como** um administrador,
- **Eu quero** alocar um local para uma competição,
- **Para que** as competições ocorram de forma organizada e em locais adequados.

### 4. Cadastrar Competição
- **Como** um administrador,
- **Eu quero** cadastrar novas competições no sistema,
- **Para que** os atletas possam se inscrever e as competições sejam realizadas conforme planejado.

### 5. Registrar Resultados
- **Como** um administrador,
- **Eu quero** registrar os resultados das competições,
- **Para que** possamos manter um histórico preciso dos desempenhos e determinar os vencedores.

### 6. Gerar Relatório de Medalhas
- **Como** um administrador,
- **Eu quero** gerar relatórios de medalhas,
- **Para que** possamos visualizar e publicar o desempenho dos países participantes em termos de medalhas conquistadas.

### 7. Inscrever-se na Competição
- **Como** um atleta,
- **Eu quero** me inscrever em competições,
- **Para que** eu possa participar dos Jogos e representar meu país.
