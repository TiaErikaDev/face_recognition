# face_recognition

## Projeto de Reconhecimento Facial

Este é um projeto de reconhecimento facial que utiliza a biblioteca `face_recognition` para identificar e reconhecer rostos em imagens. O projeto é configurado para treinar um modelo com imagens conhecidas e utilizar esse modelo para reconhecer rostos em novas imagens.

## Descrição

O projeto tem como objetivo demonstrar o uso de técnicas de reconhecimento facial com a biblioteca `face_recognition`. Ele inclui funcionalidades para:
- Treinar o modelo com imagens de pessoas conhecidas.
- Reconhecer e identificar rostos em imagens desconhecidas.
- Exibir os resultados com a detecção e anotação dos rostos nas imagens.

## Requisitos

- Python 3.9 ou superior
- Bibliotecas Python necessárias (listadas abaixo)

## Instalação

1. **Clone o Repositório:**

   ```bash
   git clone https://github.com/TiaErikaDev/face_recognition.git
   cd face_recognition
   
2. **Crie um Ambiente Virtual (opcional, mas recomendado):**

   ```bash
   python3 -m venv venv
   source venv/bin/activate

3. **Instale as Dependências:**
   Certifique-se de que as dependências necessárias estão instaladas. Você pode instalar usando pip:

   ```bash
   pip install -r requirements.txt

## Uso

1. Treinar o Modelo com Imagens Conhecidas:
Coloque as imagens das pessoas conhecidas na pasta training e execute:
    ```bash
    python detector.py --train

2. Reconhecer Rostos em Imagens Desconhecidas:
Coloque a imagem na qual deseja realizar a identificação na pasta apropriada e execute:
    ```bash
    python detector.py --test --image_location path/to/your/image.jpg
    
## Estrutura do Projeto
detector.py: Script principal para treinar e testar o modelo de reconhecimento facial.
training/: Pasta contendo imagens conhecidas para treinamento.
unknown/: Pasta para colocar imagens para teste.

## Contribuição
1. Faça um Fork do Repositório.

2. Crie uma Branch para sua Feature:
    ```bash
    git checkout -b minha-feature
    
3. Faça Commits das Suas Alterações:
    ```bash
    git commit -am 'Adiciona nova feature'

4. Faça o Push para a Branch:
    ```bash
    git push origin minha-feature
    
5. Crie um Pull Request no GitHub.

## Licença
Este projeto está licenciado sob a Licença MIT.

## Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.

 - Nome: Erika Pimentel
 - Email: erikamayarapimentel@gmail.com
 - GitHub: TiaErikaDev
