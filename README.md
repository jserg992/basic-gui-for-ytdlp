Fiz esse GUI, utilizando Claude, basicamente estava cansado de programas que baixem vídeo durante um certo tempo e parem do nada.
Assim fiz esse programa, que você consegue atualizar manualmente cada modulo dele. yt-dlp e ffmpeg.
Outras solucoes para resolver os problemas de downloads de vídeo do youtube (tipo deno) são direto no PATH.

Funções:
- Cookies
- Modo de download áudio e vídeo separados.
- Seleção de qualidade de download + escolha por formatos (as vezes o melhor arquivo não é o que ele determina, por exemplo vídeos que contem qualidade aprimorada não são a primeira opção))
- Reenconder de áudio e vídeo nativo via ffmpeg. (H265/H265 com e sem GPU. PCM, AAC, MP3)
- Fila de download e Log

ATT Futuras.
Melhora de interface > Torna-lá mais bonita e moderna e facilitar o caminho para cada ação.
Implementar atualização automatica do projeto.
Implementar busca automatica por atualizacoes no yt-dlp.
