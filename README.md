# ☁️ CRIANDO MÁQUINAS VIRTUAIS NO AZURE  
 
<p align="center">
  <img src="https://i.postimg.cc/Gmxtwttm/azure-fundamentals.png" width="256">
</p>

---  
## ⏯️ INTRODUÇÃO  

<p align='justify'>Neste laboratório do bootcamp <i>Azure Essencials</i>, foram abordadas questões referentes a Acordo de Nível de Serviço (SLA) e uas implicações na criação de recursos, como máquinas virtuais no portal <a href='https://portal.azure.com/'><i>Microsoft Azure.</i></a>. Além disso, essa prática tinha como objetivo explorar a documentação relacionada aos tópicos tratados no laboratório.</p>  

--- 
## 🗒️RESUMO DOS TÓPICOS:  

<p align='justify'>- A Tabela de Acordo de Nível de Serviço (<i></i>Service Level Agreement</i> – SLA) mostra os percentuais de SLA e os tempos previstos para inatvidade do recurso ou serviço por semana, mês e ano. </p>    

<p align='justify'>- Ao criar um recurso que já obedece SLA, por ser nativo no Azure, se este ficar indisponível por mais tempo do que a previsão da tabela de SLA, a Microsoft deve ressarcir ao cliente. Entretanto, não há ressarcimento para indisponibilidade de máquina virtual criada por cliente, porque o SLA é criado a partir da requisição do cliente.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab2-criando-maquinas-virtuais/blob/main/images/sla-azure.png' width=880>  
</p>

<p align='justify'>- É importante saber qual o tempo de inatividade aceitável do serviço ou recurso antes de criar uma arquitetura de estruturas na nuvem.</p>  

<p align='justify'>- Na comparação entre recursos com 99% e 99,99% de SLA existe uma diferença grande no tempo de indisponibilidade, porque vai de 1,68 hora para 1,01 minuto. Há menor tempo de indisponibilidade quanto mais 9 houver no percentual do SLA e, quanto menos 9 houver no percentual de SLA, mais tempo de indisponibilidade terá o recurso/serviço.</p>  

<p align="center">
  <img src='https://github.com/rosacarla/lab2-criando-maquinas-virtuais/blob/main/images/criar-vm.png' width=880>  
</p>  

<p align='justify'>- Na tela de configuração de VM, os nomes dos campos oferecem uma janela com resumo sobre o item ou ainda um link para consultar na documentação do Azure a explicação sobre cada item do formulário a ser preenchido.</p>  

<p align="center">
  <img src='https://github.com/rosacarla/lab2-criando-maquinas-virtuais/blob/main/images/availability-vm-azure.png' width=880>
</p>
  
<p align='justify'>- Quanto à vinculação do SLA a opções escolhidas para criação de recursos, um exemplo é a opção selecionada para a zona de disponibilidade da VM, que envolve a escolha de um SLA específico. </p>  

<p align='justify'>- O mesmo vale para a criação de conta de armazenamento. Quando é selecionada a opção de redundância, há replicação do dado entre data centers e regiões. Quanto mais se replica um recurso, há menos tempo de indisponibilidade, por ter o mesmo dado disponível em mais de um lugar ao mesmo tempo, o que, por outro lado, ajuda na recuperação dos dados em caso de situações extremas, como catástrofes.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab2-criando-maquinas-virtuais/blob/main/images/redundancia-disponibilidade.png'> 
</p>

<p align='justify'>- Como há preços fixados para cobrança pelo uso do serviço na nuvem, é importante saber a finalidade real da requisição, se é para produção, teste, só saber como funciona, porque é preciso ter um orçamento pré-definido.</p>  

---  
## ✍️ AUTORA    

Carla Edila Silveira  
Contato: rosa.carla@pucpr.edu.br  

---  

## ©️ LICENÇA

[MIT](https://choosealicense.com/licenses/mit/)  

---  

## 🔗 LINKS ÚTEIS  

- [Recomendações para definir metas de confiabilidade](https://learn.microsoft.com/pt-br/azure/well-architected/reliability/metrics)
- [Opções de disponibilidade para Máquinas Virtuais do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/availability)

---  

