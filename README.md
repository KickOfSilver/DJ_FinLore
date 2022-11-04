[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/eritislami/evobot)

# 🎵 Finlore (Discord Music Bot)
> DJ FinL é um bot feito usando discord.js [discordjs.guide](https://discordjs.guide)

## Instalação

1. Como obter um token de bot de discórdia **[Guia](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot**
2. YouTube Data API v3 Key **[Guia](https://developers.google.com/youtube/v3/getting-started)**  
3. SoundCloud não fornece mais API**
4. Node.js v12.0.0 ou mais recente

---

## 🔎 Fazendo o projeto

Após o acabamento da instalação, você pode usar `node index.js` para iniciar o bot.

```
Digite (npm i) no console
```

🚨🚨 **não compartilhe seu token para outras pessoas ou torná-lo público é estritamente proibido. Então, não compartilhe seu token a nenhum custo ou use .gitignore para ocultar segredos** 🚨🚨

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "STAY_TIME": 30,
  "LOCALE": "pt_br",
  "support_server": "",
  "DEFAULT_VOLUME": 100
}
```

Os locais atualmente disponíveis são:

• English (en)
• French (fr)
• Spanish (es)
• Turkish (tr)
• Korean (ko)
• Brazilian Portuguese (pt_br)
• Simplified Chinese (zh_cn)
• Traditional Chinese (zh_tw)

## 📝 Features & Commands

> Nota: o prefixo padrão é '!!'

* 🎶 Usando URL do YouTube

`/play youtube_link`

* 🔎 Tocando música via nome

`/play Marshmello, Khalid - Numb`

* 🔎 Pesquise e reproduza

`/search Imperial March Trap Remix by Goblins from Mars`