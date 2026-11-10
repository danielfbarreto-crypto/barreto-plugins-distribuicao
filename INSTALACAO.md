# Instalar e atualizar os plugins

[Voltar à central](README.md)

1. Tenha Revit 2025 e pyRevit instalados. O instalador BE-ACE não instala o pyRevit.
2. Conecte-se à rede do escritório ou VPN corporativa autorizada e confira o acesso à base corporativa.
3. Na página do plugin, abra a distribuição indicada. Baixe o ZIP do plugin em **Assets**; não use **Code → Download ZIP** nem **Source code** para instalar.
4. Extraia o ZIP inteiro para uma pasta local. Não execute o BAT dentro do ZIP nem copie só o BAT.
5. Confira seus trabalhos e feche o Revit normalmente. O instalador não fecha nem salva seus projetos.
6. Para BE-ACE, execute **INSTALAR-BE-ACE.bat**. Se detectar Revit aberto durante atualização, feche-o e pressione ENTER para tentar novamente; C cancela.
7. Abra Revit 2025 e confira os oito botões BE-ACE. Não mantenha duas extensões BE-ACE carregadas.
8. Consulte **Manuais/A4** ou **Manuais/Mobile**. Guarde o número da distribuição para suporte.

## Atualizações

Na V01, o instalador substitui integralmente a pasta BE-ACE.extension. Painéis antigos deixam de ficar ativos; a instalação anterior fica em BE-ACE-Backups, ao lado de Extensions. Outros plugins são preservados e uma falha de ativação restaura a versão anterior.


A publicação no GitHub não altera a instalação automaticamente. Repita o procedimento com a versão indicada pelo responsável. Não misture arquivos de pacotes diferentes. Instalar a homologação substitui a cópia BE-ACE daquele usuário; use-a somente no teste combinado.

## Homologação BE-ACE atual

[BE-ACE — V01](https://github.com/danielfbarreto-crypto/barreto-plugins-distribuicao/releases/tag/BE-ACE-V01) · piloto válido até **22/11/2026 às 00:07:33 (Brasília)**. Após o prazo, os botões bloqueiam até renovação administrativa. A validação física pela VPN externa e desconectado ainda está pendente.

As famílias RFA não estão no ZIP. Use a base corporativa de acessibilidade e as famílias oficiais **BE-ACE-PISO TÁTIL-ALERTA** e **BE-ACE-PISO TÁTIL-DIRECIONAL**, categoria **Equipamento especial**. Projetos com famílias antigas exigem recarga e conferência da categoria, conforme os manuais.

Não remova a proteção de autorização nem copie arquivos de licença entre máquinas. Falhas: consulte [Suporte](SUPORTE.md).

