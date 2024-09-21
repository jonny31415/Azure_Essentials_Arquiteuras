# Construindo Arquiteturas no Azure
Ao construir uma arquitetura no Azure é importante considerar diversos fatores:

## Localização dos Recursos
É essencial avaliar quais são os locais em que os recursos estarão localizados, de modo a saber quais são suas zonas de disponibilidade e de *disaster recovery*. Isso se torna mais importante quando existe alguma lei que impede o armazenamento de determinados dados em regiões foras do país de origem.

## Organização da Arquitetura
Para melhor manutenção e controle das aplicações, pode-se dividir os recursos em Grupos de Recursos, que permitem a verificação de recursos criados, modificados e excluídos, por meio dos logs, além de definir diferentes níveis de acesso e controle na criação/modificação/deleção dos recursos. Além disso, ao adicionar marcadores nos recursos e grupos de recursos, isso vem descrito na cobrança da Azure, o que permite uma análise financeira mais fácil para determinar quem deve arcar com cada custo.  
