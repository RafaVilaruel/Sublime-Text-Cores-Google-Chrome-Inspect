# Sublime-Text-Cores-Google-Chrome-Inspect
Tema criado pelo Tonsky: https://github.com/tonsky/sublime-scheme-alabaster

**Editado por mim para que tenha as exatas cores do Google Chrome Inspect**

**Segue tradução + texto original**

-´----------------------------------------------------------------------

Um esquema de cores claras com quantidade mínima de destaque para o Texto Sublime 3.

-------------Motivação-----------------------------------------------------

A maioria dos esquemas de cores destaca tudo o que pode, acabando parecendo um show de fogos de artifício.

Em vez disso, o Alabaster usa realce mínimo; define apenas quatro classes:

Cordas
Todas as constantes conhecidas estaticamente (números, símbolos, palavras-chave, valores booleanos)
Comentários
Definições globais

-------------------------------------------------- -----------------
Além disso:
-------------------------------------------------- ----------------

O Alabaster não destaca palavras-chave do idioma padrão (se, senão, função, etc.). Eles geralmente são a parte menos importante e mais óbvia de qualquer programa.

Alabaster destaca comentários. A maioria dos esquemas tenta diminuir os comentários usando cinzas de baixo contraste. Acho que se o código era complexo o suficiente para merecer uma explicação, é essa explicação que devemos ver e ler primeiro. Seria um crime escondê-lo.

Alabaster não usa variações de fonte. É difícil escanear códigos quando alterna entre normal, negrito e itálico o tempo todo. Além disso, nem todas as fontes fornecem variantes em negrito / itálico.

Ter uma quantidade mínima de regras significa que você pode usá-las conscientemente para procurar a informação exata de que precisa. A maioria dos outros esquemas de "fogos de artifício" fornece apenas uma contribuição significativa: se colorida, provavelmente está sintaticamente correta. Em vez disso, no Alabaster, você pode se lembrar de todas as regras e, por exemplo, se você precisar procurar uma string, sabe que está procurando um token verde. E todas as cordas realmente saem porque não há muitas outras coisas destacadas.

O Alabaster destaca apenas as coisas que o analisador pode identificar de maneira confiável. Acredito que, se destacar apenas parcialmente, faz mais mal do que bem. Quando o destaque funciona de maneira confiável, seu cérebro aprende a confiar nele. Quando não é confiável, seu cérebro gasta preciosos ciclos cerebrais para verificar novamente tudo o que vê na tela.
-------------------------------------------------- -------------------------------------------------- -

Faça o download dos arquivos * .sublime-color-schema deste repositório.
Selecione Preferências? Procure pacotes no menu principal.
Copie os arquivos do esquema * .sublime para Pacotes / Usuário /.
Selecione Preferências? Esquema de cores ... e escolha Alabaster ou Alabaster BG no menu.

==========================================================================================================

Alabaster Color Scheme

A light color scheme with minimal amount of highlighting for Sublime Text 3.

-------------Motivation------------------------

Most color schemes highlight everything they can, ending up looking like a fireworks show.

Instead, Alabaster uses minimal highlighting; it defines just four classes:

Strings
All statically known constants (numbers, symbols, keywords, boolean values)
Comments
Global definitions

-------------------------------------------------------------------
Additionally:
------------------------------------------------------------------

Alabaster does not highlight standard language keywords (if, else, function, etc). They are usually least important and most obvious part of any program.

Alabaster highlights comments. Most schemes try to dim comments by using low-contrast greys. I think if code was complex enough that it deserved an explanation then it’s that explanation we should see and read first. It would be a crime to hide it.

Alabaster doesn’t use font variations. It’s hard to scan code when it jumps between normal, bold and italics all the time. Also, not all fonts provide bold/italics variants.

Having minimal amount of rules means you can consciously use them to look for the exact piece of information you need. Most other “fireworks” schemes provide only one meaningful contribution: if it’s colored it’s probably syntactically correct. Instead, in Alabaster you can actually remember all the rules, and e.g. if you need to look for a string you know that you’re looking for a green token. And all the strings really pop out because there are not many other things highlighted.

Alabaster only highlights things that parser could identify reliably. I believe that if highlighting works only partially then it does more harm than good. When highlighting works reliably, your brain learns to rely on it. When it’s not reliable, your brain spends precious brain cycles to re-check everything it sees on the screen.
------------------------------------------------------------------------------------------------------

Download *.sublime-color-scheme files from this repo.
Select Preferences ? Browse packages from the main menu.
Copy *.sublime-color-scheme files to Packages/User/.
Select Preferences ? Color Scheme ... and pick Alabaster or Alabaster BG from the menu.
