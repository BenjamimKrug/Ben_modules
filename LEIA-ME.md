# Ben_modules
Minha biblioteca pessoal de simbolos, footprints e modelos 3d para usar no KiCad. Alguns dos símbolos e footprints eu consegui portando a diy_modules, uma biblioteca que eu usava para o Eagle EDA, outros eu peguei na SnapEDA e todo o resto fui eu mesmo que fiz. A grande maioria dos modelos 3D eu peguei gratuitamente no GrabCad. Eu sei que muitos eletrônicos criam as suas próprias bibliotecas de simbolos e footprints para não precisar depender das libs de outros, mas como eu fiz ela ser bem completa achei que seria importante compartilhar para que todos tivessem acesso.

# Processo de instalação
1. Clone o repositório. 
2. Vá no KiCad e abra o menu de configuração dos caminhos configure o caminho relativo para a biblioteca:

<img src="/images/menu de caminhos.png" alt="preferences paths">

<img src="/images/paths menu add item.png" alt="add item to paths">

<img src="/images/paths menu unfilled.png" alt="unfilled path">

3. Então preencha o campo vazio que será criado com o nome sendo 'BEN_MODULES' and então configure o caminho como caminho onde você clonou o repositório, no meu caso eu coloquei ele nos Documentos do Windows
<img src="/images/paths menu filled.png" alt="filled path">

4. Com o caminho configurado, adicione a biblioteca de símbolos em Preferencias->Gerencie as bibliotecas dos símbolos:

<img src="/images/menu simbolos.png" alt="preferences symbols">

<img src="/images/symbols library add item.png" alt="add item to symbols library">

<img src="/images/symbols library unfilled.png" alt="unfilled symbols library">

5. Então preencha o campo vazio criado com o nome sendo 'Ben_modules' e configure o caminho do arquivo de símbolos usando o caminho relativo que você criou anteriormente, preenchendo com '${BEN_MODULES}\symbols\Ben_modules.kicad_sym', como pode ver abaixo:

<img src="/images/symbols library filled.png" alt="filled symbols library">



6. Aí você faz o mesmo processo com a biblioteca de footprints

<img src="/images/menu footprints.png" alt="preferences footprint">

<img src="/images/footprints library add item.png" alt="add item to footprints library">

<img src="/images/footprints library unfilled.png" alt="unfilled footprints library">

7. assim como antes, você preenche o nome no campo vazio como sendo 'Ben_modules' e configura o caminho até a pasta de footprints usando o caminho relativo criado antes, preenchendo o campo do caminho como '${BEN_MODULES}/footprints/Ben_modules.pretty', assim como abaixo:

<img src="/images/footprints library filled.png" alt="filled symbols library">

A partir daí deveria tudo estar funcionando e pronto para uso. Em teoria o KiCad vai informar se iver algum problema em encontrar a biblioteca, então o processo de instalação é para ser bem simples. Se você encontrar algum problema, por favor relate ele na aba issues do repositório para que eu possa solucionar o mais rápido possível. 