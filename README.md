# BoraBusHackathon
_Prever a satisfação dos clientes com relação aos serviços do BoraBusão!_ 

## Objetivos
E aí? O que queremos fazer? Aonde queremos chegar com isso?

<br>_Entender como usar e criar TransformerMixin e BaseEstimators do pacote SKLearn._</br>
<br>_Criar pipelines._</br>
<br>_Entender como salvar transformacões em binários e como recuperar eles e usar para gerar previsões._</br>
<br>_Entender o MLFlow._</br>
<br>_A **métrica** a ser avaliada para a previsão de satisfação dos clientes será a **acurácia**._ Mas é importante mostrar a curva ROC e a métrica KS apenas para enriquecerem os resultados, será obrigatório gerá-los e interpertar os resultados dos mesmos.</br>


> Os trabalhos entregues serão avaliados em um dataset separada e desconhecido de vocês. Por favor, **criem um repositório no github com as soluções**, e sigam o cookie cutter de data science como padrão https://github.com/drivendata/cookiecutter-data-science

## Sobre o dataset

O conjunto de dados veio de uma enquete com os clientes da BoraBusão e queremos saber se com estes dados podemos prever a satisfação dos mesmos com os serviços da empresa. (**Lembrando que tanto a empresa citada quanto os dados são fictícios e alterados**)

### Features e contexto
<ul>
  <li><strong>ID:</strong> Identificação do cliente</li>
  <li><strong>Genero:</strong> Gênero do cliente</li>
  <li><strong>PlanoFidelidade:</strong> Se o cliente possui ou não o plano fidelidade da BoraBusão</li>
  <li><strong>Idade:</strong> Idade do cliente</li>
  <li><strong>RazaoViagem:</strong> Motivo da viagem ( pessoal ou a trabalho? )</li>
  <li><strong>CategoriaPassagem:</strong>  Em qual catergoria ele está viajando? Normal, Comforto ou Leito</li>
  <li><strong>DistanciaKm:</strong> A distancia do trecho de viagem</li>
  <li><strong>WiFi:</strong> Possui WiFi no ônibus, o serviço está bom?</li>
  <li><strong>ConvenienciaHorarios:</strong> Os horários de partida e chagada são convenientes?</li>
  <li><strong>FacilidadeReservaViaApp:</strong> Nível de facilidade de fazer a reserva da passagem</li>
  <li><strong>PontosLocalização:</strong> A localização dos pontos de ônibus é boa, qual a satisfação com relação a esse ponto</li>
  <li><strong>Alimentação:</strong> A alimentação servida no oninbus e nos pontos, qual a sua avaliação?</li>
  <li><strong>CheckInViaApp:</strong> Facilidade de fazer o checkIn via o app</li>
  <li><strong>ConfortoInterno:</strong> Nível de conforto do ônibus ( cadeiras, ar-condicionado)</li>
  <li><strong>ServicosIntegracao:</strong> Nível de satisfação desde a chegada até o embarque.</li>
  <li><strong>SalaDeEspera:</strong> Nível de satisfação com a sala de espera de quem tem o plano Fidelidade</li>
  <li><strong>Bagagem:</strong> Nível de satisfação com o serviço e manuseamento da bagagem do passageiro</li>
  <li><strong>ServicoCheckin:</strong> Nivel de satisfaçao com o serviço de checkin local</li>
  <li><strong>ServicoDeBordo:</strong> Nível de satisfação com o serviço de bordo</li>
  <li><strong>Limpeza:</strong> Nível de satisfação com a Limpeza</li>
  <li><strong>AtrasoNaSaída:</strong> Atraso em minutos na partida</li>
  <li><strong>AtrasoNaChegada:</strong> Atraso em minuto na chegada</li>
  <li><strong>SatisfacaoGeral:</strong> Variável alvo, o cliente está satisfeito ou não</li>
</ul>

## Alguns procedimentos
O dataset tem variáveis categóricas que precisam ser tratados e salvos como binários (usando pickle ou joblib) pois as transformações irão refletir no modelos, para entender melhor esse processo tomem como exemplo esse repositótio aqui https://github.com/vivianyamassaki/kaggle_titanic_deploy .

> Lembrando que além das transformações a avaliação usará um dataset externo. Então antes de fazer qualquer transformação já separem um conjunto de testes com 10% do tamanho original para validar o modelo final. **CUIDADO!! Isso é diferente de separar o dataset em treino e teste na hora de gerar o modelo** nessa etapa voces terão um conjunto de treino, um de teste e um de validação já com as transformações geradas por vocês, e que voces irão usar para ajustar a acurácia do modelo gerado.
 Então sigam esse procedimento, separem o dataset da seguinte forma:
 <ul>
  <li> <strong>Teste final</strong> - 10%, será usado apenas com o binário gerado a partir do seu modelo final.</li>
  <li> <strong>Etapa de geraçao do Modelo</strong> - Treino 60%, Teste 15% , Validação 15% </li>
</ul>

## Apresentação dos resultados.

Gerar um .ppt com no maximo 4 slides de conteúdo, que será apresentado para todos no dia 26/09 as 15h.
Terão 8 minutos para defenderem os resultados achados.

> O vencedor será anunciado no dia 26/09, os 3 primeiros colocados irão mostrar os resultados. 
> As outras apresentações também serão avaliadas, mas em outro momento.

<br><strong> A data da entrega é 23/09 até as 09:30 da manhã.</strong></br>
### Lembretes
A entrega deve conter:
> Um repositório github com a solução desenvolvida e os binários gerados.
> Uma apresentação .ppt com 4 slides no máximo.




<p> <strong>BOA SORTE AOS PARTICIPANTES</strong> </p>

