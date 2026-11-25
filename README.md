# Vem que é Tech (VQT) - App

Atividade acadêmica Programação em Scripts: aplicativo mobile de assistência técnica sob demanda, em que o cliente cria uma conta, abre chamados para o conserto de aparelhos e acompanha tudo pelo celular, feito com Power Apps (aplicativo de tela).

> Este projeto é a versão mobile do **Vem que é Tech (VQT) - Web**. A ideia é a mesma, mas com funcionalidades diferentes.

## Telas

<p align="center">
  <img src="images/01_tela_inicial.png" width="220" alt="Tela inicial">
  <img src="images/04_boas_vindas.png" width="220" alt="Boas-vindas">
</p>

**Tela inicial** e **boas-vindas**: apresentação do app, com opção de ignorar o tutorial.

<p align="center">
  <img src="images/05_meus_chamados_claro.png" width="220" alt="Meus chamados, tema claro">
  <img src="images/06_criar_chamado_claro.png" width="220" alt="Criar chamado, tema claro">
</p>

**Tema claro**: lista "Meus chamados" com busca por título e a tela de criação de chamado, com os serviços e aparelhos atendidos.

<p align="center">
  <img src="images/07_meus_chamados_escuro.png" width="220" alt="Meus chamados, tema escuro">
  <img src="images/08_criar_chamado_escuro.png" width="220" alt="Criar chamado, tema escuro">
</p>

**Tema escuro**: as mesmas telas no modo escuro.

<p align="center">
  <img src="images/03_abertura_chamado.png" width="220" alt="Abertura de chamado">
  <img src="images/02_abertura_chamado_anexos.png" width="220" alt="Abertura de chamado, anexos">
</p>

**Abertura de chamado**: formulário com título, categoria, aparelho, sistema operacional, descrição do problema e fotos.

## Tecnologias

* Power Apps (aplicativo de tela)
* Power Fx (fórmulas)

## Funcionalidades

* Tela inicial e boas-vindas com tutorial, que pode ser ignorado
* Cadastro e login de usuários
* Abertura de chamados com título, categoria, marca/modelo do aparelho, sistema operacional e descrição do problema
* Anexo de fotos do aparelho no chamado
* Lista "Meus chamados" com busca pelo título
* Botão para cancelar o chamado direto na lista
* Tela de informações com os serviços (quedas, troca de peças, telas rachadas, instalação, manutenção e limpeza) e os aparelhos atendidos (celulares, computadores, tablets, notebooks, consoles e outros)
* Tema escuro e claro
* Tela de configurações
* Navegação por barra superior com início, chamado e configurações

## Arquivos

* `vqt_projeto_prog_scripts.msapp`: arquivo do aplicativo, para importar no Power Apps
* `images/`: prints das telas usados neste README
* `README.md`: este arquivo

## Como executar

1. Baixe o arquivo `vqt_projeto_prog_scripts.msapp` deste repositório.
2. Acesse [make.powerapps.com](https://make.powerapps.com) com uma conta corporativa ou escolar.
3. Crie um **Aplicativo de tela em branco** (formato telefone).
4. No editor, vá em **Arquivo → Abrir → Procurar** e selecione o `.msapp`.
5. O app abre com todas as telas e fórmulas. Use o botão de executar (▶) para testar.

## Observações

* Para executar o app é preciso uma conta do Power Apps. Conectores premium exigem licença compatível.
