# Relatorio de Instalacao
## Aula 6
### **Estudante**: Raylan da Silva Cabral


Segundo a fonte de informacao *freeze* **é uma técnica é muito utilizada em escala empresarial, onde muitos computadores são usados por várias pessoas, sendo necessário fazer manutenção sempre. Para evitar gastos e tempo com a manutenção do sistema, é possível congelar o sistema em determinado estado, evitando que qualquer alteração seja salva, ou seja, o usuário pode apagar arquivos do sistema, alterar configurações e forçar ao máximo para causar o erro, porem ao reiniciar o computador, tudo estará como antes e nada foi danificado ou alterado.**
 

O programa utilizado é o Deep Freeze, um software pago que promete fazer justamente isso com o máximo de segurança possível, apesar de muitos pensarem que isso pode prejudicar o HD, esse pensamento é completamente inválido, pois as alterações não são feitas no HD, e sim no setor de boot do sistema operacional, que ao ser carregado, é responsável por ler o estado em que o sistema foi salvo e carregar a partir deste ponto.


- ### Vantagens de congelar o sistema ###
- São muitas vantagens que podem ser utilizadas neste sistema, como:
1. Descartar o uso de sistemas antivírus residentes.
2. Evitar corrompimento de arquivos do sistema.
3. Previne infecção de vírus no sistema.
4. Evitar alterações nas configurações do sistema.
5. Prevenir a instalação de programas espiões pelos usuários.
6. Anular a remoção de programas ou componentes do Windows.
7. Manter o sistema do mesmo jeito a cada inicialização.
8. Pode ser descongelado a qualquer hora pelo administrador através de uma senha.
9. Pode se congelar e descongelar o sistema em qualquer ponto quantas vezes quiser.
10. Agora vamos ao outro lado do programa.
 
 - ### Desvantagens de congelar o sistema ###
- Apesar das desvantagens serem menores que as próprias vantagens, iremos apresentar os pontos fracos de congelar o sistema.
1. Programas não irão atualizar enquanto o computador estiver congelado.
2. Qualquer arquivo salvo em uma unidade bloqueada será descartado.
3. Históricos ou logs na unidade congelada não irão mais ser alterados.
4. É recomendado ser instalado logo após a formatação do sistema.
5. O programa apresenta recursos interessantes para solucionar as desvantagens, como a manutenção programada, onde através de uma função, o programa consegue rodar e atualizar programas utilizando o recurso de linha de comando do Prompt de Comando, no caso das atualizações automáticas o  Prompt de Comando não é necessário.
   

   ### Instalar S.O Automaticamente ###

   Segundo a fonte de informação **Dual Boot, a melhor maneira de instalar dois sistemas operacionais
A primeira das técnicas que podemos usar para instalar dois (ou mais) sistemas operacionais é Dual Boot** . A inicialização dupla é obtida instalando os dois sistemas operacionais no mesmo computador, em partições ou discos rígidos diferentes e escolhendo qual dos dois deseja inicializar a partir de um gerenciador de inicialização.
Como uma desvantagem do dual boot, devemos enfatizar que não poderemos ter mais de um sistema rodando ao mesmo tempo . Lembre-se também de que precisamos criar partições ou ter diferentes discos rígidos para instalar sistemas operacionais. Além disso, o processo pode ser um pouco complicado e longo , já que teremos que instalar os sistemas um a um, cuidando para que o façam em suas partições correspondentes. O bootloader deve reconhecer os outros sistemas operacionais instalados no PC e, caso não reconheça, teremos que configurá-lo manualmente. Além disso, também é importante observar que podemos ter problemas para acessar nossos dados, uma vez que alguns sistemas (como Windows) não pode ler as partições de outros (como Linux).

E se o que queremos é instalar o macOS junto com o Windows, podemos nos preparar para ter verdadeiras dores de cabeça.

### EULA (End User Lincense Argument) ###

**Uma introdução aos acordos de licença de usuário final (EULAs)**
Segundo a fonte de informação Quando um cliente ou empresa compra um software, ele não está realmente ganhando a propriedade do software. Em vez disso, eles estão pagando pelo direito de usar o software. A propriedade desses aplicativos de software permanece com o fornecedor do software. **Para especificar claramente termos, condições, responsabilidades, restrições, obrigações e muito mais, os fornecedores vão proteger seus softwares por trás de um EULA. O usuário final deve, então, concordar com as estipulações descritas no EULA antes de poder acessar o aplicativo.**

### Quais são os outros nomes de um EULA? ### 

**"End user license agreement (Acordo de licença de usuário final)" (ou, mais comumente, a abreviação "EULA") é o termo mais usado para descrever esse tipo de contrato entre o licenciador de um produto de software e o licenciado**. No entanto, existem vários outros termos que podem ser usados para descrever acordos que cumprem essencialmente a mesma função. Alguns deles são:

1. Acordo de licenciamento
2. Acordo de licença de software
3. Contrato de usuário final do aplicativo licenciado
4. Acordo de termos e condições
5. Contratos click-wrap
6. Contratos browse-wrap
7. Contratos shrink wrap

Vale a pena reconhecer que, embora muitos destes termos sejam usados como sinônimos, alguns podem ter um foco ou uma função jurídica ligeiramente diferentes. Na documentação oficial, o uso de "acordo de licença de usuário final" ou "EULA" é geralmente a abordagem mais apropriada.

### Conceito de Play And Plungis ###

Segundo a fonte de informação **Plug and play é uma das expressões da língua inglesa muito usada na informática que significa “ligar e usar”. Nos primórdios da informática, instalar novos dispositivos era uma tarefa muito difícil de ser realizada.**

Hoje em dia, por exemplo, compramos uma placa de expansão para nosso computador, seja uma placa de vídeo extra para jogos, um potente captador de vídeo, um sintonizador de TV, entre outros, colocamos dentro do PC no local correspondente e o computador atribui automaticamente o “canal” indicado para não interferir os dados de outros dispositivos que estão no PC. É como se atribuísse uma longa pista dentro computador para poder circular. Uma vez colocado o dispositivo no computador, seu fabricante proporciona um driver para que o funcionamento da placa de vídeo, por exemplo, possa render com toda potência.


### O que é partição primária? ###

Segundo a fonte de informação Uma unidade de disco pode conter no máximo quatro partições primárias ou três partições primárias e uma única partição estendida. Um sistema de arquivos está contido em uma partição primária. Diferentemente das versões anteriores dos sistemas Microsoft Windows, os sistemas operacionais Windows mais recentes, como o Windows XP, o Windows 7 podiam ser colocados em qualquer partição. Mas os arquivos de inicialização devem estar localizados em uma partição primária. O código do tipo de partição de uma partição primária indica informações sobre o sistema de arquivos contido na partição primária ou se a partição possui um uso especial. Quando existem várias partições primárias em um disco rígido, apenas uma única partição pode estar ativa a qualquer momento e as outras partições ficam ocultas. Se uma unidade precisar ser inicializável, ela precisará ser uma partição primária.

### O que é partição lógica?###

Segundo a fonte de informação A partição estendida em uma unidade de disco rígido pode ser subdividida em várias partições chamadas partições lógicas. A partição estendida atua como um contêiner para partições lógicas. A estrutura das partes lógicas na partição estendida é descrita usando um ou mais EBR (Extended Boot Records). Os EBRs que descrevem várias unidades lógicas são organizados como uma lista vinculada. Cada EBR vem antes da unidade lógica descrita por ele. O primeiro EBR conterá o ponto inicial do EBR que descreve a próxima unidade lógica. Depois que as partições lógicas são formatadas usando um sistema de arquivos adequado, elas se tornam visíveis.

### Qual é a diferença entre Partição Primária e Partição Lógica? ###

Segundo a fonte de informação A partição primária é uma partição inicializável e contém os sistemas operacionais do computador, enquanto a partição lógica é uma partição que não é inicializável. Várias partições lógicas permitem armazenar dados de maneira organizada. Várias partições primárias em uma unidade de disco rígido são descritas usando uma única tabela de partição contida no MBR, enquanto várias unidades lógicas no disco rígido são descritas usando vários EBRs. Por esse motivo, o número de partições primárias que podem ser criadas em um disco rígido é limitado (no máximo quatro), enquanto o número de unidades lógicas que podem ser criadas é limitado apenas pelo espaço disponível no disco rígido. Geralmente, as partições primárias recebem as primeiras letras do alfabeto como letras de unidade (como C, D), enquanto as unidades lógicas recebem as outras letras (como E, F, G).

### O que é partição swap? ###

Segundo a fonte de informação à definição: a partição Swap **é um espaço restrito que armazena uma quantidade de memória física a ser utilizada quando o sistema operacional fica sobrecarregado. É como uma válvula de escape para o computador, a qual evita a queda de desempenho, travamentos e desligamentos automáticos.**
**A partição swap é um componente essencial no sistema operacional Linux que fornece espaço adicional de memória virtual quando a memória física (RAM) é insuficiente para acomodar os aplicativos em execução. A partição swap é um espaço dedicado no disco rígido que o sistema usa como uma extensão da RAM. Quando a RAM fica sem espaço, o sistema move os dados não utilizados da RAM para a partição de troca. A partição swap permite que o sistema continue a funcionar mesmo quando a memória física está cheia.**

**A principal função da partição de troca é fornecer espaço de memória de backup para a memória física (RAM). A partição de troca utiliza o espaço do disco rígido para fornecer memória virtual que o sistema utiliza como uma extensão da RAM. Sempre que o sistema necessita de espaço de memória adicional, move os dados não utilizados da RAM para a partição de troca. A partição swap melhora o desempenho do sistema ao fornecer espaço de memória de backup que garante que o sistema funcione sem problemas, mesmo com vários aplicativos sendo executados simultaneamente.**

No Linux, o uso da partição swap é automático. O sistema trata da partição de troca e gere a utilização da memória. A partição swap é essencial para sistemas com RAM limitada. A partição de troca permite que o sistema continue a funcionar sem falhar ou congelar quando a RAM está cheia. Quando a partição de troca está a ser utilizada, o desempenho do sistema pode abrandar, uma vez que o disco rígido é mais lento do que a RAM. Por isso, recomenda-se ter RAM suficiente para suportar as aplicações em execução.

O tamanho da partição de troca depende da memória física (RAM) instalada no sistema. A regra geral é ter uma partição swap com o dobro do tamanho da RAM. Por exemplo, se o sistema tiver 4GB de RAM, o tamanho recomendado da partição swap é 8GB. No entanto, se o sistema tiver mais de 8GB de RAM, o tamanho da partição swap pode ser menor.
O swap de juros é um acordo financeiro entre duas partes em que estas trocam fluxos de caixa com base em diferentes taxas de juro. É diferente da partição swap utilizada no sistema operativo Linux.

Para criar uma partição swap no Ubuntu, é necessário seguir estes passos. Primeiro, abra o terminal e digite “sudo fdisk -l” para ver as partições actuais. Em seguida, crie uma nova partição usando o comando “sudo fdisk /dev/sda”, onde sda é o nome do disco rígido. Escolha “n” para uma nova partição, seleccione o tipo de partição como “82” para swap e defina o tamanho da partição. Finalmente, formate a partição usando o comando “mkswap” e active a partição swap usando o comando “swapon”.

Em conclusão, a partição swap é um componente essencial no sistema operativo Linux que fornece espaço de memória virtual adicional quando a memória física (RAM) é insuficiente. A função da partição swap é fornecer espaço de memória de backup para a memória física (RAM). O tamanho da partição swap depende da memória física (RAM) instalada no sistema, e recomenda-se que tenha o dobro do tamanho da RAM. A partição de troca é automática no Linux, e o sistema trata da utilização da memória. Crie uma partição swap no Ubuntu usando os comandos de terminal mencionados acima.

**FAQ**
Você também pode perguntar qual é a diferença entre hedge e swap?
Em finanças, um hedge é uma estratégia financeira usada para minimizar ou compensar perdas potenciais, enquanto um swap é um acordo financeiro entre duas partes para trocar fluxos de caixa com base em uma fórmula predeterminada. Uma cobertura é normalmente utilizada para reduzir o risco num investimento, enquanto um swap é utilizado para gerir fluxos de caixa ou para tirar partido de diferenças nas taxas de juro ou nas taxas de câmbio. Em resumo, uma cobertura é uma ferramenta de gestão de risco, enquanto um swap é um instrumento financeiro utilizado para a gestão de fluxos de caixa ou para beneficiar das flutuações do mercado.

Também podes perguntar como saber se o swap está a funcionar em linux?
Para saber se o swap está a funcionar no Linux, pode usar o comando “free” no terminal para verificar o uso de memória do sistema e o uso de swap. Se a coluna “used” em “Swap” mostrar um valor superior a zero, então a swap está a ser utilizada pelo sistema. Adicionalmente, pode também verificar os logs do sistema para quaisquer erros relacionados com a utilização da swap.

E outra questão, quanta swap devo colocar no android?
A quantidade de espaço de swap que deve atribuir num dispositivo Android depende de vários factores, como o tamanho da RAM do dispositivo, o número de aplicações que executa em simultâneo e o tamanho dos ficheiros com que trabalha. No entanto, como regra geral, os dispositivos Android com 2 GB de RAM ou menos devem ter uma partição de troca entre 1 GB e 2 GB, enquanto os dispositivos com mais de 2 GB de RAM podem ter uma partição de troca de 512 MB a 1 GB. É importante notar que adicionar demasiado espaço de troca pode levar a um desempenho mais lento, por isso é melhor atribuí-lo de forma sensata.

   **Referencias**
   References
Informática, F. 3. (2016, June 3). Como congelar o Sistema Operacional? (Deep Freeze). Com.br. https://www.fator3info.com.br/fator-dicas/como-congelar-o-sistema-operacional-deep-freeze

Lage, B. (2010, November 30). Conhecendo o GRUB. DevMedia. https://www.devmedia.com.br/conhecendo-o-grub/18698

Mills, M. (2021, abril 12). Como instalar e usar dois sistemas operacionais ao mesmo tempo. ITIGIC | Technical How-Tos, Tips, and Tricks. https://itigic.com/pt/install-and-use-two-operating-systems-at-same-time/

([S.d.]). Servicenow.com. Recuperado 23 de novembro de 2023, de https://www.servicenow.com/br/products/it-asset-management/what-is-eula.html#:~:text=Um%20acordo%20de%20licen%C3%A7a%20de%20usu%C3%A1rio%20final%20%28EULA%29,no%20uso%20de%20um%20produto%20de%20software%20espec%C3%ADfico.

Conceito de Plug and Play. ([s.d.]). Conceitos. Recuperado 23 de novembro de 2023, de https://conceitos.com/plug-and-play/


Diferença entre partição primária e partição lógica. ([s.d.]). A diferença entre objetos e termos semelhantes. Recuperado 23 de novembro de 2023, de https://pt.differkinome.com/articles/technology/difference-between-primary-partition-and-logical-partition-2.html

Por, S. (2023, maio 22). Entendendo a Partição Swap: Função, Uso e Criação. Filememo.info. https://filememo.info/tech/entendendo-a-particao-swap-funcao-uso-e-criacao/








