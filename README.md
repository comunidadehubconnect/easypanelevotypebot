<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2024/04/logo_github.png" width="240" />
<p align="center">Seja bem-vindo ao Guia de Instalação Chatwoot+Evolution+Typebot 🚀</p>
</p>
  
<p align="center"> 
<a href="https://hubconnect.top" target="_blank">👉 Participe da Comunidade HubConnect 👈</a>
</p>

<hr />
<hr />

## Comando para Instalar EasyPanel

```bash
curl -sSL https://get.easypanel.io | sh
```

Crie Projects

![48098512-1c18b7b28300a0bfa7a21c97deb109fe](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/aaad7bdb-64f3-480f-a311-098fc3ca8220)


Adicione nome de Project

![48098522-0c485df00f5cadb0d329061c35fee46c](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/b72c1359-91ca-4bf6-9fb1-32525ba5747b)

## Vamos Instalar Chatwoot

Clique na aba Templates

![48098535-90f9b4f370bb8b06cfd7e4acf0ee0f97](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/03c1830c-621c-40b3-94ee-93eb568c8d2e)

Localize APP Chatwoot, clique nele

![48098554-b51ae806b9ed93f6a7b1cccc37ed62c8](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/2d97bbb3-50c4-4e12-b87a-5673c14e7f23)

Nessa tela troque idioma e Imagem docker, clique me Create

![48098583-e5b73cced4eb56836a2b2c18645c442c](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/2e88be4b-75bf-4b8e-810f-21db54c7b3a9)

```bash
chatwoot/chatwoot:latest
```

```bash
pt_BR
```

Clique em Go to Project

![48098610-7d30b35fd2e3b6dee2e329b957c726d7](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/6e76a069-024e-4076-a082-1187efb825d9)

Clique Icone marcado no print abaixo e faça seu cadastro

![48098622-3c44bfa8fa7202daa7e9a93d14c0933a](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/ad675e5e-b193-43b8-b4c0-fb7d57286c0b)

## Ajuste adicional

No adicionar URL na variável do Chatwoot Sidekiq, depois mande fazer DEPLOY

![image](https://github.com/user-attachments/assets/cf4506f8-9ba0-4112-815c-38ee26b56d3d)

FRONTEND_URL=https://www.meu.com.br

## Clique na aba Templates instalar Evolution

![48098535-90f9b4f370bb8b06cfd7e4acf0ee0f97](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/03c1830c-621c-40b3-94ee-93eb568c8d2e)

Localize Evolution, clique nele

![image](https://github.com/user-attachments/assets/f640fe0c-f363-4020-9975-02f2f72e9735)

Cliqeue em Create

![image](https://github.com/user-attachments/assets/53f7278c-1444-4e5c-ae34-5d1f9034f504)


Clique em Go to Project

![48098610-7d30b35fd2e3b6dee2e329b957c726d7](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/6e76a069-024e-4076-a082-1187efb825d9)


Clique Icone marcado no print, coloque dominio/manager

![image](https://github.com/user-attachments/assets/5f73f214-0560-45ab-80dc-12b675414a5e)


Nessa tela adicione API Global 

429683C4C977415CAAFCCE10F7D57E11

![image](https://github.com/user-attachments/assets/e925dbef-b419-45c2-91d6-0d3e65390682)


## Vamos na aba Templates, localize Typebot clique em cima dele

![48098867-1f193bf0502665271ad9a61741724f5a](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/656d552f-4152-4670-8424-837c3edf0fb0)

![48098877-369c271a9da0a7a8e8a1bc22806dbf2e](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/e0243b00-9bdc-48a3-8ab1-8cea763a89d7)

Dois campos abaixo vai colocar 

```bash
https://builder.dominio.easypanel.host
```

```bash
https://viewer.dominio.easypanel.host
```

![48098918-e15e56041dbfe36ba6c11bf276b5e8f4](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/2d41d589-35d7-4544-aa98-db9790f534cc)

Em Github Client ID* e Github Client ID* coloque qualquer coisa, não vamos usa-lo, lugar usaremos smtp

![48098946-9a7bc558b3fed0bc871f4dee67392da8](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/536468b9-6f19-418d-abac-ab7e482ce9d5)

Em Environment adicione variaveis de SMTP no final de parecer com esse

```bash
DATABASE_URL=postgres://postgres:c298a1247ecaee9df640@$(PROJECT_NAME)_typebot-db:5432/$(PROJECT_NAME)
NEXTAUTH_URL=https://builder.dominio.easypanel.host
NEXT_PUBLIC_VIEWER_URL=https://viewer.dominio.easypanel.host
ENCRYPTION_SECRET=be13eedd3c063fd099175d65ab5f304b
ADMIN_EMAIL=contato@dominio.com.br
DISABLE_SIGNUP=false
ADMIN_EMAIL=contato@dominio.com.br
NEXT_PUBLIC_SMTP_FROM='Suporte' <contato@dominio.com.br>
SMTP_AUTH_DISABLED=false
SMTP_USERNAME=contato@dominio.com.br
SMTP_PASSWORD=SenhadSMTP
SMTP_HOST=smtp.dominio.com.br
SMTP_PORT=465
SMTP_SECURE=true
S3_ACCESS_KEY=minio
S3_SECRET_KEY=1c79420ac1dd742d625d
S3_BUCKET=typebot
S3_ENDPOINT=http://$(PROJECT_NAME)_typebot-minio:9000
```

![48098960-e885495cf9ec690ba46f0b97068008fa](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/8080e201-f15c-40d6-99f4-55886298baf2)

Mande executar DEPLOY

![48098978-79214e0a2541429040e68a101b3f44d9](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/a3ae51ba-894f-4c36-b185-555c284227a7)

Clique no Icone para abrir Typebot, coloque email cadastrado no SMTP, recebera link em seu email, para accessa Typebot

![48099001-7406354be1635d5a0f827411729b083c](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/f11193c7-91f5-4422-8f94-c348c9990fee)


**Pronto tudo Funcionando** ✅😎





