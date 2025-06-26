<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="ass/css/style.css">
    <title>Multiverso Marvel</title>
</head>
<body>
 <style>
    #barao {
      display: none;
      position: fixed;
      bottom: 30px;
      right: 30px;
      background-color: #111;
      color: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 150px #000;
      font-family: Arial, sans-serif;
      z-index: 9999;
      max-width: 300px;
      animation: aparecer 0.5s ease;
      margin: 2px 30px ;
    }

    #fechar {
      position: absolute;
      top: 5px;
      right: 10px;
      background: none;
      color: #fff;
      border: none;
      font-size: 18px;
      cursor: pointer;
    }

    @keyframes aparecer {
      from { opacity: 0; transform: scale(0.8); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>



<div id="barao">
  <button id="fechar">X</button>
  <div id="mensagem">Marvel</div>
</div>

<script>
  const frases = [
    "Um fato interessante o personagem mais inteligentes da Marvel é Reed Richards (Sr.Fantástico)",
    "O pior filme da Marvel é Thor amor e trovão",
    "O personagem mais poderoso da Marvel dos quadrinhos é One-Above-All",
    "Como seu personagem prefrido da Marvel, o meu personagem favorito é o cavaleiro da lua",
    "E aí você tá gostando? Olhando para você é o maior fã da Marvel com certeza!",
    "Um fato muito interessante o primeiro filme de Marvel foi homem de ferro (2008)"
  ];

  const barao = document.getElementById('barao');
  const mensagem = document.getElementById('mensagem');
  const fechar = document.getElementById('fechar');

 
  function mostrarBarao() {
    const fraseAleatoria = frases[Math.floor(Math.random() * frases.length)];
    mensagem.innerText = fraseAleatoria;
    barao.style.display = 'block';
  }

 
  function esconderBarao() {
    barao.style.display = 'none';
 
    const tempo = Math.random() * (30000 - 10000) + 10000;
    setTimeout(mostrarBarao, tempo);
  }

  fechar.addEventListener('click', esconderBarao);


  const tempoInicial = Math.random() * (15000 - 5000) + 5000; // 5 a 15 segundos
  setTimeout(mostrarBarao, tempoInicial);
</script>

</body>
  


    <div id="p1">
        <img src="https://cdn.displate.com/artwork/380x270/2023-02-20/5b2a2a9d563f5e6eab55bda4dd6c685c_e94104e2ce97c563a7bbf2421ec628d1.jpg" class="img-responsiva">
        <h1>Multiverso Marvel</h1>
     </div>
         <div class="p2">
             <p >O que é um site?</p>

              Um site (ou website) é um conjunto de páginas e conteúdos acessíveis pela internet, organizados em um endereço eletrônico (como www.exemplo.com).Ele pode ter diversos objetivos:informar, entreter, vender produtos, apresentar portfólios, compartilhar ideias ou, como aqui, explorar um tema específico — no nosso caso, a Linha Colorosa da Marvel. Este site foi criado para reunir curiosidades, imagens, análises e tudo o que envolve esse universo visual vibrante dentro do mundo Marvel.</p>
           </div> 
             <div class="content">
               <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFrr7i26Mx029vwvrOmIBm1gICVaocmynxXA&s" class="img-roto">
                </div>
               <div class="a1">
                <h1>1943-1945</h1>
               </div>
                  <div class="t1">
                   <p>
                    Capitão América: O Primeiro Vingador (2011) é um filme do Universo Cinematográfico da Marvel que conta a origem do herói Steve Rogers. Durante a Segunda Guerra Mundial, Rogers é um jovem franzino com grande coragem e senso de justiça. Ele se voluntaria para um experimento militar e recebe um soro que o transforma no super soldado Capitão América. Com seu escudo indestrutível, ele lidera batalhas contra a organização nazista Hydra, liderada pelo vilão Caveira Vermelha. O filme mostra sua luta pelo bem, sacrifício e como ele se torna um símbolo de esperança, terminando com seu congelamento e reaparecimento no presente.
                   </p>
                  </div>
                  <div class="content1">
                    <img src="https://m.media-amazon.com/images/M/MV5BMzk0MzkxODMwOV5BMl5BanBnXkFtZTgwMjQzODE4NzE@._V1_FMjpg_UX1000_.jpg" class="img-agent">
                  </div>
                  <div class="a2">
                    <h1>1945</h1>
                  </div>
                  <div class="t2">
                    <p>
                        Agente Carter é uma série da Marvel que acompanha Peggy Carter após a aparente morte do Capitão América. Trabalhando na SSR nos anos 1940, ela enfrenta o machismo da época enquanto realiza missões secretas para ajudar Howard Stark a limpar seu nome. Com a ajuda do mordomo Jarvis, ela enfrenta ameaças perigosas e mostra seu verdadeiro valor como agente.
                    </p>
                  </div>
                  <div class="content2">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRolRjvPLHMUjAgfHNwwXuSRYztElB6b-u1Zw&s" class="img-xmanp">
                  </div>
                  <div class="a3">
                    <h1>1960</h1>
                  </div>
                  <div class="t3">
                    <p>O filme mostra a origem dos X-Men, quando Charles Xavier e Erik Lehnsherr se conhecem e formam uma equipe de jovens mutantes para impedir um vilão, Sebastian Shaw, de iniciar uma guerra nuclear. No final, eles se separam por diferenças ideológicas: Charles cria os X-Men e Erik se torna o Magneto.</p>
                  </div>
                  <div class="content3">
                    <img src="https://img.elo7.com.br/product/main/267969F/big-poster-x-men-dias-de-um-futuro-esquecido-lo05-90x60-cm-nerd.jpg" class="img-x2">
                  </div>
                  <div class="a4">
                    <h1>1973</h1>
                  </div>
                  <div class="t4">
                    <p>Num futuro dominado por robôs chamados Sentinelas, os mutantes estão quase extintos. Para impedir isso, os X-Men enviam a consciência de Wolverine ao passado, nos anos 1970, para impedir um evento crucial: o assassinato de uma figura importante por Mística. Ele precisa unir o jovem Xavier e Magneto para mudar o futuro e salvar os mutantes.</p>
                  </div>
                  <div class="content4">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIul3Rs78L7K5rvskeaClKeSyBltbN58wNbQ&s" class="img-wox">
                  </div>
                  <div class="a5">
                    <h1>1979</h1>
                  </div>
                  <div class="t5">
                    <p>O filme conta a origem de Logan (Wolverine), desde sua infância no século XIX até se tornar parte do programa Arma X, onde recebe seu esqueleto de adamantium. Ele luta ao lado de seu meio-irmão Victor Creed (Dentes-de-Sabre) em várias guerras, mas se afasta após se cansar da violência. Traído pelo governo, Logan busca vingança e enfrenta o mutante Deadpool, perdendo a memória no final.</p>
                  </div>
                  <div class="content5">
                    <img src="https://static.wikia.nocookie.net/marveldatabase/images/9/90/X-Men_Apocalypse_Poster_003.jpg/revision/latest?cb=20151211204052" class="img-xa">
                  </div>
                  <div class="a6">
                    <h1>1983</h1>
                  </div>
                  <div class="t6">
                    <p>O antigo mutante Apocalipse desperta no Egito após milhares de anos e quer destruir o mundo para reconstruí-lo com seus "quatro cavaleiros", incluindo Magneto. Os jovens X-Men, liderados por Professor Xavier, precisam se unir para impedi-lo. No final, eles conseguem derrotar Apocalipse, e os X-Men finalmente se formam como equipe.</p>
                  </div>   <div class="content6">
                    <img src="https://m.media-amazon.com/images/M/MV5BZDI1NGU2ODAtNzBiNy00MWY5LWIyMGEtZjUxZjUwZmZiNjBlXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" class="img-cm">
                  </div>
                  <div class="a8">
                    <h1>1990</h1>
                  </div>
                  <div class="t7">
                    <p>Carol Danvers, uma ex-piloto da Força Aérea, ganha superpoderes após um acidente com uma tecnologia alienígena. Sem memória de seu passado, ela vive entre os Kree como "Vers". Ao voltar para a Terra nos anos 1990, ela descobre sua verdadeira identidade, enfrenta os vilões Kree e ajuda os Skrulls, uma raça refugiada. No final, ela assume seu papel como a poderosa Capitã Marvel.</p>
                  </div>   <div class="content7">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxh6Wz-sT3manythkoNd-LYqZPecgiKcFqSqRRpWm2rECoXLd_xrjTrtGHwPBDGtrzIo8&usqp=CAU" class="img-xf">
                  </div>
                  <div class="a9">
                    <h1>1992</h1>
                  </div>
                  <div class="t8">
                    <p>Durante uma missão no espaço, Jean Grey é atingida por uma força cósmica que aumenta seus poderes, mas também a torna instável e perigosa. Enquanto tenta entender o que está acontecendo com ela, Jean perde o controle, colocando os X-Men em conflito entre si. No fim, ela precisa tomar uma decisão extrema para salvar os outros — e se sacrifica para impedir a destruição</p>
                  </div>   <div class="content8">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTF4XwTScoIO5s8odNEFKTwwdyA6dgo8BV7WqzXsv18-xBF1NDH5vOdlKlqhx38ZJKwPGk&usqp=CAU" class="img-bl">
                  </div>
                  <div class="a10">
                    <h1>1998</h1>
                  </div>
                  <div class="t11">
                    <p>Blade é um híbrido de humano com vampiro, conhecido como "walker" — ele tem força e velocidade sobre-humanas, mas não tem as fraquezas dos vampiros. Ele dedica sua vida a caçar vampiros e proteger os humanos. No filme, ele enfrenta Deacon Frost, um vampiro ambicioso que quer dominar o mundo usando um ritual antigo.</p>
                  </div>   <div class="content9">
                    <img src="https://static.wikia.nocookie.net/dublagem/images/7/76/Xmen.jpg/revision/latest/scale-to-width-down/1200?cb=20241115053035&path-prefix=pt-br" class="img-xfl">
                  </div>
                  <div class="a11">
                    <h1>2000</h1>
                  </div>
                  <div class="t12">
                    <p>Em um mundo onde mutantes são perseguidos, o Professor Xavier lidera os X-Men para proteger a paz entre humanos e mutantes. Enquanto isso, Magneto acredita que a guerra é inevitável. Wolverine e Vampira se juntam ao grupo, e juntos eles tentam impedir Magneto de transformar líderes mundiais em mutantes usando uma máquina perigosa.</p>
                  </div>   <div class="content10">
                    <img src="https://m.media-amazon.com/images/M/MV5BMGE5ZmY2NzEtZTEyMi00MWIyLThmOWYtYzJkOTQ0Y2U3ZWU1XkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" class="img-bl2">
                  </div>
                  <div class="a12">
                    <h1>2002</h1>
                  </div>
                  <div class="t13">
                    <p>Blade se une a um grupo de vampiros de elite chamado Bloodpack para combater uma nova ameaça: os Reapers, uma mutação de vampiros ainda mais perigosos que se alimentam de humanos e vampiros. Enquanto luta ao lado de antigos inimigos, Blade descobre traições e precisa impedir que essa nova raça destrua tudo.</p>
                  </div>   <div class="content11">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQxpBZdBwSIJ9Hvn4P0Aq-6wEuGeM_e-Hwd5w&s" class="img-hoar">
                  </div>
                  <div class="a13">
                    <h1>2002</h1>
                  </div>
                  <div class="t14">
                    <p>O filme Homem-Aranha (2002) narra a origem de Peter Parker, um estudante que, após ser picado por uma aranha geneticamente modificada, desenvolve superpoderes como força, agilidade e o sentido aranha. Ele se torna o vigilante Homem-Aranha para combater o crime, especialmente após a morte de seu tio Ben. Peter precisa conciliar sua vida como herói com seus sentimentos por Mary Jane Watson e sua amizade com Harry Osborn. Seu principal inimigo é o Duende Verde, alter ego de Norman Osborn, que se torna um vilão perigoso após um experimento falho.</p>
                  </div>   <div class="content12">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSiQwQFtpJtNoOC_FwkCNEzEoLvYjsgHk7N2Q&s" class="img-xf3">
                  </div>
                  <div class="a14">
                    <h1>2003</h1>
                  </div>
                  <div class="t15">
                    <p>Em X-Men 2, após um ataque mutante à Casa Branca, o militar anti-mutante Coronel Stryker lança um ataque à Escola Xavier. Os X-Men, incluindo Wolverine, Ciclope e Jean Grey, precisam formar uma aliança improvável com Magneto e Mística para impedir Stryker de usar uma versão aprimorada do Cérebro para aniquilar todos os mutantes. O filme aborda a perseguição e a luta pela sobrevivência dos mutantes.
                    </p>
                  </div>   <div class="content13">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQA4LjHc3ev4CRG1HK9_Ma_y1D4cAgmcLqiqQ&s" class="img-dem">
                  </div>
                  <div class="a15">
                    <h1>2003</h1>
                  </div>
                  <div class="t16">
                    <p>O filme Demolidor conta a história de Matt Murdock, um advogado cego que perdeu a visão na infância devido a um acidente com resíduos tóxicos. Esse mesmo acidente, no entanto, aprimorou seus outros sentidos a níveis sobre-humanos. À noite, ele se transforma no vigilante mascarado Demolidor, usando suas habilidades para combater o crime nas ruas de Hell's Kitchen, Nova York, especialmente após a morte de seu pai, um boxeador. Ele se envolve com a misteriosa e habilidosa Elektra Natchios e enfrenta inimigos perigosos como o impiedoso criminoso Rei do Crime e o assassino Mercenário.</p>
                  </div>   <div class="content14">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2cWGdeGVrN9LpOBtR0CqbMpvzZ9VGqp5Ghg&s" class="img-hoar4">
                  </div>
                  <div class="a16">
                    <h1>2004</h1>
                  </div>
                  <div class="t17">
                    <p>Em Homem-Aranha 2, Peter Parker (Homem-Aranha) enfrenta o desafio de equilibrar sua vida pessoal com suas responsabilidades de super-herói, chegando a considerar desistir. Ele lida com problemas no relacionamento com Mary Jane e a amizade com Harry Osborn. O principal vilão é o Doutor Octopus, um cientista brilhante que se torna uma ameaça após um experimento desastroso. Peter precisa superar suas dúvidas e lutar para proteger a cidade.</p>
                  </div>   <div class="content15">
                    <img src="https://resizing.flixster.com/-XZAfHZM39UwaGJIFWKAE8fS0ak=/v3/t/assets/p35188_p_v10_aa.jpg" class="img-blt">
                  </div>
                  <div class="a17">
                    <h1>2004</h1>
                  </div>
                  <div class="t18">
                    <p>Em Blade: Trinity, o caçador de vampiros Blade (Wesley Snipes) é incriminado por uma série de assassinatos de humanos, forçando o FBI a caçá-lo. Para se defender e continuar sua guerra contra os vampiros, ele é forçado a se aliar aos Nightstalkers, um grupo de caçadores de vampiros humanos, incluindo Abigail Whistler (Jessica Biel) e Hannibal King (Ryan Reynolds). Juntos, eles descobrem que os vampiros ressuscitaram o lendário Drácula (Dominic Purcell), o vampiro original e mais poderoso, em uma tentativa de finalmente acabar com Blade e dominar a humanidade. A equipe deve encontrar uma maneira de derrotar Drácula antes que seja tarde demais.</p>
                  </div>   <div class="content16">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR4zTY184YUXvL1cGqyCmFg3hX9MyClXOS4Rg&s" class="img-f4">
                  </div>
                  <div class="a18">
                    <h1>2005</h1>
                  </div>
                  <div class="t19">
                    <p>Em Quarteto Fantástico e o Surfista Prateado, Reed Richards e Susan Storm estão prestes a se casar quando a chegada do enigmático Surfista Prateado à Terra causa fenômenos estranhos e destrutivos. O Surfista é o arauto de Galactus, uma entidade cósmica que devora planetas, e veio preparar a Terra para sua destruição. O Quarteto Fantástico deve se unir para desvendar o mistério do Surfista e encontrar uma forma de deter Galactus, enquanto também lidam com o ressurgimento do Doutor Destino, que busca aprimorar seus próprios poderes através do Surfista.</p>
                  </div>   <div class="content17">
                    <img src="https://static.wikia.nocookie.net/marvel-dublagem/images/a/ab/Homem-Aranha_3.jpg/revision/latest?cb=20220329175151&path-prefix=pt-br" class="img-hi">
                  </div>
                  <div class="a19">
                    <h1>2006</h1>
                  </div>
                  <div class="t20">
                   <p>Em Homem-Aranha 3, Peter Parker (Homem-Aranha) desfruta do sucesso como herói, mas sua vida começa a desmoronar. Ele enfrenta múltiplos desafios: Flint Marko, o Homem-Areia, que ele descobre ser o verdadeiro assassino de seu Tio Ben; Harry Osborn, que se torna o Novo Duende Verde em busca de vingança pela morte do pai; e o surgimento de um simbionte alienígena. Esse simbionte se liga a Peter, amplificando suas habilidades, mas também despertando seu lado mais sombrio e agressivo. Quando Peter rejeita o simbionte, ele se une a Eddie Brock, um fotógrafo rival, criando o vilão Venom. Peter precisa lutar contra seus inimigos e contra si mesmo para proteger as pessoas que ama e a cidade.</p> 
                  </div>   <div class="content18">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5rMZrYBkre4866T9eOXB1rYTJQdxwRhAQJg&s" class="img-xvf">
                  </div>
                  <div class="a20">
                    <h1>2006</h1>
                  </div>
                  <div class="t21">
                    <p>Em X-Men: O Confronto Final, o governo descobre uma "cura" para a mutação, prometendo transformar mutantes em humanos. Isso divide a comunidade mutante: alguns veem a cura como uma libertação, enquanto outros, liderados por Magneto, a consideram uma ameaça à sua existência, intensificando a guerra entre mutantes e humanos. Paralelamente, Jean Grey ressurge como a poderosa e instável Fênix Negra, uma ameaça incontrolável que coloca em risco não apenas os X-Men, mas todo o planeta. Os X-Men, liderados pelo Professor Xavier e Ciclope, precisam enfrentar a decisão moral da cura e a força destrutiva da Fênix.</p>
                  </div>   <div class="content19">
                    <img src="https://br.web.img2.acsta.net/medias/nmedia/18/93/01/84/20230847.jpg" class="img-po">
                  </div>
                  <div class="a21">
                    <h1>2007</h1>
                  </div>
                  <div class="t22">
                    <p>Em Quarteto Fantástico e o Surfista Prateado, a Terra é ameaçada pela chegada do misterioso Surfista Prateado, que é o arauto de uma entidade cósmica devoradora de planetas. O Quarteto Fantástico deve se unir para descobrir a verdadeira natureza do Surfista e deter a ameaça iminente, enquanto também enfrentam o retorno do Doutor Destino, que busca usar os poderes do Surfista para seus próprios fins.</p>
                  </div>   <div class="content20">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSL6Pt56BTFxvrMiL8B6auVmjAynJ5bh2W0AQ&s" class="img-foh">
                  </div>
                  <div class="a22">
                    <h1>2008</h1>
                  </div>
                  <div class="t23">
                    <p>O filme Homem de Ferro apresenta Tony Stark, um genial e bilionário inventor, playboy e magnata da indústria de armamentos. Durante uma demonstração de armas no Afeganistão, ele é sequestrado por terroristas e forçado a construir um míssil. Em vez disso, Stark constrói uma armadura rudimentar para escapar. De volta aos EUA, ele decide parar de fabricar armas e, usando sua inteligência e recursos, aprimora a armadura, tornando-se o super-herói Homem de Ferro. Tony precisa enfrentar ameaças internas e externas, incluindo seu próprio sócio, Obadiah Stane, que busca roubar sua tecnologia e se torna o vilão Monge de Ferro.</p>
                  </div>   <div class="content21">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCmqf2pVltv2CvCgiCmxkviAw4afzde2V3cA&s" class="img-hof4">
                  </div>
                  <div class="a23">
                    <h1>2008</h1>
                  </div>
                  <div class="t24">
                    <p>Em Homem de Ferro 2, Tony Stark (Homem de Ferro) está desfrutando de sua fama, mas enfrenta pressão do governo para entregar sua tecnologia de armadura. Além disso, ele descobre que o paládio em seu reator Arc o está envenenando lentamente. Enquanto busca uma cura e lida com a pressão, ele enfrenta novos inimigos: Ivan Vanko (Whiplash), um gênio russo com um rancor pessoal e tecnologia similar, e o rival Justin Hammer, que tenta criar suas próprias armaduras. Tony deve confiar em seus amigos, como Pepper Potts e James Rhodes (que se torna o Máquina de Combate), para sobreviver e proteger seu legado.</p>
                  </div>   <div class="content22">
                    <img src="https://static.wikia.nocookie.net/dublagempedia/images/c/ce/4c6d75ac51fb097c9f0ae5df862abcd8.jpg/revision/latest?cb=20200609155424&path-prefix=pt-br" class="img-hulk">
                  </div>
                  <div class="a24">
                    <h1>2009</h1>
                  </div>
                  <div class="t25">
                    <p>O filme O Incrível Hulk segue a história de Bruce Banner, um cientista que, após ser exposto a raios gama em um experimento falho, se transforma no gigante verde e raivoso conhecido como Hulk sempre que sua frequência cardíaca sobe. Buscando uma cura para sua condição e tentando evitar ser capturado pelo General Thaddeus "Thunderbolt" Ross (pai de sua amada Betty Ross), que quer usar o Hulk como arma, Bruce vive escondido no Brasil. No entanto, ele é descoberto e forçado a retornar aos EUA, onde é caçado pelo soldado Emil Blonsky. Blonsky, obcecado por poder, injeta-se com um soro que o transforma no monstruoso Abominável, forçando Banner a se transformar no Hulk para uma batalha épica que decide o destino de Nova York.</p>
                  </div>   <div class="content23">
                    <img src="https://static.wikia.nocookie.net/osvingadores/images/5/5a/Thor_Official_Poster.jpg/revision/latest?cb=20150423214330&path-prefix=pt-br" class="img-tho2">
                  </div> 
                  <div class="a25">
                    <h1>2011</h1>
                  </div>
                  <div class="t26">
                    <p>O filme Thor apresenta o arrogante e poderoso guerreiro Thor, filho de Odin e príncipe de Asgard. Após desobedecer seu pai e iniciar uma guerra, Thor é despojado de seus poderes e banido para a Terra, onde deve aprender humildade. Ele encontra a astrofísica Jane Foster e sua equipe. Enquanto isso, seu irmão adotivo Loki conspira para usurpar o trono de Asgard. Thor precisa provar ser digno, recuperar seu martelo Mjolnir e seus poderes, e retornar a Asgard para impedir Loki e proteger os dois mundos.</p>
                  </div>   <div class="content24">
                    <img src="https://static.wikia.nocookie.net/universocinematograficomarvel/images/d/d0/Theavengersnewposter.jpg/revision/latest?cb=20150705230227&path-prefix=pt" class="img-vi">
                  </div>
                  <div class="a26">
                    <h1>2012</h1>
                  </div>
                  <div class="t27">
                    <p>Quando o vilão Loki (irmão de Thor) retorna à Terra com a ajuda do exército alienígena Chitauri e rouba o Tesseract, a agência de espionagem S.H.I.E.L.D., liderada por Nick Fury, decide reunir os maiores heróis do mundo. Assim, Homem de Ferro, Capitão América, Thor, Hulk, Viúva Negra e Gavião Arqueiro devem superar suas diferenças e trabalhar juntos como os Vingadores para impedir Loki e seu exército de escravizar a humanidade, culminando em uma batalha épica na cidade de Nova York.</p>
                  </div>   <div class="content25">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSb8HY-Fp8wo9UhDEaG7rBmNS8-pvAGWydomg&s" class="img-hoa2">
                  </div>
                  <div class="a27">
                    <h1>2012</h1>
                  </div>
                  <div class="t28">
                    <p>O filme O Espetacular Homem-Aranha (2012) reconta a história de origem de Peter Parker, um estudante socialmente desajeitado que é mordido por uma aranha geneticamente modificada no laboratório da Oscorp, ganhando superpoderes. Ele começa a investigar o passado misterioso de seus pais e se conecta com o Dr. Curt Connors, um ex-parceiro de seu pai. Quando Connors se transforma no monstruoso Lagarto, Peter assume a identidade do Homem-Aranha para proteger Nova York e sua nova paixão, Gwen Stacy, enquanto desvenda segredos sobre seu passado e o destino de seus pais.</p>
                  </div>   <div class="content26">
                    <img src="https://m.media-amazon.com/images/M/MV5BMTkwODYyMjgzOV5BMl5BanBnXkFtZTgwODAzMTE5MjE@._V1_FMjpg_UX1000_.jpg" class="img-agent6">
                  </div>
                  <div class="a28">
                    <h1>2013</h1>
                    <h1>temp-1-7</h1>
                  </div>
                  <div class="t29">
                    <p>Após os eventos de "Os Vingadores", o Agente Phil Coulson forma uma equipe de elite (May, Fitz, Simmons, Ward e a hacker Skye) para investigar fenômenos e ameaças sobrenaturais globais. Eles lidam com casos como humanos aprimorados e segredos sobre a tecnologia "Centopéia". Enquanto Coulson questiona sua própria ressurreição, Skye busca a verdade sobre seu passado, e a dinâmica da equipe começa a se desenvolver.</p>
                  </div>   <div class="content27">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRAivOklg9mysAswDa6Vn-iMfC0lTvtJLQs5w&s" class="img-wo">
                  </div>
                  <div class="a29">
                    <h1>2013</h1>
                  </div>
                  <div class="t30"> 
                    <p>Após os eventos de "X-Men: O Confronto Final", Logan (Wolverine) vive isolado, assombrado pela morte de Jean Grey. Ele é procurado por Yukio, uma mutante que o leva ao Japão para se despedir de um velho amigo, Yashida, um homem que ele salvou na Segunda Guerra Mundial. Yashida, agora um magnata, oferece a Logan a chance de se livrar de sua imortalidade. No entanto, Logan é arrastado para uma conspiração de clãs Yakuza, ninjas e mutantes, tendo que proteger Mariko, a neta de Yashida, enquanto lida com a perda de sua capacidade de cura e seus próprios demônios internos.</p>
                  </div>   <div class="content28">
                    <img src="https://m.media-amazon.com/images/M/MV5BMjdjNDQ3ZTEtY2Y1Mi00NmE1LWI3NWEtY2VkOTY1ODFkYTY4XkEyXkFqcGc@._V1_.jpg" class="img-tho">
                  </div>
                  <div class="a30">
                    <h1>2013</h1>
                  </div>
                  <div class="t31">
                    <p>Em Thor: O Mundo Sombrio, Thor e os asgardianos enfrentam a ameaça dos Elfos Negros, liderados por Malekith. Eles buscam a substância cósmica conhecida como Aether (ou Éter), que tem o poder de mergulhar os Nove Reinos na escuridão. Jane Foster é acidentalmente infectada pelo Aether, tornando-se um alvo para Malekith. Thor é forçado a formar uma aliança improvável com seu irmão trapaceiro, Loki, para proteger Jane e impedir que os Elfos Negros destruam o universo, em uma batalha que os leva de Asgard a Londres.</p>
                  </div>   <div class="content29">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_tsEYu82-P85DvO-Nc9xHRm8ZIMcW-ibckQ&s" class="img-agent5">
                  </div>
                  <div class="a31">
                    <h1>2013</h1>
                    <h1>temp ep 8-16</h1>
                  </div>
                  <div class="t32">
                    <p>A equipe de Coulson continua investigando mistérios, enquanto ele descobre a chocante verdade sobre sua própria ressurreição no "Projeto T.A.H.I.T.I.". Skye também começa a desvendar sua origem como uma "0-8-4". O grande ponto de virada é a revelação de que a HYDRA se infiltrou na S.H.I.E.L.D., culminando na traição de Grant Ward, que se revela um agente duplo, desmantelando a equipe e a organização.</p>
                  </div>   <div class="content30">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRK12sjPRXkaoeTcHl2BALUAWzikp4wWH-rkw&s" class="img-hf">
                  </div>
                  <div class="a32">
                    <h1>2013</h1>
                  </div>
                  <div class="t33">
                    <p>Após os eventos de "Os Vingadores", Tony Stark sofre de estresse pós-traumático e ansiedade, dedicando-se obsessivamente à criação de novas armaduras. Ele é forçado a agir quando o terrorista conhecido como Mandarim lança ataques devastadores. Com sua casa destruída e Pepper Potts em perigo, Tony precisa confiar mais em sua inteligência e engenhosidade do que em suas armaduras para lutar contra o Mandarim e a tecnologia perigosa Extremis, enquanto descobre a verdadeira identidade por trás das ameaças.</p>
                  </div>   <div class="content31">
                    <img src="https://p2.trrsf.com/image/fget/cf/774/0/images.terra.com/2013/10/23/capitaoamerica.jpg"class="img-ca">
                  </div>
                  <div class="a33">
                    <h1>2013</h1>
                  </div>
                  <div class="t34">
                    <p>Em Capitão América 2: O Soldado Invernal, Steve Rogers (Capitão América) está se ajustando ao mundo moderno e trabalhando para a S.H.I.E.L.D. ao lado da Viúva Negra. Quando um ataque a Nick Fury o coloca no centro de uma conspiração, o Capitão América descobre que a organização que ele serve está infiltrada por seus antigos inimigos, a HYDRA. Ele precisa desvendar a verdade e enfrentar um misterioso e letal assassino conhecido como Soldado Invernal, que tem laços surpreendentes com seu passado. O filme explora temas de confiança, paranoia e as consequências da segurança em detrimento da liberdade.</p>
                  </div>
                  <div class="content32">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSewzpdAzIbErVLV1YZFYoAim5hIzta81FKwQ&s" class="img-agent4">
                  </div>
                  <div class="a43">
                    <h1>2013</h1>
                    <h1>temp1 ep17-22</h1>
                  </div>
                  <div class="t35">
                    <p>Após a revelação de que a HYDRA infiltrou a S.H.I.E.L.D., a equipe de Coulson está em fuga e desmantelada. Grant Ward é exposto como um traidor da HYDRA. A equipe deve lutar para combater a HYDRA, liderada por John Garrett, e reconstruir o que sobrou da S.H.I.E.L.D., com Coulson se tornando o novo diretor em meio a mistérios sobre sua própria sobrevivência.</p>
                  </div>
                        <div class="content34">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRP5ujxaOa_w13q1cml7Nk5j3mYYa-Vv3qWVQ&s" class="img-gu2">
                  </div>
                  <div class="a34">
                    <h1>2014</h1>
                  </div>
                  <div class="t36">
                   <p>
                      O filme acompanha Peter Quill, um saqueador espacial que rouba um orbe misterioso e acaba se tornando alvo de inimigos perigosos, como o vilão Ronan, que deseja usá-lo para destruir planetas. Para escapar e salvar o universo, Quill forma uma equipe improvável com Rocket (um guaxinim armado), Groot (uma árvore que fala), Gamora (uma assassina treinada) e Drax (um guerreiro em busca de vingança). Juntos, eles se tornam os Guardiões da Galáxia, enfrentando batalhas épicas e descobrindo a importância da amizade e do trabalho em equipe.</p> 
                  </div>
                        <div class="content35">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRiMD2JfN2rzALNLxGP2II4_CbwYEu80lV-Ig&s" class="img-gu">
                  </div>
                  <div class="a35">
                    <h1>2014</h1>
                  </div>
                  <div class="t37">
                    <p>Neste segundo filme, os Guardiões continuam suas aventuras pelo cosmos enquanto lidam com conflitos internos e descobertas do passado. Peter Quill (Senhor das Estrelas) conhece seu verdadeiro pai, Ego, um ser celestial com intenções misteriosas. Enquanto isso, a equipe enfrenta novas ameaças, fortalece laços de amizade e família, e lida com sacrifícios importantes. O filme mistura ação, humor e emoção, aprofundando os personagens e mostrando que família nem sempre é de sangue — mas sim quem está ao seu lado nos momentos difíceis.</p>
                  </div>
                        <div class="content36">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNeR5GCXQOsKvKSUVa4CxfSQTCyZaZikx3_g&s" class="img-eu">
                  </div>
                  <div class="a36">
                    <h1>2014</h1>
                  </div>
                  <div class="t38">
                    <p>Essa série de curtas animados acompanha o adorável Baby Groot em pequenas aventuras divertidas e caóticas pelo universo. Cada episódio mostra Groot explorando ambientes diferentes, interagindo com criaturas estranhas e se metendo em confusões — sempre com muito humor e fofura. Mesmo sem falar mais do que "Eu sou Groot", ele consegue expressar emoções e conquistar o público. A série é leve, divertida e ideal para quem gosta do personagem e quer momentos curtos de entretenimento no estilo Marvel.</p>
                  </div>
                        <div class="content37">
                    <img src="https://static.wikia.nocookie.net/dublagem/images/4/43/OEspetacularHomemAranha2.jpg/revision/latest?cb=20240613031548&path-prefix=pt-br" class="img-hoa">
                  </div>
                  <div class="a37">
                    <h1>2014</h1>
                  </div>
                  <div class="t39">
                   <p>Peter Parker continua sua jornada como o Homem-Aranha, tentando equilibrar sua vida de super-herói com seu relacionamento com Gwen Stacy. Enquanto enfrenta novos vilões como Electro, que ganha poderes elétricos e ameaça a cidade, Peter também descobre segredos sobre o passado de seus pais. Além disso, Harry Osborn retorna e acaba se transformando no Duende Verde. O filme traz batalhas intensas, dilemas pessoais e um final emocionante que marca profundamente a vida do herói.</p> 
                  </div>
                        <div class="content38">
                    <img src="https://static.wikia.nocookie.net/daredevil/images/d/da/Daredevil1.jpg/revision/latest/scale-to-width-down/620?cb=20150408205445&path-prefix=pt-br" class="img-de">
                  </div>
                  <div class="a38">
                    <h1>2015</h1>
                    <h1>temp1</h1>
                  </div>
                  <div class="t40">
                    <p>Na primeira temporada da série Demolidor, conhecemos Matt Murdock, um advogado cego que, à noite, combate o crime como o vigilante Demolidor no bairro de Hell's Kitchen, em Nova York. Usando seus sentidos aguçados, ele enfrenta a crescente corrupção na cidade e entra em confronto com o poderoso e cruel mafioso Wilson Fisk (o Rei do Crime). A série mistura ação intensa com drama urbano, mostrando a luta de Matt para fazer justiça tanto nos tribunais quanto nas ruas, enfrentando dilemas morais e físicos.</p>
                  </div>
                        <div class="content39">
                    <img src="data:image/jpeg;base64,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" class="img-agent3">
                  </div>
                  <div class="a39">
                    <h1>2015</h1>
                    <h1>temp2 po1-10</h1>
                  </div>
                  <div class="t41">
                    <p>A S.H.I.E.L.D. tenta se reerguer após a queda causada pela HIDRA. Coulson lidera a equipe em missões secretas. Eles enfrentam novos inimigos, como o Homem-Absorvente, e descobrem mais sobre uma raça alienígena chamada Kree. Skye começa a ter visões estranhas e, no episódio 10, desperta seus poderes depois de um contato com um artefato alienígena.</p>
                  </div>
                        <div class="content40">
                    <img src="https://br.web.img3.acsta.net/pictures/18/02/07/19/48/1080296.jpg" class="img-j">
                  </div>
                  <div class="a40">
                    <h1>2015</h1>
                    <h1>temp 1</h1>
                  </div>
                  <div class="t42">
                    <p>Jessica é uma detetive particular com superforça e um passado traumático. Ela enfrenta Kilgrave, um vilão com o poder de controlar mentes, que a manipulou no passado. Ao longo da temporada, Jessica luta para expor os crimes de Kilgrave e se libertar de sua influência.
                    </p>
                  </div>
                        <div class="content41">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUquEh8ahwa1gkaN_4RNMU9K7HtflVp9Gz9Q&s" class="img-agent2">
                  </div>
                  <div class="a41">
                    <h1>2015</h1>
                    <h1>temp2 ep11-19</h1>
                  </div>
                  <div class="t44">
                    <p>Skye está mudando após ganhar poderes. Ela descobre que é uma Inumana. Enquanto isso, a S.H.I.E.L.D. enfrenta conflitos internos com outra facção liderada por Gonzales. A relação entre humanos e Inumanos começa a se complicar. Novos segredos sobre o passado de Skye e sua mãe vêm à tona, aumentando as tensões.
                    </p>
                  </div>
                        <div class="content42">
                    <img src="https://cdn.awsli.com.br/2500x2500/1610/1610163/produto/177685105/poster-vingadores-era-de-ultron-p-303a09c6.jpg" class="img-v2">
                  </div>
                  <div class="a42">
                    <h1>2015</h1>
                  </div>
                  <div class="t45">
                    <p>Os Vingadores enfrentam Ultron, uma inteligência artificial criada por Tony Stark que se volta contra a humanidade. Ultron quer “salvar” o mundo destruindo os humanos. Com a ajuda de novos aliados, como Wanda e Visão, a equipe luta para impedir a destruição global.
                    </p>
                  </div>
                  <div class="t46">
                    <h1>Continua...</h1>
                  </div>
                  
                  
                 
                    


                  
                  
                     

</body>
</html> 
