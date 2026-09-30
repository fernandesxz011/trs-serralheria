# T.R.S Serralheria

Landing page comercial **conceitual**, desenvolvida como projeto de portfólio em **HTML, CSS e JavaScript**. Apresenta serviços de serralheria em uma página com identidade escura, detalhes dourados e navegação por seções.

**Status:** protótipo frontend. O repositório não comprova publicação oficial ou aprovação do conteúdo pela empresa. Serviços, marca e autorização de uso da imagem precisam ser confirmados antes da divulgação comercial.

## Experiência implementada

- Abertura com chamada para orçamento e acesso à seção de serviços.
- Seções de serviços, apresentação da empresa e contato.
- Navegação por âncoras, com acesso simplificado ao contato em telas menores.
- Layout adaptado por CSS para telas menores.
- Revelação de elementos com `IntersectionObserver`, indicador de progresso de rolagem e efeito visual de ponteiro.
- Respeito a `prefers-reduced-motion` para reduzir animações conforme a preferência do usuário.

Os botões de orçamento levam à seção `#contato`. **Ainda não existe um canal de conversão ativo:** não há envio de formulário, botão de WhatsApp, backend ou integração de atendimento. A própria página informa que os contatos oficiais estão pendentes.

## Estrutura

| Arquivo | Responsabilidade |
| --- | --- |
| [index.html](index.html) | Estrutura semântica, estilos responsivos e interações JavaScript no mesmo arquivo. |
| [assets/fachada.jpeg](assets/fachada.jpeg) | Imagem utilizada na apresentação visual da marca; autorização de uso a confirmar. |
| `assets/.gitkeep` | Arquivo de organização da pasta de imagens. |
| [.gitignore](.gitignore) | Exclusões de arquivos locais e padrões comuns de segredos. |

As fontes DM Sans e Oswald são carregadas pelo Google Fonts. O projeto não usa framework, gerenciador de pacotes ou processo de build.

## Executar localmente

Abra `index.html` no navegador ou, com Python 3 instalado, execute na pasta do projeto:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Acesse `http://127.0.0.1:8000`.

## Validação e próximos ajustes

Em 30/09/2026, a página foi verificada localmente em Chromium nas larguras de 375, 768 e 1440 px. Não foram observados erros de JavaScript, imagens locais ausentes, âncoras quebradas ou rolagem horizontal. A checagem automatizada de acessibilidade no desktop não apontou violações; isso não substitui testes manuais de teclado e tecnologias assistivas. Recursos externos ficaram bloqueados, portanto a renderização das fontes finais ainda precisa ser revista.

Antes de publicar:

1. Confirmar serviços, textos comerciais e permissão de uso da marca e da fotografia.
2. Definir o canal oficial de orçamento e integrar os links de contato.
3. Revisar navegação por teclado, foco, movimento reduzido e apresentação em dispositivos reais.
4. Registrar capturas do protótipo e uma demonstração com status claramente identificado.

## Desenvolvimento assistido por IA

Ferramentas de IA são utilizadas como apoio à prototipação, pesquisa e desenvolvimento, com direcionamento, revisão do código e validação. O objetivo é compreender a implementação e evoluir tecnicamente, mantendo claros o estágio do projeto e suas pendências.
