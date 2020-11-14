# eda_bhe

<h3>ESTADIA</h3>
<ul>
<li><strong>Número do DUV:</strong> número do Documento Único Virtual. O DUV concentra as informações
necessárias para estadia (atracação, operação e desatracação) da embarcação.</li>
<li><strong>Estadia Off-Shore:</strong> se sim, representa que aquela embarcação é de apoio marítimo/portuáro.
Por exemplo: a embarcação pode prestar algum serviço de reparo, manutenção em uma
plataforma de petróleo, retornando ao Porto para buscar equipamentos.</li>
<li><strong>Atracação Prevista:</strong> data/hora informada pelo usuário (Agente de Navegação) da previsão de
atracação da embarcação no Porto.</li>
<li><strong>Atracação Efetiva:</strong> data/hora efetivada pelo usuário (do Porto) informando a data/hora em que
a embarcação realmente atracou.</li>
<li><strong>Desatracação Prevista:</strong> data/hora informada pelo usuário (Agente de Navegação) da previsão
de desatracação da embarcação no Porto.</li>
<li><strong>Desatracação Efetiva:</strong> data/hora efetivada pelo usuário (do Porto) informando a data/hora em
que a embarcação realmente atracou no Porto.</li>
<li><strong>Local(is) Atracação (área do porto > berço > cabeço):</strong> local em que a embarcação atracou no
Porto. O primeiro valor corresponde à área do porto, o segundo, ao berço e o terceiro, ao</li>
cabeço.</li>
<li><strong>Local(is) e Data(s) Reatracação (área do porto > berço > ca):</strong> se houve alguma reatracação, ou
seja, embarcação atracou, foi para área de fundeio, por exemplo, e voltou para o cais do Porto,</li>
realizando nova atracação. O campo contém valores da área do porto, berço, cabeço e
data/hora da reatracação.</li>
<li><strong>Bandeira da Embarcação:</strong> representa o país em que a embarcação está registrada
<li><strong>Área de Navegação:</strong>  tipo de navegação realizada pela embarcação (Ex:
EXPORTAÇÃO/CABOTAGEM, EXPORTAÇÃO/LONGO CURSO, IMPORT/EXPORT/CABOTAGEM,
IMPORTAÇÃO/LONGO CURSO, INTERIOR etc)</li>
<li><strong>Finalidade da Embarcação:</strong> característica da embarcação, destinando-se à sua finalidade. (Ex:
Apoio Marítimo/Portuário, Dragagem, Transporte de Carga Geral, Transporte de Contentores,
Transporte de Granel Sólido, Transporte de Granel Líquido etc)</li>
<li><strong>Tipo de Embarcação:</strong> característica da embarcação, definindo seu tipo. (ex: Carga geral,
Graneleiro, Navio sonda, Passageiro, Navio sonda, Petroleiro, Plataforma, Químico etc)</li>
<li><strong>Motivo de Atracação:</strong> motivo pelo qual a embarcação está atracando no Porto. Opções:
Abastecimento; Arribada; Carga e Descarga; Descarga; Desembarque/Embarque de
Passageiros; Desembarque de Passageiros; Embarque de Passageiros; Fundeio; Off-shore;
Solicitação de certificado;</li>
<li><strong>Tipo de Viagem Chegada:</strong> representa o tipo de viagem realizada pela embarcação ao chegar no
Porto: Pode ser Importação/Cabotagem; Importação/Longo Curso; Importação Mercosul;</li>
Interior; Apoio Marítimo; Apoio Portuário; Passageiro; Não Informado</li>
<li><strong>Tipo de Viagem Saída:</strong> representa o tipo de viagem a ser realizada pela embarcação ao sair no
Porto: Pode ser Exportação/Cabotagem; Exportação/Longo Curso; Exportação Mercosul;
Interior; Apoio Marítimo; Apoio Portuário; Passageiro; Não Informado</li>
<li><strong>Especialidade da Carga Predominante:</strong> especialidade predominante da carga que está sendo
transportada pela embarcação.</li>
</ul>

<h3>CARGAS</h3>
<ul>
<li><strong>Número do DUV:</strong> número do Documento Único Virtual. Para escalas no Mercante, que foram
associadas ao DUV no Porto Sem Papel, este campo é preenchido.</li>
<li><strong>Número do conhecimento:</strong> número que identifica o conhecimento de embarque</li>
<li><strong>Tipo de conhecimento:</strong> pode ser Comum, Filhote ou Master</li>
<li><strong>Tipo de Tráfego:</strong> corresponde ao tipo de tráfego da navegação (Ex: Cabotagem, Longo Curso,
Interior)</li>
<li><strong>País de origem da mercadoria:</strong> país de carregamento da carga</li>
<li><strong>Porto de origem da mercadoria:</strong>  porto de carregamento da carga, sendo formado pelo código
bitrigrama (2 primeiros dígitos: código do país; 3 últimos dígitos: identifica o porto), mais seu
nome</li>
<li><strong>País de destino da mercadoria: país de destino da carga</li>
<li><strong>Porto de destino da mercadoria: porto de destino da carga, sendo formado pelo código
bitrigrama (2 primeiros dígitos: código do país; 3 últimos dígitos: identifica o porto), mais seu
nome</li>
<li><strong>País de procedência da carga:</strong> país de carregamento da carga</li>
<li><strong>Corrente de tráfego:</strong> Se é um embarque, desembarque</li>
<li><strong>Número do item:</strong> identifica o item de carga dentro do Conhecimento de embarque. Dependendo do tipo de carga, pode conter várias mercadorias associadas.</li>
<li><strong>Tipo:</strong> corresponde ao tipo da carga, pode ser Granel, Contêiner, Carga Solta ou Veículo</li>
<li><strong>Peso total bruto:</strong> Peso total bruto em Kg do item de carga</li>
<li><strong>NCM Mercadoria:</strong> Nomenclatura Comum do Mercosul. Código que identifica a própria cargas</li>
<li><strong>Peso bruto da mercadoria:</strong> Peso bruto da mercadoria em Kg</li>
<li><strong>Cubagem em m3:</strong> Volume do item de carga</li>
A tabela de cargas se relaciona com a de estadia por meio do número do DUV.
As tabelas de data se relacionam com tabela de carga por meio do número do conhecimento
de embarque e do número do item.
</ul>
