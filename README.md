#💻 Plano de Rede - Unicesumar (Atividade MAPA Módulo 54)

## 🌟 Destaque do Projeto

**Projeto acadêmico de infraestrutura de rede** que detalha o planejamento físico e lógico de uma rede de computadores para um ambiente corporativo. 
O projeto inclui o dimensionamento de cabeamento estruturado, a distribuição de pontos de rede e Wi-Fi por setores (TI, Desenvolvimento, Administração, etc.), e a alocação de portas no servidor central.

Este trabalho foi desenvolvido como parte da disciplina de 
**Arquitetura e Rede de Computadores** e demonstra a capacidade de projetar uma solução de conectividade robusta, considerando a metragem total de cabos (219m diretos e 107m replicados)e a organização dos dispositivos.

## 📌 Status
Concluído (Atividade de Mapa Substitutivo do módulo 54).

## 📝 Descrição do Projeto

Este repositório contém o plano de rede elaborado para o sistema de informações da empresa mencionada na atividade MAPA, em atendimento aos requisitos da disciplina de
**Arquitetura e Rede de Computadores** da Unicesumar. 
O objetivo foi projetar uma rede de dados interligando diversos dispositivos e setores, guiados por um conjunto de regras para compartilhar entre si informação, serviços e, recursos físicos e lógicos[cite: 4, 5].

O projeto inclui um esboço visual da instalação e um detalhamento por setor.

## 🗺️ Estrutura da Rede

A rede é centralizada em um Servidor Central e utiliza cabeamento estruturado para conectar os diferentes setores e equipamentos.

### 📊 Distribuição de Estações e Equipamentos 

| Sala/Setor | Estações de Trabalho | Equipamentos | Pontos de Cabo (Direto do Servidor) | Total de Cabos (Metros) |
| :--- | :--- | :--- | :--- | :--- |
| **TI** | 5 | 1 Servidor Central, 5 Pontos de cabo | Portas 1, 2, 3, 4 e 5 | 42 m |
| **ADM** | 5 | 5 Pontos de cabo | Portas 9, 10, 11, 12 e 13 | 55 m |
| **Desenvolvimento** | 30 | 2 Roteadores Wi-Fi Wireless 4 Antenas | Portas 15 e 16 (para o modem) | 80 m |
| **Recepção** | 1 | 1 Ponto de cabo | Porta 22 | 56 m |
| **Relógio de Ponto** | 0 | 1 Ponto de cabo | Porta 17 | 56 m |
| **Reunião 2** | 0 | 1 Roteador Wi-Fi, 3 Pontos de cabo | Portas 6, 7 (uso) e 8 (roteador) | 15 m |
| **Reunião 1** | 0 | 1 Roteador Wi-Fi, 1 Ponto de cabo | Porta 14 (para roteador) | 22 m |

### 🔗 Detalhes de Conexão e Cabeamento

O cabeamento total foi dividido entre conexões diretas do servidor e conexões que passam por replicação de sinal:

Cabos Diretos do Servidor (Sem replicação):** Ao todo, 16 cabos, totalizando 219 metros de cabo.
Cabos com Replicação de Sinal:** Ao todo, são 26 cabos, totalizando 107 metros de cabo.

**Observação Específica:**
O cabo que sai direto do servidor central para o relógio de ponto mede 56m e está ligado à porta 17 do mesmo.

## 🚧 Observações do Esboço (Layout)

O layout da rede pode ser visualizado na imagem do esboço da instalação 
<br> </br>
<img width="419" height="457" alt="Image" src="https://github.com/user-attachments/assets/55b6f0c0-6618-44a4-8669-aefad5856ce7" />
 <br> </br>

As linhas coloridas no esboço representam o caminho do cabeamento , que, na instalação real, deve seguir por
**dentro das paredes**. 
A representação externa foi utilizada para mostrar o caminho percorrido por cada cabo, devido à falta de legibilidade caso fossem sobrepostos nas paredes do desenho.

### Legenda de Cores dos Cabos no Esboço:

* **Laranja:** Sala de ADM
* **Verde Claro:** Sala de Reunião 2
* **Vermelho:** Sala de TI
* **Azul:** Sala de Reunião 1
* **Verde Escuro:** Relógio de Ponto
* **Preto:** Sala de Desenvolvimento
* **Roxo:** Recepção

## 🎓 Autor e Detalhes

Aluno: Madison Santos Oliveira 

R.A: 1760558-5 

Disciplina:** Arquitetura e Rede de Computadores 

Instituição:Unicesumar 


       

