# Link do projeto

https://classificador-de-doenca-pulmonar.vercel.app/

# Classificador de Doença Pulmonar

Este projeto consiste em um classificador de doença pulmonar desenvolvido utilizando o Teachable Machine para treinamento, além de HTML, CSS e JavaScript para a interface web. Ele é capaz de identificar diferentes tipos de doenças pulmonares em imagens médicas.

## Conteúdo

- [Visão Geral](#visão-geral)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Utilizar](#como-utilizar)
- [Modelo Treinado](#modelo-treinado)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral

Este projeto foi desenvolvido com o objetivo de auxiliar profissionais da saúde no diagnóstico de doenças pulmonares através de imagens de raio-X ou tomografias computadorizadas. Utilizando o Teachable Machine para treinamento e técnicas de processamento de imagem, o classificador é capaz de reconhecer e categorizar imagens de acordo com diferentes doenças, como COVID-19, pneumonia bacteriana, entre outras.

## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **Teachable Machine**
- **HTML**
- **CSS**
- **JavaScript**

## Como Utilizar

Você pode abrir o link e selecionar uma imagem local ou caso nao tenha escolha uma do diretório `test_image`

Para utilizar este classificador localmente, siga os passos abaixo:

1. Clone este repositório em sua máquina local:

   ```
   git clone https://github.com/andredevsec/Classificador-Doenca-Pulmonar.git
   ```

2. Abra o diretório clonado em um servidor local. Você pode usar o Python para isso, por exemplo:

   ```
   cd Classificador-Doenca-Pulmonar
   python -m http.server
   ```

3. Acesse o servidor local no navegador web. Você pode acessar o endereço `http://localhost:8000` ou outro endereço fornecido pelo servidor local.

4. Na página web, você pode selecionar uma das imagens do diretório `test_image` para verificar o funcionamento do classificador. Também é possível tentar usar uma imagem própria para classificar.

## Modelo Treinado

Os datasets foram retirados do Kaggle e utilizados para treinar o modelo no Teachable Machine.

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir com este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.