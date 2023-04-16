{
  "Version": "1.0.28",
  "ReleaseNotes": "➡️ ATUALIZAÇÃO DISPONÍVEL ⬅️\n ••••\n
🔰 V: 1.0.28 | Horas: 08:43:07 | 16/04/2023 🔰\n
••••\n
⚠️ MURAL DE AVISOS: NOVA PAYLOAD OU AJUSTES DAS ATUAIS\n
••••••••••••••••••••\n
🚀uma dica; recomendamos ter 2 chips de operadoras diferentes, caso uma rede caia 
você tem a outra para
conectar tranquilamente.
\nAtiva e desativa o modo avião do seu aparelho algumas vezes se não conectar de primeira isso servirá para mudar o IP local do seu chip.
",
  "UrlUpdate": "https://raw.githubusercontent.com/SSHFOXBR/socks-lord-king/main/README.md",
  "Sms": "https://paste.anasor.com/paste.php?raw&id=341041",
  "EmailFeedback": "#",
  "UrlContato": "https://sshfox.com/app",
  "UrlTermos": "https://sshfox.com/termos/",
  "CheckUser": "true",
  "UdpPort": "7300",
  "Udp": [   
    {
      "Porta": "7300"
    },  
  ],
  "Servers": [
    {
      "Name": "Servidor: A",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "net.sshfoxbr.xyz",      
      "CheckUser": "http://209.14.71.99:5000/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    },
{
      "Name": "Servidor: B",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "t.topspeed.ml",
      "ServerIP": "apptest.c6bank.app",
      "CheckUser": "http://209.14.71.99:5000/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }, 
      
  ],
  "Networks": [
    
         {
      "Name": "VIVO 01 Servidor: A",
      "FLAG": "vivo",
      "Payload": "POST /connect/domainreliability/upload HTTP/1.1 [lf]Host: [app_host] [split][crlf]Upgrade: Websocket;Access-Control-Request-Method: POST;Access-Control-Allow-Origin: *;Save-Data: no;Connection: keep-alive;Keep-Alive: timeout=43200, max=71200;Cache-control: public max-age=16777216 immutable;Content-Length: 16777216;Upgrade-Insecure-Requests: 1/n/n[crlf][crlf]", 
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.51.111",
      "ProxyPort": "80",
      "Info": "Proxy"
  
   },
        {
            "Name": "VIVO 02 Servidor: A",
            "FLAG": "vivo",
            "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf][crlf]",
            "SNI": "",
            "TlsIP": "104.16.53.111",
            "ProxyIP": "104.16.53.111",
            "ProxyPort": "80",
            "Info": "Proxy"
        },
        {
            "Name": "VIVO 03 Servidor: A",
            "FLAG": "vivo",
            "Payload": "BASELINE-CONTROL wss://cardinalcommerce.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
            "SNI": "songbird.cardinalcommerce.com",
            "TlsIP": "198.217.251.250",
            "ProxyIP": "198.217.251.250",
            "ProxyPort": "443",
            "Info": "Tlsws"
        },
{
      "Name": "VIVO 04 Servidor: A",
      "FLAG": "vivo",
      "Payload": "POST /connect/domainreliability/upload HTTP/1.1 [lf]Host: [app_host] [split][crlf]Upgrade: Websocket;Access-Control-Request-Method: POST;Access-Control-Allow-Origin: *;Save-Data: no;Connection: keep-alive;Keep-Alive: timeout=43200, max=71200;Cache-control: public max-age=16777216 immutable;Content-Length: 16777216;Upgrade-Insecure-Requests: 1/n/n[crlf][crlf]", 
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.51.111",
      "ProxyPort": "80",
      "Info": "Proxy"
  
   },
{
      "Name":"VIVO 05 Servidor: A",
      "FLAG":"vivo",
      "Payload":"GET-CONTROL ws://net.sshfoxbr.xyz HTTP/1.1[crlf]Host: itsupport.surveymonkey.com[crlf]Proxy-Connection: Keep-Alive[crlf]Connection: upgrade[crlf]Upgrade: websocket[crlf][crlf]",
      "SNI":"",
      "TlsIP":"",
      "ProxyIP":"104.16.51.111",
      "ProxyPort":"80",
      "Info":"Proxy"
  
   },
    {
      "Name":" VIVO 06 Servidor: A",
      "FLAG":"vivo",
      "Payload":"GET-CONTROL ws://net.sshfoxbr.xyz HTTP/1.1[crlf]Host: itsupport.surveymonkey.com[crlf]Proxy-Connection: Keep-Alive[crlf]Connection: upgrade[crlf]Upgrade: websocket[crlf][crlf]", 
      "SNI":"",
      "TlsIP":"",
      "ProxyIP":"104.16.51.111",
      "ProxyPort":"80",
      "Info":"Proxy"
    },
{
      "Name": "VIVO 07 Servidor: A",
      "FLAG": "vivo",
      "Payload": "BASELINE-CONTROL wss://[app_host] HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]TOPSPEED[crlf][crlf]",
            "SNI":"[app_host]",
            "TlsIP":"servicedesk.resultadosdigitais.com.br",
            "ProxyIP":"",
            "ProxyPort":"443",
            "Info":"Tlsws"
    },
{
      "Name": "VIVO 08 Servidor: A",
      "FLAG": "vivo",
      "Payload": "JHOW-CONTROL / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket: Averest-Cam[crlf][crlf]",
      "SNI": "faq.foxbit.com.br",
      "TlsIP": "faq.foxbit.com.br",
      "ProxyIP": "faq.foxbit.com.br",
      "ProxyPort": "80",
      "Info": "Proxy"
     },
{
      "Name": "VIVO 09 Servidor: A",
      "FLAG": "vivo",
      "Payload": "GET-TOPSPEED wss://[app_host]/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]TOPSPEED[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.51.111",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
   {
      "Name": "VIVO 10 Servidor: A",
      "FLAG": "vivo",
      "Payload": "GET-TOPSPEED wss://[app_host]/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]TOPSPEED[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.53.111",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
   "Name": "VIVO 11 Servidor: A",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "104.18.11.117",
      "ProxyIP": "104.18.11.117",
      "ProxyPort": "80",
      "Info": "Proxy"
  },
{
      "Name": "VIVO 12 Servidor: A",
      "FLAG": "vivo",
      "Payload": "BASELINE-CONTROL / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },

{
      "Name": "VIVO 13 Servidor: A",
      "FLAG": "vivo",
      "Payload": "GET-MATRIX wss://net.sshfoxbr.xyz/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "net.sshfoxbr.xyz",
      "TlsIP": "support.deezer.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO 14 Servidor: A",
      "FLAG": "vivo",
      "Payload": "GET-MATRIX wss://net.sshfoxbr.xyz/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "net.sshfoxbr.xyz",
      "TlsIP": "support.deezer.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
{
      "Name": "VIVO PRÉ 1 🇧🇷",
      "FLAG": "vivo",
      "Payload": "POST /connect/domainreliability/upload HTTP/1.1 [lf]Host: net.sshfoxbr.xyz[split][crlf]Upgrade: Websocket;Access-Control-Request-Method: POST;Access-Control-Allow-Origin : *;Save-Data: não;Connection: keep-alive;Keep-Alive: timeout=43200, max=71200;Cache-control: public max-age=16777216 immutable;Content-Length: 16777216;Upgrade-Insecure-Requests : 1/n/n[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.51.111",
      "ProxyPort": "80",
      "Info": "Proxy"
  
   },
{
      "Name": "VIVO PRÉ 2 🇧🇷",
      "FLAG": "vivo",
      "Payload": "GET-CONTROL ws://net.sshfoxbr.xyz HTTP/1.1[crlf]Host: itsupport.surveymonkey.com[crlf]Proxy-Connection: Keep-Alive[crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.51.111",
      "ProxyPort": "80",
      "Info": "Proxy"
   },
{
      "Name": "VIVO PRÉ 3 🇧🇷",
      "FLAG": "vivo",
      "Payload": "POST /connect/domainreliability/upload HTTP/1.1 [lf]Host: net.sshfoxbr.xyz[split][crlf]Upgrade: Websocket;Access-Control-Request-Method: POST;Access-Control-Allow-Origin : *;Save-Data: não;Connection: keep-alive;Keep-Alive: timeout=43200, max=71200;Cache-control: public max-age=16777216 immutable;Content-Length: 16777216;Upgrade-Insecure-Requests : 1/n/n[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.53.111",
      "ProxyPort": "80",
      "Info": "Proxy"
  
   },        
{
    "Name": "TIM 01 Servidor: B",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: appdev.c6bank.app[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- // HTTP/1.1[crlf]Host:net.sshfoxbr.xyz [crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
      "SNI": "",
      "TlsIP": "104.16.53.111",
      "ProxyIP": "",
      "ProxyPort": "80",
      "Info": "Direct"
  },
  {
      "Name": "TIM 02 Servidor: B",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: landing.stoodi.com.br[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- // HTTP/1.1[crlf]Host:net.sshfoxbr.xyz [crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
      "SNI": "",
      "TlsIP": "104.19.249.25",
      "ProxyIP": "",
      "ProxyPort": "80",
      "Info": "Direct"
   },
{
    "Name": "TIM 03 Servidor: B",
      "FLAG": "tim",
      "Payload": "GET wss://www.c6bank.app/ HTTP/1.1[crlf]Host: www.c6bank.app[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL /?/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
      "SNI": "",
      "TlsIP": "104.19.239.25",
      "ProxyIP": "",
      "ProxyPort": "80",
      "Info": "Direct"
  },
  {
    "Name": "TIM 04 Servidor: B",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: image.mail.c6bank.com.br[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- // HTTP/1.1[crlf]Host:net.sshfoxbr.xyz [crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
      "SNI": "",
      "TlsIP": "104.19.241.25",
      "ProxyIP": "",
      "ProxyPort": "80",
      "Info": "Direct"
  },
{
      "Name": "TIM 05 Servidor: B",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: www.c6bank.app[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- // HTTP/1.1[crlf]Host:net.sshfoxbr.xyz [crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
      "SNI": "",
      "TlsIP": "104.18.28.182",
      "ProxyIP": "",
      "ProxyPort": "80",
      "Info": "Direct"
    },
{
    "Name": "TIM 06 Servidor: B",
    "FLAG": "tim",
    "Payload": "GET / HTTP/1.1[crlf]Host: support.deezer.com[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- /?/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf]TOPSPEED[crlf][crlf]",
    "SNI": "",
    "TlsIP": "",
    "ProxyIP": "t.topspeed.ml",
    "ProxyPort": "80",
    "Info": "Direct"
    },
{
    "Name": "TIM 07 Servidor: B",
    "FLAG": "tim",
    "Payload": "GET / HTTP/1.1[crlf]Host: support.deezer.com[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- /?/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf]TOPSPEED[crlf][crlf]",
    "SNI": "",
    "TlsIP": "",
    "ProxyIP": "t.topspeed.ml",
    "ProxyPort": "80",
    "Info": "Direct"
    },
{
    "Name": "TIM 08 Servidor: B",
    "FLAG": "tim",
    "Payload": "GET / HTTP/1.1[crlf]Host: support.deezer.com[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- /?/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf]TOPSPEED[crlf][crlf]",
    "SNI": "",
    "TlsIP": "",
    "ProxyIP": "t.topspeed.ml",
    "ProxyPort": "80",
    "Info": "Direct"
    },
{
    "Name": "TIM 09 Servidor: B",
    "FLAG": "tim",
    "Payload": "GET / HTTP/1.1[crlf]Host: support.deezer.com[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]ACL- /?/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf]TOPSPEED[crlf][crlf]",
    "SNI": "",
    "TlsIP": "",
    "ProxyIP": "t.topspeed.ml",
    "ProxyPort": "80",
    "Info": "Direct"
    },
{
            "Name": "🌐TIM NA VALIDADE 1🎮",
            "FLAG": "tim",
            "Payload": "GET / HTTP/1.1[crlf]Host: jobs.deezer.com[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]PUT- // HTTP/1.1[crlf]Host: net.sshfoxbr.xyz [crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
            "SNI": "",
            "TlsIP": "",
            "ProxyIP": "support.deezer.com",
            "ProxyPort": "80",
            "Info": "Proxy"
        },
        {
            "Name": "🌐TIM NA VALIDADE 2🎮",
            "FLAG": "tim",
            "Payload": "GET / HTTP/1.1[crlf]Host: creatorsupport.deezer.com[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]PUT- // HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
            "SNI": "",
            "TlsIP": "",
            "ProxyIP": "104.16.51.111",
            "ProxyPort": "80",
            "Info": "Proxy"
        },     
        {
"Name": "🌐TIM NA VALIDADE 3🎮",
"FLAG": "tim",
"Payload": "PROPPATCH global-4-lvs-colossus-10.opera-mini.net HTTP/1.0[crlf]Host: net.sshfoxbr.xyz Host:global-4-lvs-colossus-10.opera-mini.net[crlf]",
"SNI": "",
"TlsIP": "",
"ProxyIP": "global-4-lvs-colossus-10.opera-mini.net",
"ProxyPort": "80",
"Info": "Proxy"
},
{
    "Name": "CLARO 01 Servidor: A",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "api.web.whatsapp.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Ssl"   
    },
{
    "Name": "CLARO 02 Servidor: A",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "waze.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Ssl"   
    },
    {
      "Name": "CLARO 03 Servidor: A",
      "FLAG": "claro",
      "Payload": "GET https://flex.claro.com.br/HTTP/1.0[crlf]host: net.sshfoxbr.xyz[crlf]Connection: keep-alive[crlf]User-Agent: Upgrade [crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "149.78.184.22",
      "ProxyPort": "80",
      "Info": "Proxy"
   },

    {
            "Name": "OI 01 Servidor: A",
            "FLAG": "OI",
            "Payload": "BASELINE-CONTROL wss://cardinalcommerce.com/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
            "SNI": "songbird.cardinalcommerce.com",
            "TlsIP": "198.217.251.250",
            "ProxyIP": "198.217.251.250",
            "ProxyPort": "443",
            "Info": "Tlsws"
        },
        {
            "Name": "OI 02 Servidor: A",
            "FLAG": "oi",
            "Payload": "BASELINE-CONTROL wss://cardinalcommerce.com/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
            "SNI": "songbird.cardinalcommerce.com",
            "TlsIP": "198.217.251.250",
            "ProxyIP": "198.217.251.250",
            "ProxyPort": "443",
            "Info": "Tlsws"
        },
        {
            "Name": "OI 03 Servidor: A",
            "FLAG": "oi",
            "Payload": "BASELINE-CONTROL wss://cardinalcommerce.com/ HTTP/1.1[crlf]Host: net.sshfoxbr.xyz[crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
            "SNI": "songbird.cardinalcommerce.com",
            "TlsIP": "198.217.251.250",
            "ProxyIP": "198.217.251.250",
            "ProxyPort": "443",
            "Info": "Tlsws"
        }  
  ]
}
