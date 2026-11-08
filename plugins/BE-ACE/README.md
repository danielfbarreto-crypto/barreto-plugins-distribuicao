# BE-ACE | Acessibilidade

[Voltar à central](../../README.md) · [Instalação](../../INSTALACAO.md) · [Ajuda](../../SUPORTE.md)

**Oito botões para modelar, quantificar e documentar piso tátil no Revit 2025, com pyRevit.**

## Distribuição disponível

### [Baixar distribuição BE-ACE 2026.11.08.1-rc1](https://github.com/danielfbarreto-crypto/barreto-plugins-distribuicao/releases/tag/BE-ACE-2026.11.08.1-rc1)

**HOMOLOGAÇÃO — teste controlado, sem liberação geral.** Em Assets, baixe **BE-ACE-Revit-2025-2026.11.08.1-rc1.zip**. O pacote contém instalador BAT e os oito guias em A4/mobile, PDF/PPTX (32 arquivos).

Autorização piloto até **22/11/2026 às 00:07:33 (Brasília)**; após o prazo, bloqueia até renovação administrativa. A conferência física na VPN externa e desconectado permanece pendente. O pacote não promove automaticamente a versão estável anterior.

## Conheça os oito botões

Confira a máscara antes de aplicar modelagem. O projetista continua responsável por conferir o resultado e as condições de acessibilidade do projeto.

### <img src="imagens/PisoAlertaPorta.png" width="44" height="44" alt=""> Piso Alerta Porta

Seleciona portas, mostra a máscara e permite inverter o lado antes de aplicar o alerta no vão útil, a 10 cm. Preserva o alerta externo de banheiros; exclui portas de elevador.

[A4 PDF](manuais/A4/Guia%20-%20Piso%20Alerta%20Porta%20-%202026.11.07.1%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Piso%20Alerta%20Porta%20-%202026.11.07.1%20-%20Mobile.pdf)

### <img src="imagens/PisoAlertaElevador.png" width="44" height="44" alt=""> Piso Alerta Elevador

Seleciona portas de elevador e apresenta as máscaras para conferir o lado. Aplica o alerta no vão útil, com afastamento de 25 cm.

[A4 PDF](manuais/A4/Guia%20-%20Piso%20Alerta%20Elevador%20-%202026.11.07.2%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Piso%20Alerta%20Elevador%20-%202026.11.07.2%20-%20Mobile.pdf)

### <img src="imagens/PisoAlertaEscada.png" width="44" height="44" alt=""> Piso Alerta Escada

Seleciona escadas e apresenta as máscaras antes e depois dos lances atendidos. Usa afastamento de 25 cm e faixa conforme o tráfego; não insere em patamares intermediários.

[A4 PDF](manuais/A4/Guia%20-%20Piso%20Alerta%20Escada%20-%202026.11.07.3%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Piso%20Alerta%20Escada%20-%202026.11.07.3%20-%20Mobile.pdf)

### <img src="imagens/RotaAcessivelModelagem.png" width="44" height="44" alt=""> Rota Acessível

Modela piso tátil direcional a partir das linhas de rota editáveis. Trata ramificações, mudanças de direção e alertas previstos, com prévia antes de aplicar.

[A4 PDF](manuais/A4/Guia%20-%20Rota%20Acess%C3%ADvel%20-%202026.11.07.4%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Rota%20Acess%C3%ADvel%20-%202026.11.07.4%20-%20Mobile.pdf)

### <img src="imagens/UnirAlertaRota.png" width="44" height="44" alt=""> Unir Alerta à Rota

Identifica automaticamente ligações entre alertas e rotas. Mostra a prévia e aplica após confirmação, respeitando impedimentos como paredes, ambiguidades e falta de apoio.

[A4 PDF](manuais/A4/Guia%20-%20Unir%20Alerta%20%C3%A0%20Rota%20-%202026.11.07.5%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Unir%20Alerta%20%C3%A0%20Rota%20-%202026.11.07.5%20-%20Mobile.pdf)

### <img src="imagens/TabelaPisoTatil.png" width="44" height="44" alt=""> Tabela Piso Tátil

Cria ou atualiza seis tabelas de Equipamento especial, filtradas somente por BE-CATEGORIA. As três de orçamento têm BE-ID e uma linha por elemento; as demais são consolidadas.

[A4 PDF](manuais/A4/Guia%20-%20Tabela%20Piso%20T%C3%A1til%20-%202026.11.07.6%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Tabela%20Piso%20T%C3%A1til%20-%202026.11.07.6%20-%20Mobile.pdf)

### <img src="imagens/LimparArquivo.png" width="44" height="44" alt=""> Limpar Arquivo

Diagnostica os itens previstos para limpeza e apresenta um resumo antes de excluir. Protege a vista ativa e suas dependências. Confira a lista antes de confirmar.

[A4 PDF](manuais/A4/Guia%20-%20Limpar%20Arquivo%20-%202026.11.07.8%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Limpar%20Arquivo%20-%202026.11.07.8%20-%20Mobile.pdf)

### <img src="imagens/ExportarPDFDWG.png" width="44" height="44" alt=""> Exportar PDF e DWG

Exporta pranchas selecionadas para PDF e DWG, com opções de nomes e agrupamento. Apresenta arquivos existentes antes de substituí-los; saída organizada em Acessibilidade.

[A4 PDF](manuais/A4/Guia%20-%20Exportar%20PDF%20e%20DWG%20-%202026.11.07.9%20-%20A4.pdf) · [Mobile PDF](manuais/Mobile/Guia%20-%20Exportar%20PDF%20e%20DWG%20-%202026.11.07.9%20-%20Mobile.pdf)

## Dados preenchidos na modelagem

- **BE-ID:** ID do próprio elemento, para rastreabilidade.
- **BE-AMBIENTE:** nome simples do pavimento, como TÉRREO ou 1º PAVIMENTO.
- **BE-INFO:** parâmetro compartilhado oculto, com “Modelado com Propriedade Intelectual Barreto Engenharia”, nos elementos criados ou atualizados pelas rotinas de modelagem.
- **Categoria:** Equipamento especial para as famílias oficiais e tabelas de piso tátil.

Os manuais preservam suas versões funcionais aprovadas. As orientações comuns desta homologação estão também no **COMECE-AQUI.txt** do ZIP. As famílias ficam na base corporativa, fora deste pacote.

[Conferir versão e integridade](versao.json)

