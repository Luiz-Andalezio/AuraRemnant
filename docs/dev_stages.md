# 📌 Etapas do Desenvolvimento

## 1. Organização Inicial

1.1. Definir a estrutura do projeto seguindo o modelo de estrutura profissional para jogos em Java.
1.2. Configurar o ambiente de desenvolvimento (IDE, JDK, bibliotecas, etc).

## 2. Criação da Base do Projeto

2.1. Criar as **classes principais** do projeto:
2.2. Verificar e implementar **dependências externas**, se houver (ex: bibliotecas de internacionalização, persistência de dados, etc).
2.3. Implementar a tela de prompt separada.
2.4. Criar o código para gerar o executável.

## 3. Implementação da Tela Inicial

3.1. Criar a estrutura da **Tela Inicial** com suporte ao sistema de tradução (i18n).
3.2. Adicionar as seguintes opções no menu inicial: OBS: A listagem abaixo são os botões do Menu Principal.
* **Nova Jornada**
* **Continuar uma Jornada**
* **Como Jogar**
* **Configurações**
  * Idioma
    * Português-BR
    * English-UK
  * Velocidade do Texto
    * 0.5x
    * 1x
    * 2x
    * Personalizado
* **Extras** (liberados conforme o progresso)
  * Informações Iniciais
  * Personagens
  * Feras Áuricas
  * Habilidades
  * Itens
  * Locais
  * Efeitos
  * Progressão
  * Conquistas
* **Créditos**
* **Sair do Jogo**

## 4. Criação de Personagem

4.1. Implementar a lógica de **criação de personagem** após o jogador iniciar uma nova jornada.
4.2. Exibir a criação como uma **ficha/formulário interativo**, respeitando o idioma selecionado.
4.3. Caso o jogador **saia antes de concluir**, o progresso será descartado.
4.4. Realizar **testes** dessa etapa (UX, erros, compatibilidade com o salvamento).

## 5. Sistema de Salvamento

5.1. Após a criação de personagem, salvar os dados do jogo em arquivo ou estrutura serializada.
5.2. Conectar esse salvamento à opção **"Continuar uma Jornada"**.
5.3. Testar o **carregamento e persistência** de dados em diferentes sessões de jogo.

## 6. Primeira Narrativa Interativa

6.1. Adicionar a **narrativa do 1º Capítulo do 1º Volume do 1º Ato**, com estilo textual em **segunda pessoa no presente**.
6.2. Incluir ramificações iniciais até o **primeiro quiz ou combate**.
6.3. Garantir que a narrativa suporte **sistema de tradução** e estilo de exibição configurado pelo jogador.
6.4. Incluir animações e cores na palavras.