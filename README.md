<h1>
    <span> Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO</span>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
</h1>

## 1️⃣ - Computação em Nuvem
A computação em nuvem é a entrega de serviços de computação pela Internet. Os serviços de computação incluem infraestrutura de TI comum, como máquinas virtuais, armazenamento, bancos de dados e rede. Os serviços de nuvem também expandem as ofertas tradicionais de TI para incluir itens como IoT (Internet das Coisas), ML (machine learning) e IA (inteligência artificial).

Como a computação em nuvem usa a Internet para fornecer esses serviços, ela não precisa ficar restrita pela infraestrutura física da mesma forma que um datacenter tradicional. Isso significa que, se você precisar aumentar rapidamente sua infraestrutura de TI, não precisará esperar para construir um novo datacenter; você pode usar a nuvem para expandir rapidamente seu volume de TI.

### Modelos de Nuvem
#### Nuvem Privada
Uma nuvem privada é, de certa forma, a evolução natural de um datacenter corporativo. Ela é uma nuvem (que fornece serviços de TI pela Internet) usada por uma única entidade. A nuvem privada fornece um controle muito maior para a empresa e o departamento de TI. No entanto, ela também tem mais custos e menos benefícios em relação a uma implantação de nuvem pública. Por fim, uma nuvem privada pode ser hospedada em seu datacenter local. Ela também pode ser hospedada em um datacenter dedicado externo, até mesmo por terceiros que tenham dedicado esse datacenter à sua empresa.
#### Nuvem Pública
Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros. Com uma nuvem pública, qualquer pessoa que queira comprar serviços de nuvem pode acessar e usar os recursos. A disponibilidade pública geral é uma diferença fundamental entre nuvens públicas e privadas
#### Nuvem Híbrida
Uma nuvem híbrida é um ambiente de computação que usa nuvens públicas e privadas em um ambiente interconectado. Um ambiente de nuvem híbrida pode ser usado para permitir que uma nuvem privada escale para atender a uma demanda maior temporária implantando recursos de nuvem pública. A nuvem híbrida pode ser usada para fornecer uma camada adicional de segurança. Por exemplo, os usuários podem escolher com flexibilidade quais serviços manter na nuvem pública e quais implantar na infraestrutura de nuvem privada.

#### Comparação dos Modelos de Nuvem
<table>
  <thead>
    <tr align="left">
      <th>Nuvem Privada</th>
      <th>Nuvem Pública</th>
      <th>Nuvem Híbrica</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>Nenhuma despesa de capital para escalar verticalmente.</td>
      <td>As organizações têm controle total sobre os recursos e a segurança.</td>
      <td>Fornece a maior flexibilidade.</td>
    </tr>
    <tr>
      <td>Os aplicativos podem ser provisionados e desprovisionados rapidamente.</td>
      <td>Os dados não são colocados com os dados de outras organizações.</td>
      <td>As organizações determinam o local para executar os aplicativos.</td>
    </tr>
    <tr>
      <td>As organizações pagam apenas pelo que utilizam.</td>
      <td>O hardware deve ser comprado para o início e a manutenção.</td>  
      <td>As organizações controlam a segurança, a conformidade ou os requisitos legais.</td>  
    </tr>
    <tr>
      <td>As organizações não têm controle total sobre os recursos e a segurança.</td>
      <td>As organizações são responsáveis pela manutenção e pelas atualizações de hardware.</td>    
      <td>-</td>    
    </tr>
  </tbody>
</table>

### Modelo Baseado em Consumo
Os provedores de serviços em nuvem operam em um modelo baseado no consumo,  o que significa que os usuários finais pagam somente pelos recursos que usam.
* Melhor previsão de custos.
* São fornecidos preços para recursos e serviços individuais.
* A cobrança é feita com base no seu uso real.
* Sem custos prévios.
* Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
* Capacidade de pagar para obter mais recursos quando necessário.
* Capacidade de parar de pagar por recursos que não são mais necessários.

#### Tipos de Despesas

##### Despesas de capital (CapEx)
* Gasto inicial de dinheiro em infraestutura física. 
* Despesas têm um valor que se reduz com o tempo.

##### Despesas operacionais (OpEx)
* Gasto com produtos e serviços conforme necessário, pagamento conforme uso.
* É cobrado imediatamente.
---

## 2️⃣ - Benefícios da Nuvem

### Alta Disponibilidade
A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
* O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço.
*  Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).

### Escalabilidade
A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda.
* O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
* Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
* Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

#### Dimensionamento vertical
* A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos. 
* Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. Por outro lado, se você percebesse que superestimou as necessidades, poderia reduzir verticalmente, diminuindo as especificações de CPU ou RAM.

#### Dimensionamento horizontal
* A escala horizontal é adição ou subtração do número de recursos.
* Com a escala horizontal, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

### Confiabildade
Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando.
* Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
* Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.
* Com escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

### Previsibilidade
A previsibilidade na nuvem permite que você avance com confiança.
* A previsibilidade pode se concentrar na previsibilidade de desempenho ou na previsibilidade de custo.
* Implante uma solução criada em torno dessa estrutura e você terá uma solução cujo custo e desempenho são previsíveis.

#### Previsibilidade de Desempenho
A previsibilidade de desempenho se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes.

#### Previsibilidade de Custo
A previsibilidade de custos se concentra em prever o custo dos gastos com a nuvem.

### Governança
Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.
* A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação.
* Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.

### Segurança
Em relação à segurança, você pode encontrar uma solução de nuvem que atenda às suas necessidades de segurança, mas é importante lembrar que a implementação de muitas destas soluções devem ser realizadas pelo cliente.
* Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.
* Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

### Gerenciamento
Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem e ambos trazem excelentes benefícios.

#### Gerenciamento da Nuvem
O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:
* Escalar automaticamente a implantação de recursos com base na necessidade.
* Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
* Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
* Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.

#### Gerenciamento na Nuvem
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Você pode gerenciá-los:
* Por meio de um portal da Web.
* Usando uma interface de linha de comando.
* Usando APIs.
* Usando o PowerShell.
  
## 3️⃣ - Tipos de Serviço de Nuvem

### IaaS (infraestrutura como serviço)
O IaaS é a categoria mais flexível de serviços de nuvem, pois oferece o máximo de controle sobre os recursos de nuvem. 
* Em um modelo de IaaS, o provedor de nuvem é responsável por manter o hardware, a conectividade de rede (com a Internet) e a segurança física.
* Você é responsável por todo o resto: instalação, configuração e manutenção do sistema operacional; configuração de rede; configuração de banco de dados e armazenamento e assim por diante.
* Com o IaaS, basicamente o hardware é alugado em um datacenter de nuvem, mas cabe a você decidir o que fazer com ele.

### PaaS (plataforma como serviço)
O PaaS (Plataforma como serviço) é um meio termo entre alugar espaço em um datacenter (infraestrutura como serviço) e pagar uma solução completa e implantada (software como serviço). 
* Em um ambiente de PaaS, o provedor de nuvem mantém a infraestrutura física, a segurança física e a conexão com a Internet. Ele também mantém os sistemas operacionais, o middleware, as ferramentas de desenvolvimento e os serviços de business intelligence que compõem uma solução de nuvem.
* Em um cenário de PaaS, você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.
* O PaaS é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento.

### SaaS (software como serviço)
O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto.
* Com o SaaS, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Email, software financeiro, aplicativos de mensagens e software de conectividade são exemplos comuns de uma implementação de SaaS.
* Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

#### Comparação dos Tipos de Serviço de Nuvem
<table>
  <thead>
    <tr align="left">
      <th>IaaS</th>
      <th>PaaS</th>
      <th>SaaS</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>O serviço de nuvem mais flexível.</td>
      <td>Focado no desenvolvimento de aplicativos.</td>
      <td>Modelo de preço de pagamento conforme o uso.</td>
    </tr>
    <tr>
      <td>Você configura e gerencia o hardware para seu aplicativo.</td>
      <td>O gerenciamento da plataforma é realizado pelo provedor de nuvem.</td>
      <td>Os usuários pagam pelo software que utilizam em um modelo de assinatura.</td>  
    </tr>
  </tbody>
</table>

<div align="center">Feito por ☁️ José Roberto Assis Silva ☁️ <a href="https://github.com/joserobertofox">JRFOX</a>.</div>

