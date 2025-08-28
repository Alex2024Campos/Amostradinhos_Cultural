<p align="center">
  <img src="https://i.ibb.co/56s7K8j/292330192-445386850928422-7259301303587158181-n-jpg.png" alt="Minimalist RPG GDD Banner">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Versão-0.2.9-blue?style=for-the-badge" alt="Versão">
  <img src="https://img.shields.io/badge/Markdown-%23%23302c9b.svg?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">

</p>

## Grupo:

 Alex Campos de Oliveira
 
 Felipe Mussato Rodrigues
 
 Guilherme Henrique Lemes de Souza
 
 Kauan Merida



## Estrutura do Documento

O template é dividido nas seguintes seções principais:
1. **Informações Gerais:** Detalha as informações básicas sobre o jogo, como título, plataforma, gênero e público-alvo.
2. **Mecânicas de Jogo:** Descreve as regras, controles, objetivos, sistema de pontuação, interações, progressão, IA, dinâmicas e economia do jogo.
3. **Narrativa:** Apresenta a história principal, personagens, cenários, missões e diálogos do jogo.
4. **Design de Níveis:** Estrutura, mapas, desafios, fluxo e balanceamento de dificuldade dos níveis.
5. **Arte e Estilo Visual:** Detalha o estilo artístico, personagens, cenários, interface do usuário e paleta de cores.
6. **Áudio:** Descreve a trilha sonora, efeitos sonoros, dublagem e som ambiente.
<!--7. **Progresso e Salvamento:** Explica os sistemas de progressão e salvamento do jogo.
8. **Monetização:** Detalha o modelo de negócio e itens pagos.
9. **Testes e Qualidade:** Plano de testes e coleta de feedback dos jogadores.
10. **Conclusão:** Resume os principais pontos do GDD e os próximos passos no desenvolvimento do jogo.
-->
# Sumário

1. [Informações Gerais](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/1.-Informa%C3%A7%C3%B5es-Gerais)<br>
    1.1. [Título do Jogo](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/1.-Informa%C3%A7%C3%B5es-Gerais#11-título-do-jogo)<br>
    1.2. [Plataforma](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/1.-Informa%C3%A7%C3%B5es-Gerais#12-plataforma)<br>
    1.3. [Gênero](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/1.-Informa%C3%A7%C3%B5es-Gerais#13-gênero)<br>
    1.4. [Público-Alvo](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/1.-Informa%C3%A7%C3%B5es-Gerais#14-público-alvo)<br>
    1.5. [Visão Geral do Jogo](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/1.-Informa%C3%A7%C3%B5es-Gerais#15-visão-geral-do-jogo)<br>

2. [Mecânicas de Jogo](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/2.-Mecânicas-de-Jogo)<br>
    2.1. [Regras Básicas](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/2.-Mecânicas-de-Jogo#21-regras-básicas)<br>
    2.2. [Controles](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/2.-Mecânicas-de-Jogo#22-controles)<br>
    2.3. [Objetivos e Metas](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/2.-Mecânicas-de-Jogo#23-objetivos-e-metas)<br>

3. [Narrativa](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/3.-Narrativa)<br>
    3.1. [História Principal](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/3.-Narrativa#31-história-principal)<br>
     3.2. [Personagens](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/3.-Narrativa#32-personagens)<br>
    3.3. [Cenários](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/3.-Narrativa#33-cenários)<br>
    3.4. [Missões e Quests](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/3.-Narrativa#34-missões-e-quests)<br>

4. [Design de Níveis](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/4.-Design-de-Níveis)<br>
    4.1. [Estrutura dos Níveis](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/4.-Design-de-Níveis#41-estrutura-dos-níveis)<br>
    4.2. [Mapas e Layouts](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/4.-Design-de-Níveis#42-mapas-e-layouts)<br>

5. [Arte e Estilo Visual](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/5.-Arte-e-Estilo-Visual)<br>
    5.1. [Estilo Artístico](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/5.-Arte-e-Estilo-Visual#51-estilo-artístico)<br>
    5.2. [Personagens e Animações](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/5.-Arte-e-Estilo-Visual#52-personagens-e-animações)<br>
    5.3. [Cenários e Ambientes](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/5.-Arte-e-Estilo-Visual#53-cenários-e-ambientes)<br>
    5.4. [Interface do Usuário (UI)](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/5.-Arte-e-Estilo-Visual#54-interface-do-usuário-ui)<br>
    5.5. [Paleta de Cores](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/5.-Arte-e-Estilo-Visual#55-paleta-de-cores)<br>

6. [Áudio](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/6.-Áudio)<br>
    6.1. [Efeitos Sonoros](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/6.-Áudio#62-efeitos-sonoros)<br>

7. [Codificação](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/7.-Codifica%C3%A7%C3%A3o)<br>
   7.1. [Movimentação](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/7.-Codifica%C3%A7%C3%A3o#71-movimenta%C3%A7%C3%A3o)<br>
   7.2. [Combate](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/7.-Codifica%C3%A7%C3%A3o#72-combate)<br>
   7.3. [Chicote](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/7.-Codifica%C3%A7%C3%A3o#73-lan%C3%A7ar-chicote)<br>
   7.4. [Diálogo](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/7.-Codifica%C3%A7%C3%A3o#74-di%C3%A1logo)<br>

8. [Floresta](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/8.-Floresta)<br>
   8.1. []()<br>
   8.2. []()<br>
   8.3. []()<br>
   8.4. []()<br>
   8.5. []()<br>
   8.6. []()<br>
9. [Vila Indígena](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/9.-Vila-Ind%C3%ADgena)<br>
   9.1. []()<br>
   9.2. []()<br>
   9.3. []()<br>
   9.4. []()<br>
   9.5. []()<br>
   9.6. []()<br>
   
10. [Cidade-de-Deus](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/10.-Cidade-de-Deus)
   10.1. []()<br>
   10.2. []()<br>
   10.3. []()<br>
   10.4. []()<br>
   10.5. []()<br>
   10.6. []()<br>
   
11. [Arena](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/11.-Arena)
   11.1. []()<br>
   11.2. []()<br>
   11.3. []()<br>
   11.4. []()<br>
   11.5. []()<br>
   11.6. []()<br>

12. [Diagrama-de-Classes-UML](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/12.-Diagrama-de-Classes-UML)
    12.1. []()<br>
    12.2. []()<br>
    12.3. []()<br>
    12.4. []()<br>
    12.5. []()<br>
    12.6. []()<br>

14. [Referências](https://github.com/Alex2024Campos/Amostradinhos_Cultural/wiki/13.-Refer%C3%AAncias)
    14.1. []()<br>
    14.2. []()<br>
    14.3. []()<br>

