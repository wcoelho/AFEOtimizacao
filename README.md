# Arquitetura de Fron End - Otimizacao

## Melhorias aplicadas  
- Utilizados links com https.
- Utilizada URL real/existente no link relativo ao rel="canonical".
- Movidos style e script para parte inferior do html.
- Removidos css não utilizados.
- Removidos Ids repetidos.
- Utilizado aria-label nos links \<a\>.
- Utilizado aria-label nos inputs.
- Adicionado rel='noopener' nos links externos.
- Adicionado novo arquivo jQuery minified - 3.4.1.
- Adicionadas imagens perdidas.
- Adicionado sinalizador passive ao addEventListener.
- Utilizado https no Live Server.

## Estratégias

1)Estratégias de compactação  
a.Compactação de arquivos HTML, JavaScript e CSS via minificação  
=> Feito Parcialmente, ainda há arquivos a compactar


3)Estratégias avançadas

b.Eliminação de regras CSS não utilizadas  
=> Regras Eliminadas

c.Aplicação do protocolo HTTP2 no servidor ao invés do HTTP1/1   
=> Feita a configuração para o LiveServer do VSCode, mas o audit não funcionou.


