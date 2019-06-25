# Arquitetura de Software Distribuído - Oferta 11
# Arquitetura de Front-End
Pontifícia Universidade Católica de Minas Gerais  


## Laboratório 2 - Otimização de sites

## Alunos
Bruno Augusto  
Dalmo Melo Pereira da Rocha  
Walter Coelho

## Melhorias aplicadas  
**Primeira Etapa**  
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
- Utilizado https no Live Server.  

**Segunda Etapa**  
- Arquivos js e css restantes minificados.  
- Imagens jpg e png substituídas pelo formato moderno jp2.  

## Estratégias

1) Estratégias de compactação  
- Compactação de arquivos HTML, JavaScript e CSS via minificação  
=> Feito  
- Compactação de imagens  
=> Feito em algumas imagens  

2) Estratégias avançadas

- Eliminação de regras CSS não utilizadas  
=> Regras Eliminadas

- Aplicação do protocolo HTTP2 no servidor ao invés do HTTP1/1   
=> Feita a configuração para o LiveServer do VSCode, mas o audit não funcionou.
