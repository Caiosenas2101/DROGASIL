Portal de Privacidade Drogasil: protótipo navegável

Redesenho do canal de direitos do titular (LGPD) da Drogasil, feito a partir do diagnóstico da Atividade 1.

Protótipo publicado: https://drogasil-g12.vercel.app

Grupo 12: Rodrigo Torres, João Marcelo Montenegro, Caio Sena, Raul Vila Nova, João Cláudio Beltrão e Marcelo Henrique.

Sobre o protótipo
Protótipo visual e navegável, em um único arquivo index.html (HTML, CSS e JavaScript).
Não usa banco de dados nem servidor.
A titular é fictícia: Marina Costa Ribeiro. Todos os dados exibidos são inventados.
Qualquer código de 6 números é aceito na verificação por SMS.
Ao recarregar a página, o protótipo volta ao estado inicial.
Roteiro para o avaliador
Início: aviso de cookies com "Recusar" e "Aceitar" do mesmo tamanho; botão "Seus dados" no cabeçalho e faixa "Privacidade e seus dados".
Privacidade e seus dados: escolha "Ver meus dados" ou "Excluir meus dados".
Fluxo da solicitação: escolher o pedido → confirmar a identidade com CPF e código SMS → solicitação enviada, com número e prazo → acompanhar.
Minhas solicitações: exemplos de cada situação:
Precisamos de você: a empresa pede um documento
Prazo vencido: a solicitação vai ao Encarregado, com opção de reclamar na ANPD
Não atendida: o motivo aparece na tela
Concluída: relatório com cadastro, compras e dados de saúde
Meus pedidos: compras da titular no app e na loja com CPF.
Minha conta: dados pessoais, autorizações (dado de saúde e compartilhamento) e "Excluir minha conta", que pede confirmação e mostra a tela "Conta excluída".

Mensagens de erro: tente continuar a exclusão sem marcar a confirmação, apague o CPF ou digite um código incompleto.

Como abrir no computador

Baixe o index.html e abra no navegador. Não precisa instalar nada.

Publicação

O site é publicado na Vercel a partir da branch main. Cada alteração enviada para o repositório atualiza o site sozinho.

O arquivo precisa se chamar exatamente index.html. Com outro nome, como index (4).html, a Vercel mostra erro 404.
