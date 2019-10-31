# DominicanWhoCodes

Open source project inspired in http://indianswhodesign.in, made to expose all the developers from the Dominican Republic with their skills and contacts.

The idea is to have this directoy where you could find the Dominicans devs info, this project is basically for me and @ManuHernandez (and everybody who want to collaborate) to learn/use some of the main JS front-end frameworks (Angular, Vue and React), play with some WebAssembly technologies like Blazor and also implement a Microservices Architecture.

See the [Roadmap](https://github.com/AngelGarcia13/DominicanWhoCodes/blob/master/Roadmap.md) for more technical details.

#### Join our Slack.

https://join.slack.com/t/dominicanwhocodes/shared_invite/enQtNzU0MjQ2OTY1MDk1LTcyMTUwODJkNTM2ZTQwYTQ0OWM4ODc4ZTBiOWU1N2Q0ZGY5NmJjZjExZjBjNTE0NGQ2ZjVjZTM2MDBjNmMzNDc

#### Join out WhatsApp Group

https://chat.whatsapp.com/L5rFQpme22IHmmyOMI1MWA

### Blazor Client App.

🚀 Amazon S3 Bucket: http://www.dominicanwho.codes.s3-website-us-east-1.amazonaws.com/

🚀 Azure WebApp (Free Tier, could be stopped anytime): http://dominicanwhocodes.azurewebsites.net/

## Project setup

```
npm install
```

## Configure the .env file

```
cp .env.example .env
```

## Serve a "local API" with the developers data
```
npm run serve-data
```
Configure the `VUE_APP_API_URL` from `.env` file with the domain of `json-server`, example `VUE_APP_API_URL=http://localhost:3000`

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
