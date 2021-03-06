# Projeto de Laboratório de Engenharia de Software e Redes

## Motivação

Construir um aplicativo que possibilite o pré-cadastramento de pacientes para a vacina, mesmo em locais remotos. Para tal, o app possibilita o armazenamento de cadastros no dispositivo móvel, de forma que cadastros podem ser feitos mesmo sem conexão à Internet. Posteriormente, quando houver acesso à Internet, os dados podem ser enviados para o servidor.

## Links importantes

### Vídeo-pitch

- Link do [youtube](https://www.youtube.com/watch?v=uah8z-GyEWU)

### Repositórios

Os repositórios de backend e frontend contém as instruções necessárias para rodar cada projeto localmente.

- [Repositório Backend](https://github.com/rodmagaldi/vacinas-server)
- [Repositório Frontend Mobile](https://github.com/iltonandrew/vacinas-app)
- [Repositório Painel de Admin](https://github.com/rodmagaldi/vacinas-admin)

### Gerenciamento de projeto

- [Notion](https://rogue-cardamom-837.notion.site/Lab-EngSoft-f3e20b4c5aa4436e860d64734d10db5d)

### Projetos rodando

- [Servidor](https://vacinas-app-mhanprpxzq-uc.a.run.app/hello-world)
- [Aplicativo](https://expo.dev/@iltonandrew/vacinas)

Para usar o app, é necessário baixar o aplicativo do Expo da loja mobile e ler o QR Code na página linkada acima.

## Dados de teste para o app

Para usar o app, basta colocar dados reais nos campos desejados. Por exemplo, existe uma validação de CPF e CEP. Além disso, colocar uma CEP válido chama automaticamente os valores de estado, cidade, bairro e rua (lembrando que há um cold start neste servidor inicial, esta requisição pode demorar alguns segundos na primeira vez que é feita).
Após preenchidos os dados, basta entrar na página de sincronização e clicar para enviar os dados colhidos.
