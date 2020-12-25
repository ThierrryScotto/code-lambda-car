## Descrição do porjeto. 

Esse projeto foi criado para estudos das ferramenta Lambda presente na AWS.
Um crud bem simples usado para cadastrar carros. Seguindo os conceitos de API Restfull.

**Contêm os seguintes métodos**
- POST
- PUTCH
- DELETE
- GET

![image](https://user-images.githubusercontent.com/37625040/103141172-55683780-46cf-11eb-9029-c7a39b3ac5d8.png)

## Rotas e Model

```bash
  model:           { type: String, required: true },
  totalKilometers: { type: String, required: true },
  year:            { type: String, required: true },
  dailyValue:      { type: Number, required: true },
  airConditioning: { type: Boolean, required: true },
  clutch:          { type: String, required: true },
  doors:           { type: Number, required: true },
  seats:           { type: Number, required: true },
  status:          { type: Number, default: 1 },      1 - active / 0 - deactivated
```

POST - https://5qaw791890.execute-api.us-east-1.amazonaws.com/v1/cars <br/>
PATCH - https://5qaw791890.execute-api.us-east-1.amazonaws.com/v1/cars/{carId} <br/>
DELETE - https://5qaw791890.execute-api.us-east-1.amazonaws.com/v1/cars/{carId} <br/>
GET - https://5qaw791890.execute-api.us-east-1.amazonaws.com/v1/cars/{carId} <br/>
GET - https://5qaw791890.execute-api.us-east-1.amazonaws.com/v1/cars 

## :rocket: Tecnologias 

-  [Node.js](https://nodejs.org)
-  [Lambda](https://aws.amazon.com/pt/lambda/)
-  [MongoDB](https://www.mongodb.com/)
-  [serverless-offline](https://github.com/dherault/serverless-offline)
