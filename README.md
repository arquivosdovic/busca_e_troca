# 🔍 Busca Avançada de Texto (Single-File App)

Este é um aplicativo web leve e poderoso, construído em um único arquivo HTML, projetado para realizar operações avançadas de busca, destaque, substituição e remoção em grandes volumes de texto ou código. Ideal para desenvolvedores ou qualquer pessoa que precise de ferramentas de manipulação de texto robustas diretamente no navegador.

## ✨ Funcionalidades Principais

* **Busca e Destaque:** Localiza todas as ocorrências do termo de busca e as destaca em um modo de visualização separado.

* **Navegação Rápida:** Botões "Anterior" e "Próximo" para percorrer rapidamente os resultados encontrados.

* **Substituição Global:** Substitui todas as ocorrências do termo de busca por um novo texto com um único clique.

* **Remoção em Massa:** Botão "Remover Tudo" para deletar instantaneamente todas as ocorrências do termo de busca.

* **Histórico Completo (Undo/Redo):** Sistema de histórico de estados (Desfazer/Refazer) que armazena as últimas 50 mudanças, permitindo reverter substituições ou edições acidentais.

### Opções Avançadas de Busca

O aplicativo oferece controle preciso sobre a busca através de caixas de seleção:

1. **Maiúsculas/minúsculas:** Define se a busca deve diferenciar entre letras maiúsculas e minúsculas.

2. **Palavra Inteira:** Garante que apenas palavras inteiras que correspondam ao termo sejam encontradas (ignora sub-strings).

3. **Diacríticos Correspondentes:** Permite buscas sensíveis a acentos e caracteres especiais (ex: buscar "cão" e não encontrar "cao").

## ⚙️ Como Usar

Por ser um aplicativo de arquivo único:

1. **Clone o repositório** ou baixe o arquivo `index.html`.

2. **Abra o arquivo `index.html`** diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, etc.).

3. Cole seu texto ou código na área de edição e comece a usar a barra de busca e os controles avançados.

## 💻 Tecnologias

Este projeto foi desenvolvido utilizando a pilha web clássica e leve:

* **HTML5:** Estrutura base do aplicativo.

* **Tailwind CSS:** Framework utilitário para um design responsivo e moderno.

* **JavaScript Puro (Vanilla JS):** Toda a lógica de busca, manipulação de DOM e gestão de histórico.

## ⚠️ Nota sobre Firebase (Uso em Ambientes Específicos)

O código possui um bloco de inicialização para **Firebase** para fins de conformidade e potencial persistência de dados em ambientes de *sandbox* (como o Google Canvas). Em um uso padrão, ao abrir o arquivo localmente, a mensagem **"ID do Usuário: (Sem Firebase)"** será exibida, e isso **não afeta** a funcionalidade principal de busca e substituição. O aplicativo é completamente funcional localmente.
