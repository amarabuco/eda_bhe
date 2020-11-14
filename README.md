# eda_bhe

<h1>DICIONÁRIO</h1>

<h3>ESTADIA</h3>
<ul>
<li>Número do DUV: número do Documento Único Virtual. O DUV concentra as informações
necessárias para estadia (atracação, operação e desatracação) da embarcação.</li>
<li>Estadia Off-Shore: se sim, representa que aquela embarcação é de apoio marítimo/portuáro.
Por exemplo: a embarcação pode prestar algum serviço de reparo, manutenção em uma
plataforma de petróleo, retornando ao Porto para buscar equipamentos.</li>
<li>Atracação Prevista: data/hora informada pelo usuário (Agente de Navegação) da previsão de
atracação da embarcação no Porto.</li>
<li>Atracação Efetiva: data/hora efetivada pelo usuário (do Porto) informando a data/hora em que
a embarcação realmente atracou.</li>
<li>Desatracação Prevista: data/hora informada pelo usuário (Agente de Navegação) da previsão
de desatracação da embarcação no Porto.</li>
<li>Desatracação Efetiva: data/hora efetivada pelo usuário (do Porto) informando a data/hora em
que a embarcação realmente atracou no Porto.</li>
<li>Local(is) Atracação (área do porto > berço > cabeço): local em que a embarcação atracou no
Porto. O primeiro valor corresponde à área do porto, o segundo, ao berço e o terceiro, ao</li>
cabeço.</li>
<li>Local(is) e Data(s) Reatracação (área do porto > berço > ca): se houve alguma reatracação, ou
seja, embarcação atracou, foi para área de fundeio, por exemplo, e voltou para o cais do Porto,</li>
realizando nova atracação. O campo contém valores da área do porto, berço, cabeço e
data/hora da reatracação.</li>
<li>Bandeira da Embarcação: representa o país em que a embarcação está registrada
<li>Área de Navegação: tipo de navegação realizada pela embarcação (Ex:
EXPORTAÇÃO/CABOTAGEM, EXPORTAÇÃO/LONGO CURSO, IMPORT/EXPORT/CABOTAGEM,
IMPORTAÇÃO/LONGO CURSO, INTERIOR etc)</li>
<li>Finalidade da Embarcação: característica da embarcação, destinando-se à sua finalidade. (Ex:
Apoio Marítimo/Portuário, Dragagem, Transporte de Carga Geral, Transporte de Contentores,
Transporte de Granel Sólido, Transporte de Granel Líquido etc)</li>
<li>Tipo de Embarcação: característica da embarcação, definindo seu tipo. (ex: Carga geral,
Graneleiro, Navio sonda, Passageiro, Navio sonda, Petroleiro, Plataforma, Químico etc)</li>
<li>Motivo de Atracação: motivo pelo qual a embarcação está atracando no Porto. Opções:
Abastecimento; Arribada; Carga e Descarga; Descarga; Desembarque/Embarque de
Passageiros; Desembarque de Passageiros; Embarque de Passageiros; Fundeio; Off-shore;
Solicitação de certificado;</li>
<li>Tipo de Viagem Chegada: representa o tipo de viagem realizada pela embarcação ao chegar no
Porto: Pode ser Importação/Cabotagem; Importação/Longo Curso; Importação Mercosul;</li>
Interior; Apoio Marítimo; Apoio Portuário; Passageiro; Não Informado</li>
<li>Tipo de Viagem Saída: representa o tipo de viagem a ser realizada pela embarcação ao sair no
Porto: Pode ser Exportação/Cabotagem; Exportação/Longo Curso; Exportação Mercosul;
Interior; Apoio Marítimo; Apoio Portuário; Passageiro; Não Informado</li>
<li>Especialidade da Carga Predominante: especialidade predominante da carga que está sendo
transportada pela embarcação.</li>
</ul>

<h3>CARGAS</h3>
<ul>
<li>Número do DUV: número do Documento Único Virtual. Para escalas no Mercante, que foram
associadas ao DUV no Porto Sem Papel, este campo é preenchido.</li>
<li></li>Número do conhecimento: número que identifica o conhecimento de embarque</li>
<li>Tipo de conhecimento: pode ser Comum, Filhote ou Master</li>
<li>Tipo de Tráfego: corresponde ao tipo de tráfego da navegação (Ex: Cabotagem, Longo Curso,
Interior)</li>
<li>País de origem da mercadoria: país de carregamento da carga</li>
<li>Porto de origem da mercadoria: porto de carregamento da carga, sendo formado pelo código
bitrigrama (2 primeiros dígitos: código do país; 3 últimos dígitos: identifica o porto), mais seu
nome</li>
<li>País de destino da mercadoria: país de destino da carga</li>
<li>Porto de destino da mercadoria: porto de destino da carga, sendo formado pelo código
bitrigrama (2 primeiros dígitos: código do país; 3 últimos dígitos: identifica o porto), mais seu
nome</li>
<li>País de procedência da carga: país de carregamento da carga</li>
<li>Corrente de tráfego: Se é um embarque, desembarque</li>
<li>Número do item: identifica o item de carga dentro do Conhecimento de embarque.</li>
<li>Dependendo do tipo de carga, pode conter várias mercadorias associadas.</li>
<li>Tipo: corresponde ao tipo da carga, pode ser Granel, Contêiner, Carga Solta ou Veículo</li>
<li>Peso total bruto: Peso total bruto em Kg do item de carga</li>
<li>NCM Mercadoria: Nomenclatura Comum do Mercosul. Código que identifica a própria cargas
Peso bruto da mercadoria: Peso bruto da mercadoria em Kg</li>
<li>Cubagem em m3: Volume do item de carga</li>
A tabela de cargas se relaciona com a de estadia por meio do número do DUV.
As tabelas de data se relacionam com tabela de carga por meio do número do conhecimento
de embarque e do número do item.
</ul>
