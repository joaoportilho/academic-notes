# Introdução a sistemas distribuídos
-	Conceitos fundamentais
-	Terminologia
-	Tendência em sistemas distribuídos

==O desejo de compartilhar recursos é o que motiva os sistemas distribuídos, sendo eles: processadores, discos, impressoras, arquivos, bancos de dados e muitos outros==

### Sistemas distribuídos

 > Um sistema distribuído é um conjunto de computadores independentes que se apresenta a seus usuários como um sistema único e coerente - A.S.TANENBAUM
 
 - Composto por computadores autônomos
 - Usuários (pessoas/programas) acham que estgão tratando como um único sistema
	 - Colaboração é o cerne do desenvolvimento de sistemas distribuídos
	 - Diferenças entre nós e o modo como se comunicam são ocultadas do usuário
	 - Interação consistente e uniforme
 - Nenhuma premissa é adotada quanto ao modo como os computadores são interconectados
 - Heterogeneidade de componentes
 
 Consequências
 
 - Concorrrência
 - Inexistência de relógio global

Erros comuns
1) Assumir que a rede é confiável
2) Assumir que a rede é segura
3) Assumir que a rede é homogênea
4) Assimir que a topologia não muda
5) Assumir que a latência é zero
6) Assumir que a largura de banda é infinita
7) Assumir que o custo de transporte é zero
8) Assumir que há só um administrador

Exemplos
- **Financeiro e comercial:** e-commece, como no caso de Amazon, eBay, tecnologias de pagamento como Paypal, *crypto currencies*, etc
- **Sociedade da informação:** WWW como um vasto repositório de informações. Google, Yahoo, Bing! Ettc. Como forma de bvusca nesse vasto repositório, bibliotecas digitais (ex. Google Books - digitalização de conteúdo), conteúdo de usuário (ex. Youtube, Wikipedia etc.) redes sociais (Facebook, MySpace, etc.), etc.
- **Entretenimento:** MMOGs, Youtube, Spotify, Netflix, Hulu etc.
- **Saúde (healthcare):** *health informatics*, telemedicina, monitoramento de idosos, etc.
- **Educação:** *e-learning*.
- **Transporte:** viabilizado pelo GPS e hoje, com tecnologias de navegação que permitirão navegação autônoma do veículo.
- **Ciência:** uso do *Grid*, como tecnologia fundamental para e-science, para suporte a armazenamento, análise e processamento de (grandes quantidade de) dados científicos. Facilitador para colaboração entre grupos científicos.
- **Gerenciamento ambiental:** uso de tecnologia de redes de sensores para monitoramento e análise de dados climáticos. Ex. Alerta de terremotos, etc.

Terminologia
