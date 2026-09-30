# Conferência DOPM

**Versão:** 3.0

**Descrição**
Executa 6 módulos de conferência do DOPM e gera um único relatório unificado por tópicos.

**Módulos**
1. **Afastamentos / Licenças** — Divergências entre partes duplicadas dos blocos
2. **Transferência de Unidade** — Nome, origem e destino
3. **Período Aquisitivo** — Duplicatas, incoerências e alertas de prazo
4. **Suspensões de Afastamento** — Datas, duração e coerência de motivos
5. **Exercício de Afastamento** — Exercício do ano atual/posterior sem início em dezembro
6. **Códigos CID-10 (Saúde)** — Presença de códigos CID-10 em blocos de texto

**Novidades na v3.0**
- Módulo de verificação de exercício: alerta quando o exercício informado é do ano atual ou posterior, exceto se o início do afastamento for a partir de 01/12 do ano atual.
- Módulo de detecção de CID-10: lista todas as ocorrências de códigos CID-10 (classificação internacional de doenças) nos blocos, sinalizando informação sensível de saúde.

**Sobre**
Extensão completa que automatiza a conferência de dados nos sistemas SEI e SISP para o contexto do DOPM/PMGO.
