# ZHACK Labs Writeups

Repositorio donde recopilo mis **writeups** de los laboratorios de **ZHACK Labs**.

El objetivo de este repositorio es documentar el proceso de resolución de cada laboratorio, explicando la vulnerabilidad, el análisis realizado y la explotación paso a paso de forma sencilla, especialmente para personas que están empezando en ciberseguridad.

> **Nota:** Todos los laboratorios pertenecen a **ZHACK Labs**. Este repositorio contiene únicamente mis explicaciones y notas personales.

---

## Estructura

Los writeups están organizados por categorías de vulnerabilidades. Cada categoría tiene su propio `README.md` con el detalle de dificultad y estado de cada laboratorio, y cada laboratorio tiene su writeup y su carpeta de capturas (`img/`).

- [01 - Inyección SQL](./01-inyeccion-sql/)
  - [01 - Papelia Sqli Filtro Categoria](./01-inyeccion-sql/01-papelia-sqli-filtro-categoria/)
  - [02 - Orbix Bypass Login SQLi](./01-inyeccion-sql/02-orbix-bypass-login-sqli/)
  - [03 - Helio SQLi Ciega Booleana](./01-inyeccion-sql/03-helio-sqli-ciega-booleana/)
  - [04 - Trackpost SQLi Numerica](./01-inyeccion-sql/04-trackpost-sqli-numerica/)
  - [05 - Vantia Union Enumeracion Esquema](./01-inyeccion-sql/05-vantia-union-enumeracion-esquema/)
  - [06 - Kordata Union Ato](./01-inyeccion-sql/06-kordata-union-ato/)
  - [07 - Novex Union Bypass WAF](./01-inyeccion-sql/07-novex-union-bypass-waf/)
- [02 - Cross-Site Scripting (XSS)](./02-xss/)
  - [01 - Trackpoint XSS Reflejado Seguimiento](./02-xss/01-trackpoint-xss-reflejado-seguimiento/)
  - [02 - Rumbo XSS Almacenado Comentarios](./02-xss/02-rumbo-xss-almacenado-comentarios/)
  - [03 - Cinexa DOM XSS Buscador](./02-xss/03-cinexa-dom-xss-buscador/)
  - [04 - Talentia XSS Reflejado Atributo HTML](./02-xss/04-talentia-xss-reflejado-atributo-html/)
  - [05 - Meteora XSS Reflejado Cadena JS](./02-xss/05-meteora-xss-reflejado-cadena-js/)
  - [06 - DOM XSS Innerhtml](./02-xss/06-dom-xss-innerhtml/)
  - [07 - Baratix XSS Reflejado Tags Bloqueadas](./02-xss/07-baratix-xss-reflejado-tags-bloqueadas/)
  - [08 - Deskline XSS Almacenado Segundo Orden](./02-xss/08-deskline-xss-almacenado-segundo-orden/)
  - [09 - Kanbo DOM XSS API JSON](./02-xss/09-kanbo-dom-xss-api-json/)
  - [10 - Linkyx DOM XSS Href Javascript](./02-xss/10-linkyx-dom-xss-href-javascript/)
  - [11 - Trendix DOM XSS Document Write](./02-xss/11-trendix-dom-xss-document-write/)
  - [12 - Helpwise XSS Reflejado Bypass CSP](./02-xss/12-helpwise-xss-reflejado-bypass-csp/)
  - [13 - Lumen DOM XSS Client Side Prototype Pollution](./02-xss/13-lumen-dom-xss-client-side-prototype-pollution/)
- [03 - Control de acceso (IDOR / BAC)](./03-control-acceso-idor-bac/)
  - [01 - Aurora Bank IDOR Extracto Claro](./03-control-acceso-idor-bac/01-aurora-bank-idor-extracto-claro/)
  - [02 - Brightline Funcion Admin Sin Proteger](./03-control-acceso-idor-bac/02-brightline-funcion-admin-sin-proteger/)
  - [03 - Aurora Bank IDOR Extracto Base64](./03-control-acceso-idor-bac/03-aurora-bank-idor-extracto-base64/)
  - [04 - Aurora Bank IDOR Extracto MD5](./03-control-acceso-idor-bac/04-aurora-bank-idor-extracto-md5/)
  - [05 - Taskora Mass Assignment Rol](./03-control-acceso-idor-bac/05-taskora-mass-assignment-rol/)
  - [06 - Portalix Bypass Control Referer](./03-control-acceso-idor-bac/06-portalix-bypass-control-referer/)
  - [07 - Aurora Bank IDOR Encadenado UUID](./03-control-acceso-idor-bac/07-aurora-bank-idor-encadenado-uuid/)
  - [08 - Aurora Bank IDOR Escritura Transferencia](./03-control-acceso-idor-bac/08-aurora-bank-idor-escritura-transferencia/)
  - [09 - Aurora Bank IDOR Token Sesion Sin Verificar](./03-control-acceso-idor-bac/09-aurora-bank-idor-token-sesion-sin-verificar/)
  - [10 - Meridian Data Room IDOR Documentos Confidenciales](./03-control-acceso-idor-bac/10-meridian-data-room-idor-documentos-confidenciales/)
- [04 - Autenticación](./04-autenticacion/)
  - [01 - Nucleo Enumeracion Usuarios Fuerza Bruta](./04-autenticacion/01-nucleo-enumeracion-usuarios-fuerza-bruta/)
  - [02 - Codexa Bypass 2FA Token Pre 2FA](./04-autenticacion/02-codexa-bypass-2fa-token-pre-2fa/)
  - [03 - Klaris Bypass 2FA Manipulacion Respuesta](./04-autenticacion/03-klaris-bypass-2fa-manipulacion-respuesta/)
  - [04 - Voltix Fuerza Bruta Multi Credencial](./04-autenticacion/04-voltix-fuerza-bruta-multi-credencial/)
  - [05 - Zephyr Bypass Login Inyeccion NoSQL](./04-autenticacion/05-zephyr-bypass-login-inyeccion-nosql/)
- [05 - SSRF](./05-ssrf/)
  - [01 - Fibra SSRF Vista Previa Enlaces](./05-ssrf/01-fibra-ssrf-vista-previa-enlaces/)
  - [02 - Snapix SSRF Proxy Imagenes](./05-ssrf/02-snapix-ssrf-proxy-imagenes/)
  - [03 - Fibra SSRF Bypass Filtro Metadata Cloud](./05-ssrf/03-fibra-ssrf-bypass-filtro-metadata-cloud/)
  - [04 - Pulse SSRF Escaneo Puertos Interno](./05-ssrf/04-pulse-ssrf-escaneo-puertos-interno/)
  - [05 - Promptia SSRF Asistente IA](./05-ssrf/05-promptia-ssrf-asistente-ia/)
  - [06 - Relay SSRF Bypass Redireccion Abierta](./05-ssrf/06-relay-ssrf-bypass-redireccion-abierta/)
  - [07 - Beacon SSRF Bypass Allowlist Host Confusion](./05-ssrf/07-beacon-ssrf-bypass-allowlist-host-confusion/)
  - [08 - Forge SSRF Redis Gopher](./05-ssrf/08-forge-ssrf-redis-gopher/)
- [06 - Lógica de negocio](./06-logica-negocio/)
  - [01 - Riftbound Price Tampering](./06-logica-negocio/01-riftbound-price-tampering/)
  - [02 - Riftbound Cantidad Negativa](./06-logica-negocio/02-riftbound-cantidad-negativa/)
  - [03 - Riftbound Race Condition Codigo Promo](./06-logica-negocio/03-riftbound-race-condition-codigo-promo/)
  - [04 - Zenith Wallet Doble Gasto Race Condition](./06-logica-negocio/04-zenith-wallet-doble-gasto-race-condition/)
  - [05 - Rivet Race Condition Cambio Correo](./06-logica-negocio/05-rivet-race-condition-cambio-correo/)
  - [06 - Arcadium Bypass Limite Intentos](./06-logica-negocio/06-arcadium-bypass-limite-intentos/)
  - [07 - Reventa Bucle Reembolso Saldo](./06-logica-negocio/07-reventa-bucle-reembolso-saldo/)
- [07 - Bug Bounty Real](./07-bug-bounty-real/)
  - [01 - Doble Cuenta Mismo Email](./07-bug-bounty-real/01-doble-cuenta-mismo-email/)
  - [02 - Pedido Confirmado Sin Pagar](./07-bug-bounty-real/02-pedido-confirmado-sin-pagar/)
  - [03 - Solvia XSS Reflejado Login Bancario Bypass WAF](./07-bug-bounty-real/03-solvia-xss-reflejado-login-bancario-bypass-waf/)
  - [04 - Aulora Webhook Pago Sin Verificacion Firma](./07-bug-bounty-real/04-aulora-webhook-pago-sin-verificacion-firma/)
  - [05 - Sonari Inyeccion Comandos Nombre Archivo](./07-bug-bounty-real/05-sonari-inyeccion-comandos-nombre-archivo/)
- [08 - API Hacking](./08-api-hacking/)
  - [01 - Facturia BOLA Facturas](./08-api-hacking/01-facturia-bola-facturas/)
  - [02 - Vextra Endpoint API Sin Usar](./08-api-hacking/02-vextra-endpoint-api-sin-usar/)
  - [03 - Mass Assignment Creacion Administrador](./08-api-hacking/03-mass-assignment-creacion-administrador/)
  - [04 - Auditra API Super Admin Sin Autenticacion](./08-api-hacking/04-auditra-api-super-admin-sin-autenticacion/)
  - [05 - Talio Response Manipulation Acceso Portal](./08-api-hacking/05-talio-response-manipulation-acceso-portal/)
  - [06 - Nexora Server Side Parameter Pollution](./08-api-hacking/06-nexora-server-side-parameter-pollution/)
  - [07 - Stackhaus Token Consola Claves Raiz](./08-api-hacking/07-stackhaus-token-consola-claves-raiz/)
  - [08 - Fluxpay Token Developer Liberar Pago](./08-api-hacking/08-fluxpay-token-developer-liberar-pago/)
  - [09 - Corven SSPP URL REST](./08-api-hacking/09-corven-sspp-url-rest/)
- [09 - Prototype Pollution](./09-prototype-pollution/)
  - [01 - Nimbus Server Side Prototype Pollution](./09-prototype-pollution/01-nimbus-server-side-prototype-pollution/)
  - [02 - Nimbus Blind Server Side Prototype Pollution](./09-prototype-pollution/02-nimbus-blind-server-side-prototype-pollution/)
  - [03 - Helix Prototype Pollution Query String](./09-prototype-pollution/03-helix-prototype-pollution-query-string/)
  - [04 - Cobalt Developer Administrador Prototype Pollution](./09-prototype-pollution/04-cobalt-developer-administrador-prototype-pollution/)
- [10 - Account Take Over](./10-account-take-over/)
  - [01 - Novaflix ATO XSS Almacenado](./10-account-take-over/01-novaflix-ato-xss-almacenado/)
  - [02 - Novaflix Password Reset Poisoning](./10-account-take-over/02-novaflix-password-reset-poisoning/)
  - [03 - Stratos ATO OAuth Redirect Uri](./10-account-take-over/03-stratos-ato-oauth-redirect-uri/)
- [11 - Ataques a JWT](./11-ataques-jwt/)
  - [01 - Skyloom JWT Firma No Verificada](./11-ataques-jwt/01-skyloom-jwt-firma-no-verificada/)
  - [02 - Skyloom JWT Clave Firmado Debil](./11-ataques-jwt/02-skyloom-jwt-clave-firmado-debil/)
  - [03 - Skyloom JWT Confusion Algoritmo RS256 HS256](./11-ataques-jwt/03-skyloom-jwt-confusion-algoritmo-rs256-hs256/)
- [12 - HTTP Request Smuggling](./12-http-request-smuggling/)
  - [01 - Trayecto TE CL](./12-http-request-smuggling/01-trayecto-te-cl/)
  - [02 - Trayecto TE TE](./12-http-request-smuggling/02-trayecto-te-te/)
  - [03 - Abaco CL TE](./12-http-request-smuggling/03-abaco-cl-te/)
  - [04 - Abaco TE CL](./12-http-request-smuggling/04-abaco-te-cl/)
  - [05 - Mesa CL TE](./12-http-request-smuggling/05-mesa-cl-te/)
  - [06 - Mesa TE CL Captura Sesion Victima](./12-http-request-smuggling/06-mesa-te-cl-captura-sesion-victima/)
- [13 - Inyección de comandos (OS Command Injection)](./13-os-command-injection/)
  - [01 - Verdemart Inyeccion Salida Reflejada](./13-os-command-injection/01-verdemart-inyeccion-salida-reflejada/)
  - [02 - Halyard Inyeccion Argumentos CLI](./13-os-command-injection/02-halyard-inyeccion-argumentos-cli/)
  - [03 - Pingdesk Inyeccion Ciega Exfil Fichero](./13-os-command-injection/03-pingdesk-inyeccion-ciega-exfil-fichero/)
  - [04 - Fortibox Inyeccion Bypass Filtro](./13-os-command-injection/04-fortibox-inyeccion-bypass-filtro/)
  - [05 - Cronalix Inyeccion Ciega Tiempo](./13-os-command-injection/05-cronalix-inyeccion-ciega-tiempo/)
  - [06 - Certza Inyeccion Fuera Banda OOB](./13-os-command-injection/06-certza-inyeccion-fuera-banda-oob/)
- [14 - CORS](./14-cors/)
  - [01 - Planora CORS Robo Clave API Reflexion Origin](./14-cors/01-planora-cors-robo-clave-api-reflexion-origin/)
  - [02 - Statix CORS Bypass Allowlist Sufijo](./14-cors/02-statix-cors-bypass-allowlist-sufijo/)
  - [03 - Nummo CORS Confianza Origen Null](./14-cors/03-nummo-cors-confianza-origen-null/)
  - [04 - Vaulta CORS Bypass Allowlist Regex](./14-cors/04-vaulta-cors-bypass-allowlist-regex/)
- [15 - Hacking de IA (LLM)](./15-hacking-ia-llm/)
  - [01 - Certia Abuso IA System Prompt](./15-hacking-ia-llm/01-certia-abuso-ia-system-prompt/)
  - [02 - Suptic Prompt Injection Indirecta](./15-hacking-ia-llm/02-suptic-prompt-injection-indirecta/)
  - [03 - Nexo Abuso Herramientas LLM SSRF](./15-hacking-ia-llm/03-nexo-abuso-herramientas-llm-ssrf/)

---

## Objetivos

- Documentar el proceso de resolución de los laboratorios.
- Aprender y reforzar conceptos de seguridad web.
- Compartir explicaciones sencillas y fáciles de seguir.
- Tener un repositorio de referencia para futuras consultas.

---

## Aviso

Estos writeups tienen un propósito **educativo** y están basados en laboratorios diseñados para practicar seguridad informática de forma legal.
No deben utilizarse para realizar pruebas sobre sistemas sin autorización.

---

## Enlaces

- ZHACK Labs: https://labs.zh4ck.es/
- ZHACK Academy: https://zh4ck.es/

---

⭐ Si este repositorio te resulta útil, puedes dejar una estrella.