---?image=assets/image/capa_slide.jpg

<font color="white"> Estado do desenvolvimento do DSGTools </font>
<br>
<font color="white"> 1º Ten Borba </font>
<br>
<font color="white"> 1º Ten Esperidião </font>

---?image=assets/image/sumario_slide.jpg

## Sumário

+ Objetivos;
+ Equipe do Projeto;
+ Lançamento do DSGTools 3.1:
 - Novas funcionalidades;
 - Melhorias;
 - Correção de bugs;
+ Versão em trabalho: DSGTools 3.2;
+ Lançamentos futuros (_Roadmap_);
+ Acompanhamento do Projeto;
+ Como contribuir?

---
## Objetivos
+ Apresentar o estado atual do Projeto SIG Desktop; |
+ Apresentar o DSGTools 3.1; |
+ Apresentar as funcionalidades previstas para a versão 3.2; |
+ Apresentar o Roadmap do projeto; |
+ Apresentar as formas de contribuição com o projeto; |

---
## Projeto SIG Desktop
+ 1º Ten Borba (Gerente) e 1º Ten Esperidião (Adjunto) |
+ Colaboradores: |
 - Cap Luiz Claudio (2º CGEO); |
 - Cap Diniz (1º CGEO); |
 - 2º Sgt Wallace (2º CGEO); |
 - 3º Sgt Jossan (1º CGEO); |
 - outros militares; |
---
## DSGTools 3.1
+ Novas funcionalidades;|
+ Correção de bugs (versão atual 3.1.3);|
+ Melhorias de usabilidade;|

---

## DSGTools 3.1: Novas Funcionalidades

---
@title[Novo modelo de banco]
### Novo Modelo de banco de dados: EDGV 3.0
@fa[arrow-down]
+++ 
* Homologado em dezembro de 2017;
* Aborda o sistemático e o grandes escalas; |
* Quantidade de Classes maior que a 2.1.3; |
* Bye bye Gothic? |
* Desafios: Nova validação e edição para a EDGV 3.0. |

---
@title[Novos processos de validação]
### Novo processo de validação: Unir Linhas com Atributos Comuns
@fa[arrow-down]
+++ 
+ Conecta linhas baseado no conjunto de atributos; 
+ Lista de exclusão de atributos a serem considerados; |
+ Procedimento de limpeza é executado após o procedimento. |
+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/merge_lines.gif?raw=true" width="800" height="500">

---

### Novo processo de validação: Identificar Pontas Soltas
@fa[arrow-down]
+++ 
+ Indica problemas de conectividade; 
+ Raio de busca; |
+ Camadas de filtro (retira falsos-positivos); |
+ Tipo de identificação. |
+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/identify_dangles.gif?raw=true" width="800" height="500">

---

### Novo processo de validação: Seccionar Linhas com Linhas
@fa[arrow-down]
+++ 
+ Quebrar linhas nas intersecções;
+ Semelhante ao Line on line overlayer do FME. |

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/line_on_line_overlay.gif?raw=true" width="800" height="500">

---

### Novo processo de validação: Cortar Elementos Utilizando Áreas como Referência
@fa[arrow-down]
+++ 
+ Processo que consiste cortar um conjunto de feições de acordo com as feições da camada de referência
+ Duas opções: |
 - Manter os elementos fora da referência, e
 - Descartar os elementos fora da referência.

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/overlay_areas_with_elements.gif?raw=true" width="800" height="500">

---

### Novo processo de validação: Identificar Buracos e Sobreposições em Camadas de Cobertura Terrestre
@fa[arrow-down]

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/earth_coverage_gaps_and_overlaps.gif?raw=true" width="800" height="500">

---

### Novo processo de validação:  Identificar Buracos em Camadas

---

### Novo processo de validação: Identificar Sobreposições em Camadas

---
@title[Melhorias]
## DSGTools 3.1: Melhorias

---
### Ferramenta de seleção genérica 

+ Agora abre um menu para que o usuário escolha a feição a ser selecionada quando há múltiplas opções para a seleção

@fa[arrow-down]

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/layer_selection.gif?raw=true" width="800" height="500">

---

### Ferramenta de área mínima
+ Agora permite rotação do gabarito

@fa[arrow-down]

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/rotate_shape.gif?raw=true" width="800" height="500">

---

### Ferramenta de aquisição em ângulos retos 

+ Agora permite aquisição de linhas

@fa[arrow-down]

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/right_angle_with_lines.gif?raw=true" width="800" height="500">

---

### Ferramenta de aquisição de círculos 

+ Agora permite aquisição de linhas

@fa[arrow-down]

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/circle_with_lines.gif?raw=true" width="800" height="500">

---

### Nova interface para configuração dos Ajustes para a Ferramenta de (Re)Classificação
@fa[arrow-down]
+++
+ Escolha de atributos não editáveis;
+ Escolha de atributos a serem ignorados; |
+ Escolha da abertura ou não do formulário após digitalização; |
+ Atribuição de cores; |
+ Atribuição de dica de uso (tooltip); |

+++ 
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/gifs/new_field_toolbox_config.gif?raw=true" width="800" height="500">

---

### Melhorias para a Caixa de Ferramentas de Validação
@fa[arrow-down]
+++
+ A caixa de ferramentas de validação agora mostra o tempo gasto na execução do processo de validação;
+ Nova funcionalidade de limpar flags pelo tipo; |
+ Nova funcionalidade de limpar todas as flags; |
+ Nova funcionalidade de filtrar flags pelo tipo; |
+ Novo histórico de validação; |

---

### DSGTools 3.2: Em desenvolvimento

+ Lançamento previsto para Agosto de 2018; |
+ Principal foco: Validação topológica; |
+ Quais funcionalidades? |
@fa[arrow-down]
+++

+ Snap Hierárquico
@fa[arrow-down]
+++

+ Validação de atributos
@fa[arrow-down]
+++

+ Direcionamento de Trechos de Drenagem
@fa[arrow-down]
+++

+ Procedimentos de desconstrução de polígonos
@fa[arrow-down]
+++

+ Workflow de validação
@fa[arrow-down]
+++

+ Melhorias na interface de validação
@fa[arrow-down]
+++

+ EDGV Pro 2.1.3
+ EDGV Pro 3.0
@fa[arrow-down]
+++

+ Ferramenta de Aquisição em Mão Livre
@fa[arrow-down]
+++

+ Configurador de parâmetros para o operador
@fa[arrow-down]
---

### Roadmap
@fa[arrow-down]
+++

+ DSGTools 3.3
 - Migração para o QGIS 3.0;
 - Reorganização do código;
 - Melhorias na ferramenta de conversão;
@fa[arrow-down]
+++

+ DSGTools 3.4
 - Ferramentas de Edição;
 - Melhorias de uso;
@fa[arrow-down]
+++

+ DSGTools 3.5
 - Banco de topônimos;
 - Relatórios para a produção;
 - Melhorias de uso;
@fa[arrow-down]
---

### Acompanhamento do projeto (github)
@fa[arrow-down]
+++
+ Público: possibilidade de verificar a execução das demandas;
@fa[arrow-down]
+++
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/tickets.png?raw=true">
+++

+ Possibilidade de reportar bugs e solicitar melhorias
@fa[arrow-down]
+++
<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/issues.png?raw=true">

---

### Como contribuir?

+++

<img src="https://github.com/phborba/presentation_test/blob/master/assets/image/would-you-please-help-me.jpg?raw=true">

---?image=assets/image/slide_final.jpg