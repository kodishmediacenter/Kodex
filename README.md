# kodex 

Linguagem Codificação baseada em prompts para IA converter em HTML
<pre>
[] = inicia o comando kodex
name = Titulo da pagina <title></title>
normal = texto tamanho normal 
tamB = h3
tamA = h2
tamS = h1
pular linha = <br>
link = inserir um hiperlink  
imagem = inseerir uma figura
centro = centralizado
esquerda = alinhado a esquerda 
direita  = alinhado a direita
topicos  = Coloca o conteudo em topicos onde a virgula é novo topico
stopico  = é sub topico 
tabela   = os campos da tabela [tabela:bordaON] com borda e [tabela:bordaOFF sem Borda] as colunas usa virgula e linha
procede apos um ponto e virgula
:        = Separação comando e conteudo 
cordefundo = nome da cor de fundo em portugues ou inglês ou Hexadecimal -> [cordefundo:azul]
cordafonte = nome da cor do texto em portugues ou inglês ou Hexadecimal -> [cordafonte:azul]
formulario = todos campos separado por virgula depois {Metodo de Envio [get ou post]}
f{}        = Tipo de formulario password / e-mail / number (exclusivo para numero) / date / checkbox / radio / file (Upload de arquivos)
no caso f{} só necessario para um fim especifico caso contrario entenda-se como text
flista     = lista suspensa todos topicos com separação de virgula
flistaBR   = lista suspensa de Estados brasileiros sendo , [flistaBR:siglas] sendo siglas dos estados Brasileiros caso 
flistaGlobo = lista de paises do mundo 
flistaUS    = lista os Estados do Estados Unidos
flistaPTG   = lista os Distritos de Portugal e Regiões Autonomas
flistaQMC   = lista de elementos da tabela periodica
flistaLGBT  = lista de generos LGBT
fcbox       = caixa de texto
contrario seria o nome completos dos estados.  [flistaBR:nominal] 
:siglas  -> Separar por siglas
:nominal -> Separar por nome extenso de forma nominal
embedVideo -> Inseri o Video do youtube e afins
pre -> Conteudo texto puro sem formatação
italico -> Deixa o Texto em italico 
negrito -> Deixa o Texto em negrito 
alias   -> converter processo no prompt em instrução
stringhtml -> Converta palavras acentuadas para converter para padrão html exemplo João -> Jo&atilde;o
youvideo -> Embedar o video do youtube seguindo formato padrão do youtube 
myouvideo -> converta url do youtube criando [alias:[imagem:"https://i.ytimg.com/vi_webp/oDvgftwzKAc/maxresdefault.webp"][pular linha][link:Abra o Video:https://www.youtube.com/watch?v=oDvgftwzKAc]]
pagenext  = Proxima pagina gera outro arquivo
tamanho   = define o tamanho da imagem

</pre>
