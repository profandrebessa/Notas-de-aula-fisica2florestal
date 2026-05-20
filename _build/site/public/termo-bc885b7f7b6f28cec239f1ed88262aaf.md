
# Balanço energético na natureza

## Introdução

Como uma planta regula sua temperatura? O que é ponto de orvalho? Por que noites nubladas são mais quentes? 

A resposta a todas essas perguntas envolve as forças gravitacional e eletromagnética. Porém, as respostas serão obtidas de modo mais natural em termos da contabilidade de energia.

Antes de iniciarmos essa contabilidade, vamos ver algumas definições e princípios fundamentais.

#### Sistema

É a porção de matéria que está sendo estudada. A depender da situação, o sistema pode ser uma massa de solo, uma massa de ar, um célula, uma planta, o cômodo de uma casa, a atmosfera, o planeta inteiro, etc.

Analisemos a contabilidade da energia do sistema e suas trocas com a sua **vizinhança**.


#### O que é energia?

Energia é um conceito que nasce na Mecânica para medir a quantidade de movimento de um conjunto de partículas. Estamos falando da energia cinética (energia da matéria em movimento). Uma partícula de massa $m$ com velocidade $v$ tem energia cinética:
\begin{equation}
K = \frac{1}{2}mv^2\;\;\;\hbox{(energia cinética)}.
\end{equation}
A unidade padrão da energia cinética é o **Joule**. 

Exemplo: uma pedra de 1 kg atinge o chão com velocidade de 3 m/s. Qual era a sua energia cinética? 
\begin{equation}
K = 0,5*(1\,kg)*(3\,m/s)^2= 4,5\,J\,.
\end{equation}

#### Experimento mental

Dois corpos grandes como planetas estão distantes e se movem, se aproximando. Inicialmente, um tinha energia cinética $K_1$ e o outro, $K_2$. A energia cinética combinada era $K_{12}=K_1+K_2$. A trajetória dos planetas é tal que eles se aproximam. Pela força da gravidade, um sente a presença do outro. Suas velocidades se alteram. Neste momento, a soma das energias cinéticas não é mais a mesma de antes. Após um tempo, cada um segue uma trajetória e eles se afastam. Ao fim, a energia cinética do planeta 1 vai ser $K'_1\neq K_1$ e a do planeta 2 será $K_2' \neq K_2$. Porém, $K_1'+K_2' = K_1+K_2$. 

Concluímos que, enquanto interagiam, a contabilidade de energia ainda pode ser feita, embora ela não seja apenas cinética. A diferença na contabilidade ganha um nome: **energia potencial**.

Assim, quando um objeto de massa $m$ é atirado para o alto, ele parte com uma velocidade alta e tem uma certa energia cinética. À medida em que sobe, sua energia cinética diminui. Em termos de contabilidade de energia, dizemos que aumentou a **energia potencial gravitacional** do corpo na interação com o planeta Terra. 

Nas proximidades da superfície da Terra, a energia potencial gravitacional é dada por:
\begin{equation}
U_g = mgh\;\;\;\hbox{(energia potencial gravitacional)}.
\end{equation}
A contabilidade é tal que:
\begin{equation}
\frac{1}{2}mv^2 + mgh \approx \hbox{ constante}.
\end{equation}
No ponto mais alto, a energia cinética é zero e a potencial é máxima. Na descida, a energia cinética volta a aumentar e a potencial diminui.

A soma da energia cinética com a potencial não é exatamente constante porque perdemos parte da contabilidade. De fato, a presença do ar faz com que parte da energia na subida e descida seja transferida para o movimento do ar em volta do objeto. Isso fica bem perecetível quando um objeto se move na água.

Quando objeto chega no chão sua energia cinética vai a zero e a potencial será mínima? Como fica a contabilidade de energia? Para ficar completa, a contabilidade de energia não pode se resumir a acompanhar a energia cinética e potencial gravitacional de pedras, pássaros, etc. Precisamos mergulhar na formas de energia interna dos corpos.


## Energia interna do sistema

A **energia interna** de um sistema se ditribui nas seguintes formas:

- **Energia cinética de agitação dos átomos e moléculas que compõe o sistema.**
:::{figure} ./_static/gas3.mp4
---
width: 80%
figclass: margin-caption
name: gas3
---
Simulação do movimento de agitação térmica de átomos e moléculas.
:::

Átomos e moléculas têm massa e estão em movimento. Portanto, têm energia cinética. A **energia cinética média** associada à agitação das particulas de um sistema é a **temperatura**. Quando a temperatura aumenta é porque aumentou a energia cinética média de agitação. Dizemos que a água foi aquecida.

- **Energia potencial nas ligações químicas das substâncias que compõem o sistema.** 
    
:::{figure} ./_static/energiaglicosequebra.png
---
width: 500px
name: energiaglicosequebra
---
A energia guardada na molécula de glicose é maior do que a energia guardada nas moléculas de gás carbônico $CO_2$ e de água $H_2O$.
:::
Assim como uma mola dura comprimida tem mais energia potencial elástica que uma mola mole igualmente comprimida, diferentes ligações químicas guardam quantidades diferentes de energia.
   
Exemplo aplicado: o floema tem mais energia química do que o xilema. A diferença da energia química das moléculas foi adquirida na fotossíntese.

- **Energia potencial na organização coletiva das moléculas.**

:::{figure} ./_static/energiaagualiquidogas.png
---
width: 400px
name: energiaagualiquidogas
---
A água na fase líquida tem energia guardada nas interações entre as moléculas. Na fase gasosa, praticamente não há essas ligações.
:::

A depender da forma como os átomos e moléculas se organizam, a energia pode variar. Assim, moléculas de água organizadas na fase sólida (gelo) têm uma energia de organização diferente de quando estão na fase líquida ou gasosa. Isso ocorre porque muda a forma das ligações **intermoleculares** (entre os átomos e moléculas).

#### Equilíbrio termodinâmico

Todo sistema, após um certo tempo, tende a uniformizar suas propriedades. Sistemas simples, como água contida em um recipiente, podem ser caracterizados por algumas poucas variáveis, como o volume, a pressão, a energia e a temperatura. 

#### Escalas de temperatura

A escala que usamos no dia-a-dia é a escala **Celsius**. Assim, sob pressão atmosférica, dizemos que a temperatura em que a água se solidifica em gelo é $0^\circ C$. A temperatura de ebulição da água é $100^\circ C$. 

Uma escala mais interessante do ponto de vista da compreensão dos fenômenos é a escala Kelvin. A temperatura de solidificação da água é $273,15K$. A temperatura de ebulição é $373,15K$. 

Imagine uma situação de um sistema que não tem agitação nenhuma. Tudo em repouso. Na escala Kelvin, sua temperatura seria zero, como esperado. Na escala Celsius, a temperatura correspondente seria $-273,15^\circ C$.

Note que não usamos $100^\circ K$, mas $100K$. Observe também que quando um corpo aumenta a sua temperatura em $1^\circ C$, sua temperatura aumentou em $1K$. Em geral, temos:
\begin{equation}
(T)_{Celsius} \;=\;(T)_{Kelvin} - 273,15\;. 
\end{equation}

## Como variar a energia interna de um sistema?

Considere o sistema formado por um litro de água. Podemos aumentar a energia interna da água fazendo girar uma pá dentro da água, como mostra a figura.
:::{figure} ./_static/energiatrabalhomecanico.png
---
width: 300px
name: energiatrabalhomecanico
---
Quando o bloco cai, faz girar as pás dentro da água. Após um tempo, as pás param de se mover: sua energia cinética foi transferida para a água.
:::

Depois de um tempo, a pá é freada pela água. Pra onde foi a energia cinética da pá? Ela foi transferida para a água. Neste caso, as moléculas da água ficaram mais agitadas: houve aumento da temperatura. Isso acontece porque, ao girar, a pá empurra as moléculas da água, dando energia cinética a elas.

Isso ocorre também quando se comprime um fluido. Veja o que acontece com o gás em um pistão quando ele é comprimido.
:::{figure} ./_static/energiatrabalhocompressao.jpg
---
width: 300px
name: energiatrabalhocompressao
---
Ao comprimir um pistão, damos energia cinética ao gás. Quando o pistão é que empurra e se expande, o gás faz isso com redução da sua energia cinética.
:::
Ao empurrar o pistão, as moléculas do gás são empurradas e ganham energia cinética. Perceba que o oposto pode acontecer: quando gás se expande, o saldo é de um empurrão do gás, que fica com menos energia cinética.

Na natureza, não temos pistões mecânicos como esse. Mas, temos mecanismos de expansão e compressão de um sistema contra a sua vizinhança. Pode ser uma massa de ar que se expande ao se aquecer, pode ser uma célula que se expande quando absorve água. 
 
Esse tipo de transferência de energia em que há forças externas atuando sobre o sistema é chamado de **trabalho**. Dizemos que o trabalho é positivo quando a energia interna do sistema aumenta. O trabalho é negativo quando a energia interna do sistema diminui, como na expansão do gás.

Há, porém, uma forma diferente de variar a energia interna do sistema. Quando o sistema a uma certa temperatura é posto em contato com uma vizinhança que tem uma temperatura diferente, a tendência é que a temperatura se equilibre. Para isso, o sistema com maior energia cinética média (temperatura) fica menos agitado, enquanto o outro fica mais agitado. Esse tipo de troca de energia é chamado de **calor** por condução.

:::{figure} ./_static/energiacalorconducao.png
---
width: 350px
name: energiacalorconducao
---
A figura ilustra a troca de energia que chamamos de calor por condução. As moléculas do sistema $A$ tem energia cinética média maior (veja o tamanho da setinha) que as de $B$. Ao serem colocados em contato térmico (mesmo que na vizinhança) a energia cinética média de $A$ diminui, e a de $B$ aumenta, até que se igualem.
:::

Outro processo de troca de energia envolve radiação. A agitação dos átomos e moléculas é sempre acompanhado de emissão de ondas eletromagnéticas (radiação). Uma característica das ondas eletromagnéticas é a frequência, associada à sensação de cor. Quanto maior a temperatura do corpo, maior a frequência dominante da radiação. O Sol, por ser muito quente, tem cor amarela. Um carvão em brasa, por não ser tão quente, tem frequência dominante no vermelho. Corpos mais frios que a brasa ainda emitem radiação, mas nosso olho não enxerga, pois a frequência dominante é infravermelha. Nosso corpo, por exemplo, emite radiação infravermelha. Vistos por uma câmera de infravermelho (como o olho de um gato), nosso corpo parece uma brasa.

Pode-se mostrar que a radiação também carrega energia, sendo que a energia é maior para frequência maior. Então, dois corpos de temperaturas diferentes podem troca energia por radiação. Chamamos esse processo de **calor** por radiação.

Quando um fluido não está em equilíbrio térmico e possui regiões com diferentes temperaturas, pode se desencadear um mecanismo eficiente de equilíbrio térmico: a convecção. Quando uma chaleira aquece a água, a parte de baixo da água tem uma temperatura mais alta, por estar em contato com o fundo da chaleira. A tendência será essa região quente subir (por ficar menos densa) forçando a parte cima (mais fria) a descer. Estabelece-se um fluxo de matéria. Chamamos esse processo de **calor por conveccção**.
:::{figure} ./_static/energiacalormecanismos.png
---
width: 400px
name: energiacalormecanismos
---
A figura ilustra a troca de energia que chamamos de calor por condução. As moléculas do sistema $A$ tem energia cinética média maior (veja o tamanho da setinha) que as de $B$. Ao serem colocados em contato térmico (mesmo que na vizinhança) a energia cinética média de $A$ diminui, e a de $B$ aumenta, até que se igualem.
:::

Observação: é errado dizer “o sistema tem 100 J de calor”. Calor e trabalho
não são propriedades do sistema em um dado estado. Calor e trabalho são processo de variação de energia.

Apesar disso, utilizaremos as expressões "troca de calor", "fluxo de calor", ou diremos "o calor fluiu
do sistema A para o sistema B", embora o mais correto fosse dizer: "energia foi
transferida do sistema A para o sistema B na forma de calor".

#### A Primeira Lei da Termodinâmica

No balanço da energia de um sistemas, vamos denotar por $W$ o trabalho externo realizado e $Q$ as trocas de energia por calor. Então, a variação da energia interna do sistema total é dada por:
\begin{equation}
\Delta E_{int} = W + Q\;.
\end{equation}
A energia contabilizada como calor será considerada positiva quando a energia está entrando por calor.

#### Capacidade térmica e calor específico

Considere a seguinte situação. Um sistema recebe energia da sua vizinhança. Aguarda-se até que o corpo entre em equilíbrio térmico e mede-se sua nova temperatura, maior. Qual é a relação entre a quantidade de energia fornecida ao sistema e a variação da sua temperatura?

Mais especificamente. quantos joules de energia devemos fornecer ao sistema para elevar a sua temperatura em 1$^\circ$C? 

Essa quantidade varia de um sistema para outro se chama **capacidade térmica** e será representada pela letra $C$.

A capacidade térmica é medida em joules por grau Celsius $J/^\circ C$ ou, equivalentemente, em joules por Kelvin $J/K$. 

Considere um sistema com capacidade térmica $C=12J/^\circ C$. Para aumentasr a sua temperatura em $5^\circ C$ devemos fornecer ao sistema $5\times 12 = 60J$. Em geral, para uma variação de temperatura $\Delta T$ devemos fornecer a seguinte quantidade de energia:
\begin{equation}
Q \;=\;C\;\Delta T.
\end{equation} 
Podemos usar a capacidade térmica para calcular a energia **liberada** pelo sistema ao se resfriar. Se  $C=12J/^\circ C$, para variar a temperatura em $-5^\circ C$ a quantidade de energia envolvida será: $Q = 12\times (-5) = -60 J$. O sinal de menos indica que a energia é liberada pelo sistema.

Um sistema com muita massa vai demandar muita energia para se aquecer ou resfriar. Portanto, massa maior implica em maior capacidade térmica. Assim, a pergunta: "Quem tem maior capacidade térmica, a água ou a areia?" deve ser pensada para igual massa de água e areia. 

Perguntamos, então: quantos joules de energia devemos fornecer a $1 kg$ de uma substância para elevar a sua temperatura em 1$^\circ$C? 

Essa quantidade é uma capacidade térmica por massa e se chama **calor específico**. Ela será representada pela letra $c$, em minúsculo. O calor específico é medido em joules por kg, por grau Celsius $J/(kg^\circ C)$ ou, equivalentemente, em joules por kg, por Kelvin $J/(kg K)$. 

```{table} Tabela com valores típicos de calor específico
| Material | Calor específico ($J/(kg^\circ C$)|
|----------|----------|
| água líquida | 4200     |
| gelo   | 2100 |
| vapor d'água   | 1900 |
| álcool   | 2400 |
| areia   | 800 |
| concreto   | 1000 |
| ferro   | 460 |
| madeira seca  | 2000 |
:name: tab:calorespecifico
```

**Exercício:** 

Uma casa contém $1,0 \times 10^5$ kg de concreto. Quanto calor é liberado pelo concreto à noite, quando ele resfria de $25^\circ$ C para $20^\circ$ C? 

Resolução. Pela tabela, cada quilograma de concreto libera $1 kJ = 1000 J$ ao baixar sua temperatura em $1^\circ C$. No exercício, a queda de temperatura é de $5^\circ C$. Assim, cada quilograma de concreto vai liberar $5 kJ$ de energia. Mas, a massa de concreto é $10^5 kg$. Portanto, a energia total liberada será: $10^5\times 5 kJ = 5\times 10^8 J$, que pode ser escrito como $800 MJ$ (mega joule).

Pela tabela, vemos que a água líquida demanda muita energia para ser aquecida. Por exemplo, uma massa de areia demanda $5$ vezes menos energia para se aquecer do que a mesma massa de água. Visto de outra maneira, se fornecemos uma mesma quantidade de energia para uma massa de areia e para uma massa correspondente de água, a variação da temperatura da areia será cinco vezes maior.

Os oceanos, por terem grande massa de água absorvem grandes quantidades de calor sem variar significativamente sua temperatura. Dizemos que são ** **reservatórios térmicos**. Em tempos de aquecimento global do planeta, eles mantém a temperatura ambiente sem grandes variações. Essa inércia térmica que os oceanos proporcionam poderá vir a ser um problema pois, uma vez aquecidos, levará anos para que, revertendo-se a tendência de aquecimento global, a Terra volte a se resfriar.


#### Energia e mudanças de fase

Pode ocorrer de fornecermos grandes quantidades de energia a um sistema e sua temperatura permanecer constante, mesmo que ele não seja um reservatório térmico! Isso é sinal de que o sistema está passando por transformações em sua estrutura interna, isto é, por uma mudança de fase. A energia recebida pelo sistema não vai se distribuir na forma de mais agitação microscópica. Ela vai ser usada para romper ligações internas que mantinham certo ordenamento estrutural, permitindo que um novo ordenamento se estabeleça. 

Sabemos que a água pode se apresentar em três fases diferentes: sólido (gelo), líquido e gás. A água permanece na fase sólida numa certa faixa de temperatura. Sob pressão atmosférica, a água é sólida a temperaturas abaixo de $0^\circ$ C. Assim, podemos ter gelo a -50$^\circ$ C ou a -20$^\circ$ C, por exemplo. 

Quando fornecemos calor ao gelo a -20$^\circ$ C ele se aquece, passando a temperaturas maiores, sem deixar de ser gelo. O calor fornecido quando acarreta aumento de temperatura é denominado {\bf calor sensível}. Quando, porém, o gelo atinge 0$^\circ$ C e absorve algum calor, ele se mantém a 0$^\circ$ C e passa a derreter gradativamente. Até que todo a fase sólida tenha dado lugar à fase líquida, o acréscimo de calor não representa aumento de temperatura. Diz-se que se trata de {\bf calor latente}. No caso, calor latente de fusão. Após o gelo derreter completamente, a água líquida a 0$^\circ$ C passa a aumentar sua temperatura novamente até que nova transição de fase se estabeleça. 

Quanto maior a massa de gelo, maior o calor latente necessário para fundi-lo completamente. O mesmo se dá com outras substâncias. Se denotamos o calor latente necessário para fundir 1 kg de uma substância por $L_f$, o calor latente necessário para fundir uma massa $m$ da mesma substância é $m\,L_f$. 

O processo inverso, ou seja, de solidificação por resfriamento possui as mesmas características: para solidificar uma massa $m$ de uma substância, ela libera uma quantidade de calor igual a $m\,L_f$.

Na modelagem simplificada que faremos, a transição de fase de líquido para gás segue um comportamento inteiramente análogo ao da passagem sólido-líquido. Até chegar na temperatura de ebulição da água (100$^\circ$ C), esta permanece líquida, aquecendo ao receber qualquer calor sensível. A 100$^\circ$ C, inicia-se a transição de fase. Até que um certo calor latente de ebulição seja absorvido, haverá água nas fases líquida e gasosa. Após a conclusão da transição de fase, teremos vapor a 100 $^\circ$ C. A partir daí, a absorção de calor acarretará aumento de temperatura. 

O comportamento das trocas de calor com a água passando pelas transições de fase está resumido nas figuras abaixo:
:::{figure} ./_static/energiacalormecanismos.png
---
width: 400px
name: energiacalormecanismos
---
A figura ilustra a troca de energia que chamamos de calor por condução. As moléculas do sistema $A$ tem energia cinética média maior (veja o tamanho da setinha) que as de $B$. Ao serem colocados em contato térmico (mesmo que na vizinhança) a energia cinética média de $A$ diminui, e a de $B$ aumenta, até que se igualem.
:::

Os calores latentes de fusão e ebulição de algumas substâncias podem ser encontrados na tabela:

```{table} Calor latentes típicos de algumas substâncias
name: tab:caloreslatentes
| Substância | Calor latente de fusão ($L_f$) em kJ/kg|Calor latente de vaporização ($L_v$) em $kJ/kg|
|----------|----------|----------|
| água | 333,5 | 2257|
| álcool   | 109 | 879|
| chumbo   | 24,7 | 858 |
```


**Exercício**

Calcule a quantidade de calor necessária para levar 1 kg de água da fase sólida, a -20$^\circ$ C, até a fase de vapor, a 120$^\circ$ C.



### Exercícios

2) Você precisa comprar um aquecedor de água para a sua piscina de 20.000 L. Desprezando as perdas de calor da água da piscina para o ambiente, qual deve ser potência desse aquecedor se você quer que a água passe de $24^\circ$ C para $36,0^\circ$ C em $2$ h? Resp.: 140 kW.

3) O calor específico do cobre é mais do que o dobro do calor específico do chumbo. Um bloco de
cobre e um bloco de chumbo têm a mesma massa e a mesma temperatura (20$^\circ$C). Os blocos são jogados
simultaneamente em um único calorímetro contendo água a 40$^\circ$C. Qual afirmativa é verdadeira quando o
equilíbrio térmico é atingido: \
\
(a) O bloco de chumbo terá absorvido mais energia que o bloco de cobre.\
(b) Os dois blocos terão absorvido a mesma quantidade de energia.\
(c) O bloco de chumbo está a uma temperatura menor do que o bloco de cobre.\
(d) O bloco de chumbo terá absorvido menos energia que o bloco de cobre.\
(e) O bloco de chumbo está a uma temperatura maior do que o bloco de cobre.

4) A capacidade térmica de um bloco deve ser determinada. O bloco é colocado em um calorímetro de cobre com massa de $25$ g, contendo $60$ g de água a $20^\circ$ C. Depois, $120$ mL de água a $80^\circ$ C são adicionados ao calorímetro. Quando o equilíbrio térmico é atingido, a temperatura do sistema é $54^\circ$ C. Qual é a capacidade térmica do bloco? Resp.: $\approx$ 120 J/K. 

5) Calcule a quantidade de calor necessária para levar 1 kg de água da fase sólida, a -20$^\circ$ C, até a fase de vapor, a 120$^\circ$ C. Resp.: 3,1 $\times 10^6$ J.  

6) Um copo de vidro de $25,0$ g  contém 200 mL de água a $24,0^\circ$ C. Se dois cubos de gelo, de $15,0$ g cada um e a uma temperatura de $-3,0^\circ$ C são colocados no copo, qual é a temperatura final da bebida? Faça as contas levando em conta a aproximação em que se despreza qualquer transferência de calor entre o copo e o ambiente. Resp.: 10,6$^\circ$ C. 

7) Um calorímetro de alumínio, de $200$ g, contém $600$ g de água a $20^\circ$C. Um pedaço de gelo de $100$ g, a $-20^\circ$C, é colocado no calorímetro. \
\
(a) Determine a temperatura final do sistema. Resp.: 5,26$^\circ$ C.\
(b) Um pedaço de $200$ g de gelo, a $-20^\circ$C, é adicionado. Quanto gelo permanece no sistema depois de atingido o equilíbrio térmico? Resp.: 175 g.\
(c) A resposta $(b)$ mudaria se os dois pedaços de gelo tivessem sido colocados ao mesmo tempo?

