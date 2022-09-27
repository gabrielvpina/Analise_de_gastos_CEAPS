# Dados Abertos CEAPS
> CEAPS - Cotas para Exercício da Atividade Parlamentar dos Senadores

A CEAPS destina-se ao ressarcimento das despesas efetuadas com:
- aluguel e manutenção de imóvel destinado à instalação de escritório de apoio à atividade parlamentar;
- aquisição de material de consumo para uso no escritório de apoio à atividade parlamentar, despesas postais, aquisição de publicações, locação de móveis e de equipamentos;
- locação de meios de transporte destinados à locomoção dentro do estado de origem, hospedagem e alimentação do parlamentar ou de servidores comissionados e efetivos lotados em seu gabinete;
- combustíveis e lubrificantes;
- contratação de consultorias, assessorias, pesquisas, trabalhos técnicos e outros serviços de apoio ao exercício do mandato parlamentar;
- serviços de segurança prestados por empresa especializada;
- divulgação da atividade parlamentar;
- passagens aéreas, aquáticas e terrestres nacionais destinadas ao parlamentar ou a servidores comissionados e efetivos lotados em seu gabinete, em gabinete de liderança ou gabinete da Comissão Diretora, quando o parlamentar exercer concomitantemente a titularidade.




## Uma análise dos dados disponíveis (2017-2022)

> Fonte: [Dados abertos](https://www12.senado.leg.br/transparencia/dados-abertos-transparencia/dados-abertos-ceaps?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Ci%C3%AAncia+de+Dados+1%2F7%3A+Data+Cleaning+and+Preparation&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Java%29+Dia+1%2F7%3A+Consumir+uma+API+de+filmes)

## 01: Processo de tratamento e limpeza de dados
Os dados foram disponibilizados no formato CSV (Comma-Separated Values), e apresentaram inconsistências como a presença de células na primeira linha que não
eram configuradas como _headers_, ou seja, títulos dos campos presentes na planilha.
