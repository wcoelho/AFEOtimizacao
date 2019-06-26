# Arquitetura de Software Distribuído - Oferta 11
# Arquitetura de Front-End
Pontifícia Universidade Católica de Minas Gerais  


## Laboratório 2 - Otimização de sites

## Alunos
Bruno Augusto  
Dalmo Melo    
Walter Coelho  

## Primeira Etapa
- Site original, sem melhorias.  

**Pontuação**

![alt text](report/score_1o_Estagio.JPG)

**Estatística**

126 requests | 30.3kB transferred | 4.5MB resources | Finish: 3.25s | DOMContentLoaded: 2.89s | Load: 3.13s

## Segunda Etapa  

**Melhorias aplicadas**  
- Utilizados links com https.
- Utilizada URL real/existente no link relativo ao rel="canonical".  
- Movidos blocos de script para o fim do arquivo index.html.  
- Movidos blocos de style e css para o início do arquivo index.html.  
- Removidos css não utilizados.
- Removidos Ids repetidos.
- Utilizado aria-label nos links \<a\>.
- Utilizado aria-label nos inputs.
- Adicionado rel='noopener' nos links externos.
- Adicionado novo arquivo jQuery minified - 3.4.1.
- Adicionadas imagens perdidas.
- Adicionado sinalizador passive ao addEventListener.

*Nota:* Tentamos utilizad https no Live Server, sem sucesso.  

**Estratégias**

- Compactação de arquivos JavaScript e CSS via minificação.  
- Eliminação de regras CSS não utilizadas.  
- Aplicação do protocolo HTTP2 no servidor ao invés do HTTP1/1.   
=> Feita a configuração para o LiveServer do VSCode, mas o audit não funcionou.

**Pontuação**

![alt text](report/score_2o_Estagio.JPG)

**Estatística**

119 requests | 243kB transferred | 2.7MB resources | Finish: 2.63s | DOMContentLoaded: 2.63s | Load: 2.92s  
  

## Terceira Etapa  

**Melhorias aplicadas**  
- Arquivos js e css restantes minificados.  
- Imagens jpg e png substituídas pelo formato moderno jp2.  
- Compactação do HTML.  

**Estratégias**

- Compactação de arquivos HTML via minificação. 
- Compactação de arquivos JavaScript e CSS via minificação.  
- Compactação de imagens.  

**Pontuação**

![alt text](report/score_3o_Estagio.JPG)

**Estatística**  

120 requests | 246kB transferred | 2.4MB resources | Finish: 3,00s | DOMContentLoaded: 2.50s | Load: 2.97s
