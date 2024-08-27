# Decodificador-Alura-Challenge

Este é um projeto de decodificador desenvolvido como parte do "Decodificador-Alura-Challenge". A aplicação permite que os usuários criptografem e descriptografem mensagens utilizando uma técnica simples de substituição de letras por códigos. Além disso, o texto resultante pode ser copiado para a área de transferência.

## Funcionalidades

- **Criptografar Mensagens:** Substitui certas letras por códigos predefinidos.
- **Descriptografar Mensagens:** Reverte as substituições, retornando ao texto original.
- **Copiar Texto:** Copia o texto criptografado ou descriptografado para a área de transferência.

## Como Funciona

### Criptografia

- **Entrada:** O usuário digita uma mensagem na área de texto.
- **Processamento:** Ao clicar no botão "Criptografar", a função `encriptar()` substitui as seguintes letras por códigos:
  - `e` → `enter`
  - `i` → `imes`
  - `a` → `ai`
  - `o` → `ober`
  - `u` → `ufat`
- **Saída:** O texto criptografado é exibido na área de mensagem.

### Descriptografia

- **Entrada:** O usuário insere um texto criptografado na área de texto.
- **Processamento:** Ao clicar no botão "Descriptografar", a função `desencriptar()` reverte as substituições para as letras originais.
- **Saída:** O texto descriptografado é exibido na área de mensagem.

### Copiar Texto

- **Copiar:** O usuário pode clicar no botão "Copiar" para copiar o texto exibido na área de mensagem para a área de transferência.

## Estrutura do Projeto

- **index.html:** Estrutura a interface do usuário.
- **index.css:** Estiliza a interface do usuário (arquivo não mostrado aqui, mas presumivelmente existe em `./src/styles/index.css`).
- **script.js:** Contém as funções de criptografia, descriptografia e cópia de texto.

## Tecnologias Utilizadas

- **HTML5:** Para estruturar a página web.
- **CSS3:** Para estilizar a interface do usuário.
- **JavaScript:** Para implementar a lógica de criptografia, descriptografia e copiar texto.

## Como Executar o Projeto

1. Clone este repositório para o seu computador.
   ```bash
   git clone https://github.com/seu-usuario/decodificador-alura-challenge.git
   ```
2. Navegue até o diretório do projeto.
   ```bash
   cd decodificador-alura-challenge
   ```
3. Abra o arquivo `index.html` em seu navegador.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações, entre em contato:

- **Email:** caio.almeida.dev@gmail.com
- **LinkedIn:** [Caio Vinicius Almeida De Araujo](https://www.linkedin.com/in/caio-vinicius-almeida-fullstack-developer)

---

Este projeto foi desenvolvido como parte do desafio de codificação da Alura. A ideia é praticar e demonstrar habilidades em HTML, CSS e JavaScript.
