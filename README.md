# Site de Streaming com Controle por Gestos de Mão
### Visão Geral do Projeto
Este projeto é um site de streaming que permite aos usuários controlar o mouse usando gestos de mão. Utiliza a tecnologia de reconhecimento de mão do Google com JavaScript para a detecção de gestos e HTML para a interface. O projeto é construído com Node.js e usa Browser-Sync para iniciar e sincronizar a aplicação.

### Funcionalidades
- Controle do cursor do mouse usando gestos de mão.

- Interface de streaming com controles básicos.

- Reconhecimento e resposta em tempo real a gestos de mão.


### Tecnologias Utilizadas

- **JavaScript:** Para reconhecimento de gestos de mão e marcos faciais, além de manipulação das interações do usuário.

- **TensorFlow.js:** Para a implementação do reconhecimento de gestos de mão e detecção de marcos faciais.

- **HTML/CSS:** Para criação da interface do usuário.

- **Node.js:** Ambiente de execução do backend.

- **Browser-Sync:** Para recarregamento ao vivo e sincronização 
durante o desenvolvimento.

### Configuração e Instalação

#### Clone o Repositório
````bash
git clone https://github.com/FlazO0/Streaming.git
cd Streaming
````

#### Instale as Dependências

Certifique-se de ter o Node.js instalado. Em seguida, instale os pacotes necessários do Node.js:

````bash
npm install
````

#### Inicie a Aplicação

Use o Browser-Sync para iniciar a aplicação com recarregamento ao vivo:

````bash
npx browser-sync -w
````

Isso abrirá a aplicação no seu navegador padrão e recarregará automaticamente quando você fizer alterações nos arquivos.

#### Uso
````
Abra a aplicação no seu navegador web.

O sistema irá pedir acesso a sua camera.

A interface detectará seus gestos de mão usando a câmera e moverá a ilustração da mão diacordo.

Use gestos de mão para interagir com os controles de streaming (ex: abra a mão por completo pra subir feche a mão por completo para descer.).
````